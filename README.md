# Ember Simple Auth Devise Example

To know how to build the devise backend, check the commits here:  
https://github.com/jimbeaudoin/ember-simple-auth-example/commits/devise-integration

You can also take a look at this blog post:  
http://givan.se/ember-cli-simple-auth-devise/

### Version
  * Ember: 2.1.0
  * Ember Simple Auth: 1.0.1
  * Rails: 4.2.4
  * Devise: 3.5.2

### Backend Setup
```sh
cd backend/
bundle install
bundle exec rake db:create
bundle exec rake db:migrate
bundle exec rake db:seed
bundle exex rails s
```

### Frontend Setup
```sh
cd frontend/
npm install
bower install
ember s --proxy http://localhost:3000
```

### Login Credentials
Email: test@example.com
Password: 12345678
