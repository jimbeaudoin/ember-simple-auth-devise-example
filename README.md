# Ember Simple Auth Devise Example

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
