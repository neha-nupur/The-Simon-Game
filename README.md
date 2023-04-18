# The-Simon-Game
<html>
<h2> Framework/Tools Used:</h2>
<ul>
  <li>HTML </li>
  <li>CSS </li>
  <li>JavaScript </li>
</ul>
<h2> HTML:</h2>
<ul>
  <li>Defines the basic structure of the web page </li>
  <li>Includes a title, a header, and a container with four buttons that will serve as the game board </li>
  <li>Also includes two external resources: a stylesheet and a JavaScript file</li>
  <li><strong>Button Animation:<strong> The JavaScript code adds a "pressed" class to the drum button when it is clicked or pressed, and removes it after a short delay to create a visual animation effect. </li>
</ul>

<h2> CSS:</h2>
<ul>
  <li>Defines the visual styles for the web page, such as font, color, and layout </li>
  <li>Includes styles for the game board buttons, such as background color and size </li>
</ul>

<h2> JavaScript:</h2>
<ul>
  <li>Defines the game logic and behavior, and handles user interactions with the game board </li>
  <li>Defines an array of button colors, an array to hold the game pattern, and an array to hold the user's clicked pattern </li>
  <li>Initializes variables to track whether the game has started, and the current level </li>
  <li>Listens for a key press to start the game </li>
  <li>Listens for clicks on the game board buttons, adds the clicked color to the user's clicked pattern, plays a sound, and animates the button press </li>
  <li>Defines a function to check the user's pattern against the game pattern, and to progress to the next level or end the game if the pattern is incorrect </li>
  <li>Defines a function to generate the next color in the game pattern, display it on the game board, play its associated sound, and increment the level </li>
  <li>Defines a function to animate the button press by adding and removing a CSS class </li>
  <li>Defines a function to play the appropriate sound file based on the color name </li>
  <li>Defines a function to reset the game variables and restart the game if the player loses </li>
  
</ul>
 <h3>Note: The above make up the complete Simon game.</h3>

</html>
