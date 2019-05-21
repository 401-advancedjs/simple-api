![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## HTTP, REST, and Swagger docs

### Author: Melissa Stock

### Links and Resources
* [submission PR](https://github.com/401-advancedjs/simple-api/pull/1)
* [swagger inspector](https://app.swaggerhub.com/apis/MeStock/HTTP-and-REST/0.1#/)

#### Documentation
* [swagger docs](https://swagger.io/docs/) (API servers)

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `json-server --id _id --watch ./data/db.json`
* Endpoint: `/categories/`
  * Returns a JSON object with id, name, display name, and description in it.
* Endpoint: `/products/`
  * Returns a JSON object with id, category, name, display name, description in it.
  
#### Tests
* No test

#### UML
![UML](/data/IMG_0555.jpeg)

