# New York Times React Search
React Search uses an API to get articles from the New York Times and components to show the articles. Articles can be saved into another component and the Mongo database.

Following the process all the way through:

* Front end: The user clicks a button (pages/Articles.js) which calls an API CRUD action (utils/API.js) and moves server-side.
* Back end: This (the utils/API.js from above) uses Axios to make API CRUD calls within the app (routes/api/articles.js). This routes the CRUD call to the specific method in the controllers/articlesController.js. This manipulates the article model for the database.

It's a full stack application using node and express for the server, deployment on Heroku, Mongo for the database, and React.js for the front-end.

## Instructions

1. Enter in the topic, start year, and end year and click "search".
2. Click the article to open in a new window and read it or click "Save Article" to move it to the Saved section.
3. Saved articles can be removed from the app and database.

## Built With

* JavaScript - Makes it interactive
* React - JavaScript library for building user interfaces
* Bootstrap - Makes it pretty
* Node - Executes JavaScript server-side
* Express - Web framework for Node.js
* MongoDB - Database
* Mongoose - Makes working with Mongo easier
* Heroku - Deployment
* NPM Packages - Small packages of reuseable code that pack a big punch (express, body-parser, express-handlebars, mongoose, cheerio, axios)

## Authors

* **William Cotton** - *[wcotton229](https://github.com/wcotton229)*

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/osd) file for details
