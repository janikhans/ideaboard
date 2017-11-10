# Idea Board API

Backend API built using Rails 5.1.3

### Setup

Make sure Rails is installed

```
gem install rails -v 5.1.3
```

Navigate to `/ideaboard-api` and run:

    rails db:migrate
    rails db:seed
    rails s -p 3001

CRUD routes for Ideas can be found at `localhost:3001/api/v1/ideas.json`
