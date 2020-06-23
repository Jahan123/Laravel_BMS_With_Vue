# Laravel And Vue js Book Management system Application 



In this application We Are dealing with laravel API with Authentication Passport token Guard,It contains Three Technologies
  - Vuejs
  - Laravel
  - Vuetify(For Some Styling)
  - axios(API)
---
### Installation
Lets Talk About Installation Of This Project And Run in Your Machine

```bash
$ cd Laravel_BMS_With_Vue-master
$ npm install 
$ composer install
```
After That Manage .env file and add database settings such as database name, password and username
As we are also using Email Queuing System so We Will Also Configure that

```bash
    first rename .env-example file to .env
    add database credentials, after that add for Email Queuing
    QUEUE_CONNECTION=database
```
### Take All Mail Credentails From here after signin into the mailtrap click below and you redirect to that website
[![MailTrap Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://mailtrap.io/)

### After that generate Key for application
```sh
php artisan key:generate
```
###  migrate
```sh
 php artisan migrate
```
## As we are Using Passport Install it Client
```sh
 php artisan passport:install
```
### Now, Our Application Ready To Run. All We need To Do Just Run Command Below Given
```sh
php artisan serve
127.0.0.1:8000
```
### For Vue js Run Command
```sh
  npm run watch
```
### As We Are Using Mail Queue
```sh
    php artisan queue:listen
```
Now Website is Running 


