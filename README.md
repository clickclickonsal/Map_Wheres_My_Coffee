# Map! Where's My Coffee?

## OverView
User inputs their City in the the search form and based on the city, the app
returns 10 nearby Coffee Shops Name and Address. Also clicking on the name of the Coffee shop
on the site will redirect User to the yelp website displaying more information about the place as well as reviews.

## Local Set Up
* $ git clone git@github.com:ClickClickkOnSal/Map_Wheres_My_Coffee.git
* $ bundle install
* $ rake:db:create
* $ figaro install
* Sign up for Yelp's API keys at http://www.yelp.com/developers/manage_api_keys
* Add your API keys in the file created by figaro @ config/application.yml
  * yelp_consumer_key: '<'Consumer Key'>'
  * yelp_consumer_secret: '<'Consumer Secret'>'
  * yelp_token: '<'Token'>'
  * yelp_token_secret: '<'Token Secret'>'
* Insert your keys as strings after the colon(:)
* rails s
* Go to the url "localhost:3000" in your browser without the quotes

## Technologies Used
* Ruby 2.1.2
* Ruby on Rails 4.1.5
* jQuery
* SASS
* Yelp API
