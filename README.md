<h1 align="center"> Quiz Games</h1>

<p align="center">
<img src="image.png" alt="drawing" width="200"/>


Quiz games are interactive games designed to test and enhance a player's knowledge on various topics through a series of questions. These games can be played individually or in groups, and they often feature multiple-choice questions.
</p>

## User Stories :

1. The user should be able to see a landing page when I arrive at the website to know I'm in the right place.

2. he user must be able to see the "start game" button .

3. The user should be able to see one question at a time with multiple answer options.

4. The user must be able to select an answer for each question.

4. the user should be able to see feedback after selecting.

5.  the user should be able to proceed to the next question.

6.  the user should be able to view the  total score.

7. the user should be able to view time of the  questions .


8. the user should be able to play another round to try to improve  record.

10. the user should be able to see clear message indicating the score of the game.

## Pseudocode :
1. **Define constants and variables.**
```
// Define a constant for DOM elements.
// Define a constant for the total number of questions.
// Define a constant array for the quiz questions and answers.
// Define a variable for the user's score.
// Define a variable for the current question and answers.
// Define a variable for the game message.

```


2. **Add event listeners - use delegated event listeners to listen to multiple elements with a single listener..**
```
// Add an event listener to the start Game button.
// Add an event listener to the select Answer.
// Add an event listener to the next question button.
// Add an event listener to the restart quiz button.
// // Add an event listener to the DarkMode button.
```


3. **Invoke the init function used to initialize all state variables.**

```
1. Wait for the user to click on an Sart game option.
// Display the Questions container

2. when desplay Questions container.
 // display the Question and options.
 // display the timer.
 // display the score.
 // display the number of question.
 // display the messeges.
 


3. Wait for the user to click on an answer option.
// Assign the user's selected answer to a variable
// Compare the user's selected answer to the correct answer
// IF the user's answer is correct
    // THEN increment the user's score
    // Update the game message to "Correct!"
// ELSE
    // Update the game message to "Incorrect!"
    // End the Game and return back to first page with score .
// IF timer is finish
  //THEN Game over .
//ELSE
  // the timer  continues to decline until it ends.
// Render the game message to the DOM


4. Wait for the user to click on the next question button.
// Increment the current question index
// IF there are more questions
    // THEN display the next question and answer options
// ELSE
    // Display the final score
    // Display the restart quiz button
```

4. **Wait for the user to click the "Play Again" button.**

```
// Reset current question index to 0
// Reset user score to 0
// Reset  the timer .
// Clear the game message
// Display the first question and answer options again

```