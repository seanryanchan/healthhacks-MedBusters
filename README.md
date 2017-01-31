# MedBusters
## MediCode x HealthHacks
MedBusters Health Edu-gaming app!

HealthHacks 2017

MediCode: Sean, Makki, Cid, Carlo

### Install Rails 5 and Ionic
```
rbenv install 2.3.0
gem install bundler
gem install rails
```

### RailsAPI Setup
```
git pull origin master
cd csidevise/railsapi
bundle install
sudo service postgresql start
sudo -su postgres psql #to start psql cli
CREATE ROLE csidevise WITH LOGIN CREATEDB PASSWORD 'csidevise';
\q #to quit psql
bundle exec rails db:create db:migrate db:seed
bundle exec rails s
```
