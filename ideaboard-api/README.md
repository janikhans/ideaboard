# Idea Board API

Backend API built using Rails 5.1.3

### Setup

Navigate to `/ideaboard-api` and run:

    bundle install
    rails db:migrate
    rails db:seed
    rails s -p 3001

CRUD routes for Ideas can be found at `localhost:3001/api/v1/ideas.json`
