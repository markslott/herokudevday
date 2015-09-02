##Heroku-Salesforce Query Builder using Node.Js, AngularJs, Salesforce REST API, OAuth2 and Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy) 

Live Demo - https://demo-pgquery.herokuapp.com/
 


It uses Google's Angularjs MVC Javascript library and REST API provided by Salesforce. For Authentication, it uses OAuth. Node.js is used as a primary language and hosted on Heroku.

This Node.js application is used for building HSQB with following features :

- Toggle between API name and Label Name
- Search Objects or Fileds needs to build HSQB (In my case, it was primitive. I had more than 70 Objects and many of those objects has 300+ fields)
- Checkboxes to select fields (No need to hold control button to select multiple fields)
- Automatic Query Builder at Right side of the page
- Shows API count used by application
- Search returned records
- Sorting on Table Headers
- Pagination

