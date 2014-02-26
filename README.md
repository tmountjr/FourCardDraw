FourCard Draw
=============

Consider a probability question: Five cards, four of which are aces, are placed face-down on the table. The rules are simple - draw a card, and if it's an ace, draw another card. What is the probability of drawing four aces in a row?

Mathematically, it's simple:

* On the first draw, your chances of drawing an ace are 4/5.
* One the second draw, your chances are now 3/4.
* Third draw, 2/3
* Fourth and final draw, 1/2.

So your chances are 4/5 * 3/4 * 2/3 * 1/2 = 24/120 = 1/5, or 20%.

But that seems low. So this is a simulator designed to play this game of chance millions of times over and track how many times the computer "wins" the game over an enormous sample size.
