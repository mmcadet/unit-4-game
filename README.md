# unit-4-game
jQuery Assignment

CrystalsCollector Game


2. The player will have to guess the answer, just like in Word Guess. This time, though, the player will guess with numbers instead of letters. 

3. Here's how the app works:

   * There will be four crystals displayed as buttons on the page.

   * The player will be shown a random number at the start of the game.

   * When the player clicks on a crystal, it will add a specific amount of points to the player's total score. 

     * Your game will hide this amount until the player clicks a crystal.
     * When they do click one, update the player's score counter.

   * The player wins if their total score matches the random number from the beginning of the game.

   * The player loses if their score goes above the random number.

   * The game restarts whenever the player wins or loses.

     * When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values. Of course, the user's score (and score counter) will reset to zero.

   * The app should show the number of games the player wins and loses. To that end, do not refresh the page as a means to restart the game.

##### Option 1 Game design notes

* The random number shown at the start of the game should be between 19 - 120.

* Each crystal should have a random hidden value between 1 - 12.


<!-- Crystals Collector Game
This is a guessing game using numbers where the player will guess with numbers.
There will be four crystals displayed as buttons on the page.
The player will be shown a random number at the start of the game.
When the player clicks on a crystal it will add a specific amount of points to the player's total score.
The player wins the game if their total score matches the random number and the player loses the game if their total score goes above the random number.
The amount of points each crystal adds is not shown to the player, but their total score is displayed and updated after each crystal is clicked.
The number of games won and lost will be displayed.
If the player successfully matches their total score to the random number they get 1 win, if the player's total score is above the random number the player get 1 loss, either way the game restarts.
When the game is restarted, the player will be shown a new random number, all the crystals will now have 4 different hidden values, and the player's total score is reset to 0.
Game design note:
The random number shown at the start of the game should be between 19 - 120
Each crystal should have a random hidden value between 1 - 12
Heroku: https://intense-anchorage-88733.herokuapp.com/ -->