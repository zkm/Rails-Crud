# Rails-CRUD

##### Prerequisites

The setups steps expect following tools installed on the system.

- Github
- Ruby [3.1.2]
- Rails [7.0.4]

##### 1. Check out the repository

```bash
git clone git@github.com:zkm/rails-crud.git
```

##### 2. Create and setup the database

Run the following command to create and setup the database.

```ruby
rake db:migrate
```

##### 4. Add some data so we can run tests

Run the following command to seed database.

```ruby
rake db:seed
```

##### 5. Start the Rails server

You can start the rails server using the command given below.

```ruby
bundle exec rails s
```

##### 6. View routes

Run the following command or go to http://localhost:3000/rails/info/routes to see all routes your application is configured to. 

```ruby
rails routes
```

And now you can visit the site with the URL http://localhost:3000/dogs
