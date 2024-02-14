/**********************************************************************
 *  README.txt                                                   
 *  ENGR105 - Final Project 
 *  Project Title: Blackjack                     
 **********************************************************************/

Authors: Zach Rudder and Tyler Chaudhary


/**********************************************************************
Instructions
**********************************************************************/
To launch the code, run the "start.m" file. To interact with the app, 
follow the onscreen instructions to place a bet, start a hand, and 
choose to hit or stand. 

/**********************************************************************
Summary
**********************************************************************/
This project is intended to be a simulator of the popular card game
Blackjack. This app allows a user to "sit" at the table and visualize
the game as it progresses. The user starts with $5000, and is able to 
place a bet from $0 to $5000 throughout the game. Their total amount
of money is tracked and displayed through their entire time on the app.
The player can choose to "Hit" or "Stand" and the winner of the hand is
determined using typical Blackjack rules. 
Some of the major challenges we faced were figuring out the best way to
create a card deck, learning how to use GUI in Matlab and how to work in
the AppDesigner workspace, and how to follow the specific rules of the 
game. Many conditional were used as is the nature of the game, and we had 
to develop an algorithm to determine the value of an ace after each new card
was played, as the value can change between 1 or 11 depending on the other 
cards in the hand. After developing the base code, we had to learn 
how to add all the graphics in AppDesigner and how the user inputs work 
with the base code we had developed. Multiple times we ran into problems
with the wrong cards or images being displayed at the wrong time, and had
to work out each problem on its own. Our main goal was to make the app 
as close to popular online Blackjack apps as possible, so the graphics
part of the project was very important to us. 


/**********************************************************************
Dependencies
**********************************************************************/
The entire project was built in Matlab AppDesigner.