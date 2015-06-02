# IMDB App

## Description
Use the unofficial IMDB API to create an app that keep track of the movies that you want to watch


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand how to use a router to update URL hash
* Understand how to use GET requests to query an API
* Understand how to use a constructor


### Performance Objectives

After completing this assignment, you be able to effectively use

* $.get
* Backbone.Router.extend
* Backbone.history.start()
* backbone router navigate



## Details

### Deliverables

* A repo containing at least:
  * `dist/main.js`
  * `dist/index.html`

### Requirements

* No JSHint warnings or errors
* No HTML validation errors


## Normal Mode
Using the [IMDB API](http://www.omdbapi.com/) create an application with two pages:

1. A home page (/) with a search bar, search button and description of the app. Upon searching for a movie it should update the URL and take you to the next page.

2. A search results page (/search/:query) that displays a list of movies based on the search you made. This page should make a GET request to the IMDB API and display those movies on the page.

	* When you click on any of the movies in your search results it should add that movie to an object, and add that object to an array that keeps track of all the movies you have clicked on.

	* The same movie should never appear twice in that array.

	* Upon adding a new movie to your array, console.log the entire contents of the array.

	* The search results page should also have a search bar and search button that allows you to do another search. Doing another search should also change the URL.

## Hard Mode
1. When you click on a movie on the search results page its opacity should be reduced by 50% to indicate that it is on your watch list. If you do another search and that movie appears in the results it should show up with an opacity of 50% in the results again.

2. Pick a color scheme from [Colour Lovers](http://www.colourlovers.com/browse) and update your design to use those colors.

3. Animate your search results so that when they appear on the page they fade in, slide in, etc.


## Notes

Notes go here...

## Additional Resources

* Read []()
