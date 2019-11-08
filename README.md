# Password Generator
## The Repository

This repository holds the Javascript code for my password generator.

## Password Generator

This project features a password generator with a length of up to 128 characters and a combination of up to 4 different character types. The user is prompted to choose their desired password character length followed by 4 prompts requesting which character types they would like to have included in their password. An alert is given if the user chooses a password length fewer than 8 or more than 128 characters. An alert is given if the user does not choose at least one of the 4 character types.

Once the user chooses their character length and desired character types, the program runs 1 of 15 password generator funcitons. The randomly generated password is then given in an alert message.

This project has better solidified my understanding of objects, functions, loops, and if/else statements. 

Potential future additions to this project:

* A loop that resets the ability to choose password length and character type if the requirements are not met without having to refreshing the page (Only applicable with current program which uses alerts and confirm functions)

* A styled webpage with functional buttons as opposed to confirm and alert functions

* Determine a DRY solution to this program as opposed to needing 15 password generator functions and 15 if/else statements