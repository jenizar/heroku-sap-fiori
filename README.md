# heroku-sap-ui5-mockd-internal
Deploy SAP Fiori Master-Detail Mockdata Internal to Heroku cloud

# Deploy to Heroku cloud

$ git clone `https://github.com/jenizar/heroku-sapui5-mockd-internal.git`

$ cd heroku-sapui5-mockd-internal (make sure you are in heroku-sapui5-mockd-internal directory)

$ heroku login

$ heroku create jenizar-sapui5-mockd

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-mockd

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-mockd is name your apps in the url, open your browser: https://jenizar-sapui5-mockd.herokuapp.com

- cause this apps using html static therefore utilize php buildpack. 
