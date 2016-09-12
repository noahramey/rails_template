# Ruby on Rails Application Template

Ruby on Rails Application Template to quickly start making a Rails app.

### Installation

Open Terminal and clone the repository.  
```
$ cd Desktop
$ git clone https://github.com/noahramey/rails_template.git
```

Navigate to the repository and bundle Ruby gems:
```
$ cd rails_template
$ bundle install
$ git remote remove origin
```

Make sure Postgres is running on your local machine, then setup the database:
```
$ rails db:setup db:test:prepare
```

Start the Rails server.
```
$ rails s
```

Open your browser and navigate to `localhost:3000`. You are now ready to start making your app!


License
-------

MIT License. Copyright &copy; 2016 "Noah Ramey"
