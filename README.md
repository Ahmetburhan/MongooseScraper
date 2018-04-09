# **MongoDB/Mongoose NYT web-scraper**

### To view the deployed version, _**[click here!]
https://mongo-scraper-cheerio.herokuapp.com/

![Demo](/out.gif?raw=true "Demo of Mongo Scraper")
## Functionality
On the backend, the app uses `express` to serve routes and `mongoose` to interact with a `MongoDB` database.

On the frontend, the app uses `handlebars` for templating each article and `materialize` as a styling framework. The app also uses `jQuery` and `AJAX` to help with making post requests.

And for webscraping, the app uses the `request` and `cheerio` node packages. All webscrapping code can be found in the `scrape.js` file.
## Technologies used:
* Node.js
* Express.js
* MongoDB
* Mongoose
* Handlebars.js
* Javascript/ES6
* jQuery
* AJAX/JSON
* NPM modules:
  * Cheerio
  * Request-Promise
* Bootstrap 3
* CSS3 (including css animations and transitions)
* HTML5
* Canvas BG

## This is an app that uses Cheerio to scrape the New York Times US section and pull the most recent top articles:
