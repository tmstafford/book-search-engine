# Book Search Engine

## Description

The Books Search Engine is a fully functional Google Books API search engine built with a RESTful API. The website was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API. The code was refactored to use a GraphQL API built with Apollo Server. 
The code was refactored by setting up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API. The existing authentication middleware was modified so that it works in the context of a GraphQL API. An Apollo Provider was created so that requests can communicate with an Apollo Server.

The application is also deployed on Heroku. It can be found at https://arcane-lake-56277.herokuapp.com/.

Users can type a search term in the search box and view results. The user can save books by clicking "Save This Book!" under each search result. A user can view their saved books on a separate page. 


<img width="1437" alt="Screen Shot 2021-04-08 at 2 49 32 AM" src="https://user-images.githubusercontent.com/70179648/113988567-35d7c380-9815-11eb-9bd0-9ea587947288.png">

<img width="918" alt="Screen Shot 2021-04-08 at 2 51 12 AM" src="https://user-images.githubusercontent.com/70179648/113988673-5142ce80-9815-11eb-9d97-232b38a52dbb.png">

## Installation

Clone this repository, then run `npm install` to install all dependencies needed for this application. Run `npm start` in the terminal to view the build of the application in local enviornment.

## Usage
Users can type a search term in the search box and view results. The user can save books by clicking "Save This Book!" under each search result. A user can view their saved books on a separate page. 

<img width="613" alt="Screen Shot 2021-04-08 at 2 53 54 AM" src="https://user-images.githubusercontent.com/70179648/113989143-c2828180-9815-11eb-933c-e618f69f49c1.png">

<img width="1425" alt="Screen Shot 2021-04-08 at 2 54 22 AM" src="https://user-images.githubusercontent.com/70179648/113989172-cc0be980-9815-11eb-941a-9b12b8b8c8fb.png">

## Contributing
Made by Tatum Stafford. [GitHub](github.com/tmstafford).
