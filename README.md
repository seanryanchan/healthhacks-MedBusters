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

### Rails Full Stack Setup
```
git pull origin master
# CHANGE WORKING DIRECTORY TO RAILS APP
cd healthhacks-MedBusters/medbusters 
bundle install
sudo service postgresql start
sudo -su postgres psql #to start psql cli
create role medbusters with login createdb password 'medbusters';
\q    # to quit PSQL CLI
bundle exec rails db:create db:migrate db:seed
bundle exec rails s
```
