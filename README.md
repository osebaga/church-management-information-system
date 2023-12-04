# About Church Management information System
    Its a web application for churches that manages administrative activities in the church.
    it manages the church's attendances, collections, members, events, announcements.
    features also includes bulk sms, email messaging, analysis on attendance, collection, members etc

# Installation

## Clone project
```bash
git clone git@github.com:osebaga/church-management-information-system.git
```
## Install Composer Dependencies
```bash
composer install
```
## Create Environment File
```bash
cp .env.example .env
```
## Configure Environment File
/ .env
```
APP_NAME=CMS
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://127.0.0.1:8000

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=church
DB_USERNAME=root
DB_PASSWORD=

MAIL_MAILER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS=null
MAIL_FROM_NAME="${APP_NAME}"
```
## Generate App Key
```bash
php artisan key:generate
```
## Create Database
...
## Migrate Database Tables
```bash
php artisan migrate
```

## Running Server
```bash
php artisan serve
```

## Previews

![Dashboard view](https://github.com/osebaga/church-management-information-system/blob/master/public/img/cms.JPG)
![Dashboard view2](https://github.com/osebaga/church-management-information-system/blob/master/public/img/cms2.JPG)
![Dashboard view3](https://github.com/osebaga/church-management-information-system/blob/master/public/img/cms3.JPG)
![Dashboard view4](https://github.com/osebaga/church-management-information-system/blob/master/public/img/cms4.JPG)
