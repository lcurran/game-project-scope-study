# Game Project scope

## Wireframe

./assets/project1-wireframe-v1.png

## Data structure

grid {
  rowA: [],
  rowB: [],
  rowC: [],
  col1: [],
  col2: [],
  col3: [],
  diagonalX: [],
  diagonalY: []
}

Increment for X, decrement for O. When abs(sum) = grid dimension, if positive
player X wins, if negative player O wins.

Row arrays can be translated to X's + O's fairly easily and concatenated to save
in API.  Still debating how to make victory conditions translate back and forth
between API and app, if unable to save my grid object.

## User Stories

As a user, I want to be able to immediately play a game upon loading the page.

As a user, I want to be able to create an account easily.

As a user, I want to be able to save and access past games.

As a user, I want to be able to change my password.

As a user, I want to be able to play the app on mobile.

## Code modules

Files:

-   HTML
-   CSS
-   Gameboard arrays
-   Actions
-   API calls
-   UI elements
-   Win conditions

May end up discovering further compartmentalization is needed, but to begin to
build this should do.

## Creativity

I'd like to add a mode where you can play with any size game board, because it
should be fairly straightforward with the logic I'm planning to use.  Won't be
able to save super mode games in the API though because bigger board size isnt
supported.

## Version Control

Git repo already created, going to use a branch for each aspect of the project,
one for HTML, one for CSS, one for JS and possibly even split the API js into
another branch as well.  That way I can compartmentalize what I am working on
and focus on one thing at a time.

## Bonuses

I would love to be able to make multiplayer work
