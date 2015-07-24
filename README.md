# Spicy Watermelon

A django site.

## Setup

* git clone git@github.com:zachcalvert/spicy_watermelon.git
* cd spicy_watermelon
* mkvirtualenv spicy
* pip install -r requirements.txt
* echo "create database spicydb CHARACTER SET utf8 COLLATE utf8_bin;" | mysql -u root -p  (empty password)
* cd spicy_watermelon
* ./manage.py migrate
* ./manage.py runserver