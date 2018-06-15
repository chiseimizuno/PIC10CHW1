# PIC10CHW1

Hello, this github repo tracks my progress in completing a working siete y medio card game using C++ and user interaction through the console.  

## Introduction

Professor Salazar provided an incomplete version of the card game, which can be found in the initial commit on this repo.  

### Start Date

This project was started on April 30th.

### Goal of Game

The goal of the game is to get cards whose total value comes the closest to 7½ without going over it. Getting a card total over 7½ is called "busting".

### Possible Outcomes

- The player comes closer to 7½ than the dealer or the dealer busts but the player did not bust. In this case the player wins the round and the player's money increases by the amount that was bet.
- The dealer comes closer to 7½ than the player, or the player busts. In this case the player loses the round and the player's money decreases by the amount that was bet.
- Both, the player and dealer bust. In this case the player loses the round and the player's money decreases by the amount that was bet. This is called house advantage.
- Both the player and the dealer have the same total and they do not bust. In this case a tie is declared and no money is exchanged.

## Sample Codes

Here are some sample runs of the siete y medio card game.

### Sample User Iteraction 

How the user iteracted with the console to play the game

```
You have $100. Enter bet: 99
Your cards:
	Dos de copas        (Two of cups).
Your total is 2. Do you want another card (y/n)? n
Dealer's cards:	Sota de espadas     (Jack of spades).
The dealer's total is 0.5.

New card:
	Rey de espadas (King of spades).

Dealer's cards:
	Sota de espadas     (Jack of spades).
	Rey de espadas      (King of spades).
The dealer's total is 1.
```

### Companion Log File

Helps Understand the progress of the game

```
-----------------------------------------------

Game number: 1		Money left: $100
Bet: 99

Your cards:
	Dos de copas        (Two of cups).
Your total: 2.

Dealer's cards:
	Siete de bastos     (Seven of clubs).
	Sota de espadas     (Jack of spades).
	Rey de espadas      (King of spades).
Dealer's total is 8.

-----------------------------------------------
```
## Progression

### Problems

Thankfully, due to the my professor's awesome lectures, I had no problem finishing the homework in no time

### Hours taken

11 hours 30 minutes

### Resources used

Professor Salazar's Lecture Slides

## Program used

C++ Using Visual Studio 2015 (Widnows 10)

## Authors

Chisei Mizuno
