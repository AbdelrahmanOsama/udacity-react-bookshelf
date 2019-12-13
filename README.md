# MyReads Project

This project is the final milestone of the the first part (React Fundamentals) of Udacity's React Nanodegree program. Essentially it's an application which allows you to manage your books in three shelfs ("Currently Reading", "Want to Read" and "Read"). The user is capable to move the book from one shelf to another (via context menu) or remove it from any of the three shelfs at all (context menu option "None"). There is also a possibility to search for other books via a search mask and add then to one of the three personal shelfs. 

## Start of the application

To get started simply run the following commands:

* install all project dependencies with `npm install`
* start the development server with `npm start`

## Code base
```bash
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with the app.
├── package.json # npm package manager file. 
├── public
│   ├── favicon.ico # React Icon
│   └── index.html #Central html file which is the anchor for the React app
└── src
    ├── App.css # App Styles
    ├── App.js # This is the root of the app. 
    ├── App.test.js # Used for testing. Provided with Create React App.
    ├── Authors.js # Component for rendering author information. Multiple authors are shown vertically
    ├── Book.js # Component for handling a single book instance
    ├── BookCategoryChanger.js # Component for handling the category (shelf) information of a book
    ├── BookShelf.js # Container for multiple books of one certain category  
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. 
    ├── icons # Images for the app. 
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── Search.js # Component for handling and rendering search results
    ├── index.css # Global styles. 
    |── index.js # used for DOM rendering 
```
