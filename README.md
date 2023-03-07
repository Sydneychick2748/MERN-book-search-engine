# MERN-book-search-engine



## Description

This is an application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that enables users to search for books on Google Books by entering a title. The results of the search are displayed on the app. Users can log in and save books they are interested in to their account. The app uses a GraphQL API provided by Apollo Server to access its internal database. Security for the app is ensured through the use of JSON Web Tokens and the jwt-decode module on the client side.





## Table of Contents (Optional)



- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)
- [Contribute](#contribute)
- [Questions](#questions)

## Installation

The application was cloned from the github repo and then set up in vs code the technologies used are :
React.js
CSS
Bootstrap
JavaScript
Node.js
npm
Express.js
MongoDB
Mongoose
@apollo/client
apollo-server-express
graphQL
JWT
bcrypt
Google Books API
concurrently
nodemon

To start the application:
npm i 
npm run build 
npm run develop 

To see the application in action go to the live heroku link here: 

## Usage
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Sign up and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Sign up menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Sign up
THEN I am presented with three inputs for a username, an email address, and a password, and a sign up button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the sign up button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Sign up and an input field to search for books and a submit button  


   

## Credits

 React- A JavaScript library for building user interfaces

Apollo Client - A framework for binding data to your UI with GraphQL.



## License
This applications has no license.



## Contribute
If you want to contribute then you can go to the repo here:


## Questions
If you have any questions you can email me here: anabennett77@gmail.com 


