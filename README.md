# Test-Cases

Below are some Test-Cases that I made

-----------------

#### Title: Test login with correct credentials

  #### Description: Check if the login works when a person uses a correct user/pass to enter the game

 ####  Steps to reproduce:

1. Go to www.Questmaster.com/login
2. Add a correct user/pass
3. Press Login button

 #### Expected result : User will be able to login
 
 #### Test data: User: Max & Pass:123456

-----------------

Title: Search for an item in the inventory
NEW
Description: Search for an item and after that use the delete function in the search bar to delete the item from
the inventory.
Steps to reproduce:
1. Go to http://www.Questmaster.com/login
2. Use credentials to login
3. Press “I” button to open inventory menu
4. Click on the search bar
5. Search for the item
6. Click on item
7. Click on “Delete”
8. Click on “Yes” when the delete interrogation appears
Expected result: User will be able to find the searched item in the game and delete the item from the inventory
for him.
Test data: For search: Goat Cheese
User: Max & Pass:56789

-----------------

Title : As a user I want to craft a potion that increases my stamina permanently
Preconditions :
User has to be logged in
The user has to have the next potion requirements : 2 x Grumpy Beets , 1 x Glass Bottle and 3 x Enchanted
Blue Leaves
The user has to be near a cauldron
Given the user already possesses the necessary ingredients
When the user uses the cauldron and adds the ingredients to their specific socket
Then the potion will be created and automatically added to the user’s inventory
Expected results :
G : the user succesfully grabs the necessary ingredients
W: The user succesfully opens the brewing menu of the cauldron and selects each ingredient to their respective
socket
T: The potion will be succesfully created and automatically added to the user’s inventory for later consumption
The potion does not fail in the brewing process

-----------------

Title : As a user I want to change my password because I forgot it 
Preconditions :
User has to have access to the website 
User has to have the website opened in the browser
The user has the email address to fill the required empty bracket
The user has a desired password nearby  to replace the one that he forgot 
Given the user already possesses the email address and a new suitable password
When the user enters the email address and the new password in their respective brackets
Then the “Save Password” button will redirect the user to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes.
Expected results :
G : the user successfully select the email address and the new password 
W: The user successfully enters the email address and the new password in their respective brackets
T: The “Save Password” button will successfully redirect the user to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes
The “Save Password”  does not remain static after being clicked 

-----------------

Title: Test “Save Password” button after entering the credentials 
Description: Check if the “Save Password” button works when a person uses a correct email address and a new password to enter his/hers account after forgetting their initial password
Steps to reproduce:
1. Go to http://www.Foodchooser.com//login
2. Select “Sign in” near the “Already a user” text
3. Select “Have you forgotten your password” option
4. Click on the search bar
5. Enter your email 
6. Open your email provider (Yahoo, Google etc)
7. Search for the email automatically sent by the platform 
8. Click on the link inside the received email
9. Enter the new password that replaces the old one
10. Press “Save Password” button
Expected result: User will be redirected to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes
Test data: To test the functionality of the “Save Password” button
User: Max & Pass:56789

-----------------

Title: Body functionality for a NPC
Description: Checking if a random NPC has his/her’s whole body visible 
 Steps to reproduce:
Enter the game
Log in with credentials
Select “New Game”
Wait for the new game cutscene to finish
Select any race available 
Press “Play”
Navigate the surroundings 
Observe the body of the found NPC
Expected result: The user should see clearly the body of the found NPC
Test data: To test the body functionality of a random NPC
User: Moxxy & Pass: 9221233

-----------------

Title : As a user I want to craft a potion that increases my stamina permanently

Preconditions :

The user has to be logged in
The user has to have the next potion requirements : 2 x Grumpy Beets , 1 x Glass Bottle and 3 x Enchanted Blue Leaves
The user has to be near a cauldron

Given the user already possesses the necessary ingredients
When the user uses the cauldron and adds the ingredients to their specific socket
Then the potion will be created and automatically added to the user’s inventory

Expected results :
G : the user succesfully grabs the necessary ingredients
W: The user succesfully opens the brewing menu of the cauldron and selects each ingredient to their respective
socket
T: The potion will be succesfully created and automatically added to the user’s inventory for later consumption
The potion does not fail in the brewing process

-----------------

Title: Bed functionality
Description: Check if the user can sleep in the bed
Steps to reproduce:
Run the game
Wait for the generic loading screen to load
Select “New Game”
Select “Human” race
Select “Begin”
Wait for the new game loading screen to load
Press “M” to open the minimap
Select “HappyGate”
Select “Fast Travel” 
Wait for the fast travel loading screen to load
Find a Bar
Find a bed
Press “E” to go to sleep
Observe the effects

