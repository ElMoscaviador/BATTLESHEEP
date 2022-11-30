# 🐑 B A T T L E S H E E P 🐑
#### A sheep-themed riff on the standard Battleship game 
https://elmoscaviador.github.io/Battlesheep/

---
## ALL ABOUT THE PROJECT 

### DESCRIPTION
This app allows you to play a sheep-themed game of Battleship.
Play against another human player or against an IA.
Place your ships using drag n'drop.
Click on an square from the opponent's gameboard to hit it. 
Sheep-based song lyrics will accompany you at every turn.

### WALKTHROUGH OF THE APP
#### Intro screen
- To play against the IA, just click 'PLAY'.
- To play against another player, click on the floating bubble then click 'PLAY'.
#### Positioning screen
- Use drag n' drop to place your ships on the gameboard.
- Press SHIFT on a keyboard or double tap on a touch screen to switch the ship's direction.
- Click 'SAVE YOUR SHEEPS' to validate your choices.
#### Battle screen
- Click on a square to hit the opponent's gameboard.
- When all ships are sunk, the game ends.

### RESPONSIVE DESIGN
- The app is built responsively to let you play on any screen resolution up to 350px. 
- The app's appearance is scalable live.
- When playing on a small screen, only the current gameboard will be displayed.

### FEATURES 
- You can play the game on mobile, tablet & PC.
- You can enable two players mode or play against the IA.
- Sheep-based song lyrics will accompany each turn.
- You can place your ships vertically or horizontally by double tapping on mobile or pressing shift on PC.
- The IA is smart: it will remember which ships were hit, which ones were sunk, which ones yet need to be sunk, and will logically determine where a ship's remaining parts are more likely to be situated based on the original hit's and successful hits' direction.

### FEATURES TO BE IMPLEMENTED 
- Accessibility is everything and that's why an accessibility mode will be added: no animations, no drag n' drop & regular checkboxes to select the player mode. Aria properties must be added to DOM elements.
- I will add much more lyrics to the future to minimize repetition.
- I will add a 'restart' button at the end of a game to spare the user from having to reload the page if they'd like to start a new game.
- I may add a dark mode if I figure out how to maintain the app's lively tone with it.

### JEST TESTING
- Only the app's logic was tested, not the DOM.
- The tests have been made using mocks in order to make them work without dependencies.
- A great majority of functions have been tested.
- The functions which were not tested have very simple logic or group tested functions together.

### ISSUES TO BE FIXED
- In some cases, when starting in small screen mode then scaling to a bigger screen, only one gameboard will remain displayed instead of two.
- The end results screen may not scale properly at some resolutions.
- Updating a ship's direction on a touch screen may result in a ship disappearing or being placed on an incorrect square.
- Using double tap to update a ship's direction can be buggy. A better trigger needs to be implemented.
- The animations can feel wonky on small screens.
- The widescreen version of the background is stretched.
- The player mode alert on the intro screen needs to be made more visible.

### ABOUT UNKNOWN ISSUES
Please do not hesitate to report any lingering issues to me - I am all ears & would be grateful to you.

---

## GENESIS OF THIS PROJECT

### WHY I TOOK ON THIS PROJECT
As a web developer in the making, I started The Odin Project's course in late 2021. 

The Battleship Project is the latest project I was asked to tackle as part of the course.

### WHAT MY LEARNING TARGETS WERE FOR THIS PROJECT
- Learning to <b>properly plan out the project</b> before writing any line of code.

- Understanding & using <b>Jest to test my app's core logic</b>.

- Improving my understanding of the <b>separation of concerns</b>.

- Programming <b>a fully-functional logic</b> before designing the app's appearance.

- Making DOM elements and logic <b>as independant as possible</b>. 

- <b>Learning to use Inkscape</b> to design my own art instead of relying on existing artwork.

### WHAT MY VISION FOR THIS PROJECT WAS
I'll admit to feeling rather uninspired by the concept of a Battleship game at first. 

Then, I got to thinking about ways to sprinkle some life into it, and it became clear:

BATTLESHIP. BATTLE / SHIP. BATTLE... SHEEP ?

It hit me: why not just make a version of Battleship based on sheep, perhaps even on my favourite show, Shaun The Sheep?

Drawing from this idea, it very quickly became clear how the app should look & feel.

Its general appearance should be cartoonish, a tad over the top and most of all colourful. 

It should look lively, include fun artwork and feel swift in its navigation.

### HOW I APPROACHED THIS PROJECT
1. <b>Learning Inkscape</b> using LOGOS BY NICK's wonderfully suscint yet helpful beginners course.
   
2. <b>Designing the app's logic</b> by drawing good old fashioned flow charts on newly learned Inkscape.

3. <b>Transcoding the flow charts</b> to Javascript.   

4. <b>Testing the core logic</b> using Jest to make sure it was fully functional.

5. <b>Designing the UI's rough outline</b> using Inkscape. 

6. <b>Designing all UI elements</b> using Inkscape.  

7. <b>Coding the DOM</b> components in Javacript.

8. <b>Creating a bridge</b> between DOM & logic elements.

9. <b>Shaping the app's appearance</b> based on the previously designed outline in CSS.

10. <b>Elimining most remaining bugs</b> and timing issues.    

### THE CHALLENGES I FACED DURING THIS PROJECT
- Designing and transcoding a fully functional smart IA to Javascript felt impossible at first, but it was facilitated greatly by the use of flow charts. It took days of designing, testing, and starting back from scratch to evaluate all scenarios the IA could possibly encounter during any given game.
  
- The system used for displaying the ships is completely different between the ship positioning screen and the actual game. Full images are used for positioning, whereas divided ones are used in the actual game. This was necessary to allow for hiding individual ship parts but necessitated additional time redesigning ships on Inkscape. 

### CLOSING THOUGHTS ON COMPLETING THE PROJECT
- For the first time since starting The Odin Project, I can say that the final result resembles my original idea closely.
- I learned so much thanks to this project, and had such incredible fun realizing it. 
- Finally getting around to learning Inkscape means I can be more creative in all future projects - it's something I've been wanting to do for years, and I'm very happy to create my own stuff.
- Likewise, learning Jest has taken me some time, but it will speed up my projects now that I've gotten comfortable with it to test my code.
- I have already refactored the code for the app's logic to make it more presentable, but I need to work further on the DOM's code as it contains code smells such as repetition.
- All in all, this project reinforced my passion for web development and I only want to improve further.

---
## CREDITS
- LOGOS BY NICK - https://logosbynick.com/ - thanks for teaching me Inkscape!
- THE ODIN PROJECT - https://www.theodinproject.com/ - for making me fall in love with web development, for free, while offering the best resources available online: thank you!
- AARDMAN ANIMATIONS - https://www.shaunthesheep.com/ - for creating Shaun The Sheep and giving me artwork ideas.
- All of the artwork was created by myself on Inkscape and inspired by Shaun the Sheep.

## AUTHOR

Hello, I'm ElMoscaviador.

Find me on Github:
https://github.com/ElMoscaviador/Battlesheep