# My API Project Template

This project contains the initial template I like to use in my personal APIs.  

## Database
The configured DB is `PostgreSQL`.  
You need to copy the file with the database configurations with `cp config/database.copy.yml config/database.yml`.  
Then, you will need to make the necessary changes to make it work with your database.  

## Gems
I added the gems:
 - [RSpec Rails](https://github.com/rspec/rspec-rails)
 - [Factory Bot Rails](https://github.com/thoughtbot/factory_bot_rails)
 - [Faker](https://github.com/faker-ruby/faker)
 - [Pry ByeBug](https://github.com/deivid-rodriguez/pry-byebug)
 - [Database Cleaner Active Record](https://github.com/DatabaseCleaner/database_cleaner)

## What I changed in the configurations?
1. I created the RSpec folder with initial configs (`spec_helper` and `rails_helper`).
2. I changed the `spec/spec_helper` file to run the tests randomly and to print the 10 slowest tests.
3. I changed the `spec/rails_helper` file to setup DatabaseCleaner.
4. I changed the `.rspec` file to print the test output as `documentation`.
2. I created the `spec/factories` folder.
3. I changed the generators to create RSpec tests.

## Warning
Please, notice this template might be outdated by the time you are using (I don't know how often I will update it), and I do not guarantee this is going to work right after you use it (more configurations may be needed).
