#RailsStarter

Inspired by [connorjacobsen/rails_starter](https://github.com/connorjacobsen/rails_starter), this is my starting Rails template.

##Current Defaults

- Ruby 2.1.5
- Rails 4.1.9
- Slim for templates
- Sass for stylesheets
- Coffeescript for javascript-y type things
- Puma for the server
- Postgres 9.3.5.1 for DB

##Dependencies

- Ruby
- Some JavaScript runtime

##Configuration

1. Clone this repo:

```
git clone https://github.com/andrewjkerr/rails_starter.git
```

2. Run `bundle install`.

3. Change the module name in `config/application.rb` to your application name.

4. Change the title in `application.html/slim` to whatever you want. (By default uses "[provided title] | [module name]" - ex "Home | RailsStarter".)

5. Change the db settings in `config/database.yml` if necessary.

6. Run `rails s`!