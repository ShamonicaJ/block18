Test specifications for the Puppy Bowl mini-game:

The Puppy Bowl is a mini-game that allows users to add and remove cute puppies to a game roster. Some of this application has already been finished, but it is important to test "complete" functionality as well, to make sure everything is working for your clients.




                Main Page - Roster Display

Verify Roster Display:
Action: Open the main page.
Expectation: The main page should show a nicely formatted list of all players.
Expect each player on the roster to be shown with two buttons: “See details” and “Remove”.

View Player Details:
Action: Click the "See details" button for a player.
Expectation: The details page for the selected player should display the player's name, breed, and assigned team (or "unassigned" if they do not have a team). A larger version of the picture should be shown, and a button should be available to go back to the main list.

Remove Player:
Action: Click the "Remove" button for a player.
Expectation: The player should be removed from the roster without a page refresh.


                        Adding Player(s)
Add New Player:
Action: Access the form to add a new player.
Expectation: The form should have inputs for player name and breed, and a submit button. After entering name and breed and hitting "submit," the new player should appear in the roster without a page refresh.


                        Removing Player(s)
Remove Player from Roster:
Action: Choose an existing player on the roster.
Expectation: Click the "Remove" button to remove the player. The player should disappear from the roster without a page refresh.




                    Stretch Goals - 
View Teammates in Single Player View:
Action: Navigate to a player's details page.
Expectation: The single player view should display all teammates (players assigned to the same team) as the current player. The list of teammates should be empty if the current player has no assigned team.

Change Team Assignment in Dropdown:
Action: Navigate to a player's details page.
Expectation: A dropdown should allow users to change the team assignment for the current player. Select a different team from the dropdown and confirm that the team assignment changes in the single player view and in the roster immediately without a page refresh.


Adding Players with Image URL
Action: Access the form to add a new player.
Expectation: The form should include inputs for player name, breed, and an image URL. After providing the image URL, the linked image should show up as the player's portrait in the roster.


Add Player with Empty Image URL:
Action: Access the form to add a new player.
Expectation: Fill in the inputs for player name and breed but provide an empty image URL. After submitting, the new player should appear in the roster. If the image URL is empty, a default image or a placeholder should be displayed.



Add Player with Invalid Image URL:
Action: Access the form to add a new player.
Expectation: Provide an invalid image URL (e.g., a non-existent URL). After submitting, the new player should appear in the roster, and if the image URL is invalid, a placeholder or error message should be displayed.

