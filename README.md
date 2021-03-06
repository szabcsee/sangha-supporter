# Dharmacloud

Dharmacloud is management application to manage various activities in the Diamond Way Buddhist centers. It is an experimental project built for fun and learning with the intention that after all it will be useful to manage administration and activities transparently in the buddhist centers. 

## Master branch

#### System dependencies for master branch
 - **Ruby version:** ruby 2.0.0p247
 - **Rails version:** Rails4
 - **Gems**
 	-- Devise gem for user management

#### Front-end technologies
 - Highcharts javascript framework for charts
 - Typeahead for autocomplete implementation

#### How to run the test suite

#### Services (job queues, cache servers, search engines, etc.)

## Deployment instructions

Master branch demo: http://vast-tor-7154.herokuapp.com/

* The application uses Ruby 2.4 and Rails 5.0.1

* The application UI used formerly ExtJs 6.0 with Sencha Cmd 6.1.2.15 which is being replaced with React and Redux

## React branch

### Configuration
Make sure that /config/oauth.yml exist as it is necessary for the SSO login.
The correct formatting of oauth.yml can be found in /config/initializers/load_oauth_config.rb

### Deployment instructions
Use the deployment script deployme.sh located in the main folder. After finishing deployment you will be located in the api_dharmacloud folder where you can lunch the server by *rails s*

## Release notes

#### Version 0.1.0
* Basic user management (with DWB SSO)
* Payment CRUD operations
* TV Content
* Main navigation 

#### Version 0.0.1R

The UI development has changed to React instead of ExtJs so we moved back from 0.1.0 to 0.0.1R as everything has to be reimplemented on the client side. The server side is in working condition and will not be touched. 