Expected result: User should be able to use the bed
Test data: To test the functionality of a bed to be used
User: Gambit_lord & Pass: Oloibaby

-----------------

Title: Gas canister resistance functionality
Description: Check if  a gas canister can resist by being penetrated by a bullet
Steps to reproduce:
Run the game 
Log in with credentials 
Select “Begin”
Wait for the generic load screen to load
Select “Load game”
Select “A Brick Away”
Press “Load” 
Wait for the load screen to load
Press “M” to open the minimap
Switch to local map by single clicking the local map option at the bottom-right corner
Find the elevators on the map
Press “M” to close the minimap
Navigate the building until you find the elevators
Look for a gas canister
Aim at the gas canister
Shot the gas canister
Observe the effect of the bullet on the canister
Expected result: User should  put a bullet hole on the gas canister 
Test data: To test the gas canister resistance functionality 
User: Oloi_Prince & Pass:9231722

-----------------

Title : In-game mailbox functionality
Preconditions :
User has to have an account to an email provider 
The user has the email address to fill the required empty bracket
The user has a desired password nearby  to replace the one that he forgot 
Given the user already possesses the email address and a new suitable password
When the user enters the email address and the new password in their respective brackets
Then the “Save Password” button will redirect the user to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes.
Expected results :
G : the user successfully select the email address and the new password 
W: The user successfully enters the email address and the new password in their respective brackets
T: The “Save Password” button will successfully redirect the user to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes
The “Save Password”  does not remain static after being clicked 

-----------------

Title: “Save Password” Functionality
Description: Check if the “Save Password” button works when a person uses a correct email address and a new password to enter his/hers account after forgetting their initial password
Steps to reproduce:
1. Go to http://www.Foodchooser.com//login
2. Select “Sign in” near the “Already a user” text
3. Select “Have you forgotten your password” option
4. Click on the search bar
5. Enter your email 
6. Open your email provider (Yahoo, Google etc)
7. Search for the email automatically sent by the platform 
8. Click on the link inside the received email
9. Enter the new password that replaces the old one
10. Press “Save Password” button
Expected result: User will be redirected to the main platform and an automatic email will be sent to the user’s email to confirm the occured changes
Test data: To test the functionality of the “Save Password” button
User: Max & Pass:56789

-----------------

Title : In-game river functionality

Description : Check if the in-game river has a water sound effect

Steps to reproduce

Run the game
Select “Play” 
Wait for the game to load 
Select “New Game” 
Press “Enter” to confirm the choice
Do the tutorial
Press “M” to open the map
Check for the nearest river
Navigate to to the nearest river
Listen for the water sounds

Expected results : The player should hear the water sound effect

Test data : Max & Password : 292120

-----------------

Title:  Search inventory  functionality

Description: Search for an item and after that use the delete function in the search bar to delete the item from
the inventory.

Steps to reproduce:
1. Go to http://www.Questmaster.com/login
2. Use credentials to login
3. Press “I” button to open inventory menu
4. Click on the search bar
5. Search for the item
6. Click on item
7. Click on “Delete”
8. Click on “Yes” when the delete interrogation appears

Expected result: User will be able to find the searched item in the game and delete the item from the inventory
for him.

Test data: For search: Goat Cheese

User: Max & Pass:56789

-----------------

Title: Test login with correct credentials

Description: Check if the login works when a person uses a correct user/pass to enter the game

Steps to reproduce:

1. Go to www.Questmaster.com/login
2. Add a correct user/pass
3. Press Login button

Expected result : User will be able to login

Test data: User: Max & Pass:123456

-----------------

Title: Testing the functionality of a door to trap a hostile NPC
Description: Check if a hostile NPCs body gets trapped by a door
Steps to reproduce:
run the game
Press “Play”
Wait for the generic load screen to load
Select “Load Game”
Select “Humble Beginnings”
Select “Load”
Wait for the load screen to load
Press “M” button to open the minimap
Search for “Gregori’s Cabin”
Press “M” button to close the minimap
Press “P” button to open “General Menu”
Select  “Mounts” in the “General Menu”
Select “Milos” 
Press “P” button to close “General Menu”
Press “E” to mount “Milos”
Travel to “Gregori’s Cabin”
Attract the attention of a hostile NPC in your director
Try to lure the hostile NPC near a door 
Trap the NPC between the wall and the door
Observe the door 

Expected result: User should see the door blocking the hostile NPC, limiting his/her movements
Test data: To test the functionality of a door to block a hostile NPC
User: SaintHuligan & Pass:727712

-----------------
