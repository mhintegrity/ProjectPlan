# Writing a Project Plan for My WebApp

## How to Write a Project Plan

### Phases of writing a plan

1. Concept
   1. Brain storm ideas, and consolidate them into a short description.
   2. Make the case for your idea by defining the idea behind the project, who and how does it provide benefit.  
2. Definition
   1. Put the plan down in writing, concentrating on outlining the projects scope and outline the work that needs to be performed.  
   2. Break down the work into tasks.  
   3. List resource dependencies and dependencies between tasks.  
   4. Based on resources (time and people) break it down into phases.
3. Determine what point is the minimum viable product (MVP).
   1. What are the tasks needed to meet MVP
4. Plan milestones
   1. MVP is 1.0
   2. Define features after 1.0 and increment them using semantic versioning.
  
### Semantic Versioning is a 3-component number in the format of X.Y.Z, where

X stands for a major version. May breaks compatibility.  
Y stands for a minor version. Minor change that doesn't break compatibility.  
Z stands for a patch. Bug fixes.  

Some times a 4th number is added for an incremental build number.

## My Sample Project Plan "Retro Arcade"

### Concept

* In the 70's and 80's the Arcade was a place where you would go to play video games.  
* High scores, bragging rights was part of the appeal.  
* The Arcade was about competitive socializing as well as playing video games.  
* The modern web application makes our app accessible to everyone, on phone, tablet or PC.  

### Definition

* The first screen (Home Screen) is a user high score tribute as well as way to display video clips of the game choices.  
  * The layout is to show each game in its own card.  
  * Each card contains the name, limited high score list and short animation of the game being played.  
  * On a phone layout show only one card with a simple way to flip from card to card.  
  * On a larger layout show multiple cards, that scroll horizontally.  
  * First screen also contains a simple hamburger menu button in the top left that when clicked reveals.  
    * User Login
    * Create New Account
    * Sponsor Us
  * When you click on a card zoom into the game if the user is logged in else goto the login screen.  
* Login screen  
  * Choose Login Method (github, facebook, twitter, google)  
  * login password  
  * Legal Disclaimer  
  * Top left corner is a home button  
* Game Screen (with login)
  * Shows a static game play image or logo, which when clicked starts a new game.  
  * Text describing the game and instructions how to play it.  
  * High Score List, showing the top 20 users
  * Top Left is a home button
* Game Play Screen
  * Game dominates the page
  * Top left corner is a simple back button that returns to the Game Instance Screen.  
* First Game **Space Invaders Clone** Named "Space Marines"
  * [Example Online Game](https://codepen.io/adelciotto/pen/BHuGL)  with an MIT License
  * Rules:  
    * **Break Down Details Here**.

### MVP

1. Home Screen (Without login)
2. Game Screen for "Space Marines"
3. Game Play Screen for "Space Marines", moving, shooting

* No High Scores

### Milestones

| Version | Milestone | Target Date |
|:-------:|:----------|:------------|
| 0.1.0 | MVP Home Screen | 1/2 week |
| 0.2.0 | MVP Game Screen | 1/2 week |
| 0.3.0 | MVP Functionally Complete | 3 weeks |
| 0.3.X | MVP Beta Testing with Class | 1 week |
| 1.0.X | MVP Delivery (Class Final) | 1 week |
| 2.0.X | Add Login | |
| 2.1.X | Add High Scores | |
| 2.2.X | Add Centipede Game | |
| 2.3.X | Add +1 to Thumbs up for other peoples high scores with user login | |
