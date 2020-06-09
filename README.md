# React Project Ideas
A collection of project ideas for building websites with React

## General approach

1. For each idea create a new repository on GitHub and [create a new React App](https://github.com/facebook/create-react-app).
2. Setup CI to build the React App using GitHub actions - this will check that the build hasn't been broken when pushing to GitHub.
3. Implement the 'main idea' on the master branch and then request a code review.
4. Each project also has several 'side ideas' which enhance the app with extra functionality. __These should be developed on a separate branch in Git, and you should create a pull request so that they can be reviewed before merging the change.__

# Ideas

## Movie List

### Main idea

Use the [omdb API](http://www.omdbapi.com/) to display a vertical display of film names. There should be one input field on screen which allows the user to control what films appear, and a button which triggers a search.

### Side ideas

1. All the useful information returned about the films should be rendered (e.g. the year of release, the plot, actors, etc)
2. When the user initially loads the website, there should be some short placeholder text that describes how to search.
3. When the user performs a search, the input field/button should be disabled, and a progress spinner should be displayed
4. An error screen should be shown to the user if the films fail to load, or if no films exist for this search term
5. Films should be sorted in alphabetical order by their title by default. A button should be available to toggle the sort to release date instead (and vice versa)
6. Write a unit test for sorting films alphabetically/by release date

