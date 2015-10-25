# Ember Simple Auth Devise Example

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
