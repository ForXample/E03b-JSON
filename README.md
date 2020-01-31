# E03b-JSON
This exercise will give you the opportunity to edit an existing JSON file (in the game-description format we are using for MSCH-C220). Fork and Clone this repository and then make the following edits to zork.json:

 - Change the exit in FORE3 from UP to DOWN (fin.)
 - Add a desc in MGRAT: "If you stay here much longer, you will be eaten by a Grue" (fin.)
 - In MIRR2, add a new exit, "NORTH" with a target of MIRR1 (fin.)
 - In BATS, add a description: "This is a cave full of bats. They are currently sleeping" (fin.)
 - In MINE7, add a new item, a "SIGN" with a description that reads "A sign is here that points down". You don't need to add a "TAKE" key/value. (fin.)
 - IN FCHMP, MRDE, MRDW, MRGE, MRGW, and PCELL add a description: "You are stuck with no way out!" (fin.)
 - Add new exit in BKENT called "ROB" with a target of "BKVAU" (fin.)
 - In EGYPT, add a new item, a "MUMMY" with a description that reads "An ancient Egyptian mummy is sprawled on the floor". If the player tries to "TAKE" it, the response should be "You stuff the mummy in to your sack". (fin.)
 - In DEAD7, change the description to "You have reached a dead end" (fin.)
 - In CP change the name to "Just a room (not at all suspicious)" (fin.)
 
If you need to check to see if you have produced a valid JSON file, you can validate it at https://jsonformatter.org/json-editor.

Edit the LICENSE and README.md and submit a URL to your repository on Canvas.

This is for the assignment for C220. Zixi Liu 2020
