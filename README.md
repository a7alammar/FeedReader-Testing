# FeedReader Testing
 Udacity Fourth Project Fend Nanodegree

In this project, I am given a web-based application that reads RSS feeds. The application has incomplete Jasmine test suites, and I wrote the remaining test suites and get them to pass. 

## How to Run the Application

1. You can download or clone this repository.

2. Find the `index.html` file, and open the file in a modern browser.

3. The Jasmine tests are displayed at the bottom of the index.html page. 

4. Open the `jasmine/spec/feedreader.js` file to start editing the test suites.

If you are not familiar with Jasmine, visit the documentation [here](https://jasmine.github.io/ "Jasmine Documentation").

##  Tests That Were Implemented

* Tests for allfeeds has been defined and that it is not empty 
* Tests for allFeeds have a url and that the url is not empty
* Tests for allFeeds have a name and that the name is not empty 
* Searches for the class of 'menu-hidden' in the body tag and checks that the menu is hidden
* Toggles on click event if the menu appears or disappears
* Tests if the loadFeed function has at least a single '.entry' within the '.feed' container
* Tests to see if two entries are not equal
