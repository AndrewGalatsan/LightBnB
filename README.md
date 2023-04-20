# LightBnB
## This is a Lighthouse Labs assignment to practice SQL.

## Entity Relation Diagram (ERD) 
![Image of ERD](https://github.com/AndrewGalatsan/LightBnB/blob/master/docs/ERD_LightBnB.png?raw=true)

## Setup

Install dependencies with `npm install`.

### Dependencies
    "bcryptjs": "^2.4.3",
    "body-parser": "^1.19.0",
    "cookie-session": "^1.4.0",
    "express": "^4.17.1",
    "nodemon": "^1.19.4",
    "pg": "^8.7.1"
    
## Running Webpack Development Server
```sh
npm run local
```

## Running SASS Updates
```sh
npm run sass
```

## Running PSQL
login to psql and use the following command:
```sh
psql -h localhost -p 5432 -U vagrant lightbnb
```
password: 123