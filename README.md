# Project-4COP3813

#**Lab 7.15:**
To get this lab done, these are the steps I did: 
- I did a loop inside a loop to complete the drawTriangle() function. This step was necessary because the function should draw a triangle with asterisks (*) based on the triangleSize parameter.
- Tested the drawTriangle() function with different arguments. One of them being "drawTriangle(4);

#**Lab 7.17:**
Things I did to complete this lab: 
- Completed the sortEvens() function. 
- The function should create a new array containing only the even integers in numArray. 
- Used the array method push() to add even numbers to a new array.

**#Lab 7.18:**
To complete this lab, these are the steps I did: 
- Added two properties: lives - initially 3, and coins - initially 0.
- Added a getter called points that returns coins * 10.
- Added a playerDies() method that subtracts 1 from lives if lives is greater than 0.
- Added a newGame() method that sets lives to 3 and coins to 0.

**#Lab 7.19:**
Things I did to complete this lab: 
-Wrote the function calcWordFrequencies() so that it has a single words parameter.
- called the function calcWordFrequencies() with a string argument containing a list of words separated by spaces.

**#Lab 7.20:**
Things I did to complete this lab: 
- I defined the printSum function with x and y as parameters.
- I used parseFloat() to attempt to convert x and y into numbers.
- I checked if both x and y are numbers using isNaN().
- If both x and y are numbers, I calculated their sum and printed: Sum is followed by the sum.
- I ensured to handle all possible cases of input being non-numeric.
- I tested the function with different inputs by calling printSum() with various values to ensure correctness.

**#Lab 7.21:**
Things I did to complete this lab: 
- I defined the trianglePerimeter function with six integer parameters representing the coordinates of the triangle's vertices: (x1, y1, x2, y2, x3, y3).
- I calculated the distance between each pair of vertices using the distance formula.
- I used the distance formula: d = Math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2) for each pair of vertices.
- I returned the sum of the three side lengths.
  
**#Lab 7.22:**
Things I did to complete this lab: 
- I defined the isStrongPassword function with a single parameter: password.
- I checked if the password is at least 8 characters long.
- I checked if the password does not contain the string "password" (case-insensitive).
- I used a regular expression to check if the password contains at least one uppercase character.
- I used a regular expression to check if the password contains at least one number.
- I used a regular expression to check if the password contains at least one special character.
- I used a regular expression to check if the password contains repeated character or number sequences of a length four or less.

**#Lab 8.14:**
Things I did to complete this lab: 
- I defined parseScores(scoresString) to convert a space-separated string into an array of score strings using split(' ').
- I defined buildDistributionArray(scoresArray) to create a grade distribution array based on standard grading ranges.
- I defined setTableContent(scoresString) to generate the bar graph in the table’s first row using parseScores() and buildDistributionArray().

**#Lab 8.15:**
Things I did to complete this lab: 
- I defined convertCtoF(celsius) to convert Celsius to Fahrenheit using the formula: °F = °C * 9/5 + 32.
- I wrote the domLoaded() function to set up the Convert button’s click event handler.
- I added input event handlers to clear the opposing text field when one is updated.
- I wrote updateWeatherImage() to update the weather image based on the Fahrenheit temperature.
- I wrote handleError(message) to set the error message for invalid input.
- I updated domLoaded() to call handleError() to clear the error message if input is valid.

**#Lab 8.16:**
Things I did to complete this lab: 
- I reviewed index.html to see it includes a 3x3 game board (gameBoard), a turnInfo paragraph, and a newGameButton for starting a new game.
- I wrote newGame() to reset the game state, clear the timeout, and reset the game board and turn information.
- I wrote boardButtonClicked(button) to handle player moves and call switchTurn() for the computer's turn.
- I wrote switchTurn() to check the game status and switch turns between player and computer.
- I wrote makeComputerMove() to let the computer choose a random move and call switchTurn().

**#Lab 8.17:**
Things I did to complete this lab: 
- I modified fetchQuotes() to request quotes from the API using XMLHttpRequest.
- I implemented responseReceivedHandler() to process the API response and display the quotes in the <div id="quotes">.
  
**#Lab 8.18:**
Things I did to complete this lab: 
- I modified startAnimation() to stop the existing timer if timerId is not null.
- I modified moveImage() to check if the heart has reached the target position. If it has, I stopped the timer and set timerId to null.

**#Lab 8.19:** 
Things I did to complete this lab: 
- In domLoaded(), added code to register addBtnClick() as the click event handler for the Add button.
- In addBtnClick(), extracted the text from the textbox and called addTask() with the new task.
- In addTask(), created a new <li> element with the task content and a ✖ button.
- Added a keyup event handler for the textbox to call addBtnClick() if the Enter key is pressed.
- Updated addBtnClick() to clear the textbox and set focus back to it.
- Added a check in addBtnClick() to prevent adding an empty task.
- Implemented removeTask() to remove the task from the list.
  
