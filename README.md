World Choropleth of Global Trade Balance

## Site is deployed on Heroku:
https://world-trade-balance.herokuapp.com

## Objective:
This project showcased developing a dynamic website application to visualise the world trade balances of every country on a world choropleth.

## Tools:
HTML5 Grid Layout method used with media queries for website responsiveness, CSS, JavaScript, D3.js, Leaflet.js, Flask, MongoDB, Python and Pandas

## Data Sources:
- International trade data: https://dataverse.harvard.edu/dataverse/atlas
- Country border geoJSON data: https://datahub.io/core/geo-countries#pandas

## Data Transformation:
- Perform aggregation of each product ID per country to find total export value per year
- Find out which country goes with each ISO code

## Data Loading:
- Data for this project is stored in a MongoDB Atlas database

## Flask Server:
- The API and the application for this project are built using the Flask framework to be locally hosted
- Using the API to visualise the data on a world choropleth powered using API endpoints

## Deployment:
Application is deployed to Heroku
