Whack-A-Mole
Whack-A-Mole is a classic arcade game where players must hit moles that pop up randomly from holes on the screen. This implementation is built using HTML, CSS, and JavaScript.

How to Play
Open the index.html file in your web browser.
Click the "Start Game" button to begin the game.
When a mole appears in one of the holes, click on it to score a point.
The game lasts for 60 seconds, and your goal is to score as many points as possible before the time runs out.
You can end the game prematurely by clicking the "End Game" button.
After the game ends, your final score will be displayed in an alert.
Files
index.html: The main HTML file that structures the game interface.
JS.JS: The JavaScript file that handles the game logic and interactivity.
style.css: The CSS file that styles the game elements and provides responsive design for smaller screens.
HTML Structure
The index.html file contains the following main elements:

A div for displaying the current score and remaining time.
Buttons for starting and ending the game.
A container div with nine holes where the moles will appear.
JavaScript Functionality
The JS.JS file contains the following main functions:

comeout(): Randomly selects a hole and adds the "mole" class to it, making a mole appear. It also adds a click event listener to the hole for scoring.
handleMoleClick(): Increments the score and removes the "mole" class from the clicked hole.
startGame(): Initializes the game state, starts the countdown timer, and begins the mole appearance interval.
endGame(): Ends the game by clearing the intervals and resetting the game state.
CSS Styles
The style.css file provides the following main styles:

Background colors and layout for the game interface.
Styling for the holes and mole appearance.
Responsive design for smaller screens, adjusting the size and layout of the game elements.
How to Customize
You can customize the game by modifying the HTML, CSS, and JavaScript files:

Change the number of holes by adding or removing div elements with the "hole" class in index.html.
Adjust the game duration by modifying the initial value of the timer variable in JS.JS.
Customize the appearance of the game elements by modifying the styles in style.css.
Add new features or modify the game logic by editing the JavaScript functions in JS.JS.
Have fun playing Whack-A-Mole