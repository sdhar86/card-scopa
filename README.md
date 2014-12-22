A multiplayer cardgame project built in meteorJS

This code was written while following a tutsplus tutporial written by Andrew Burgess.
======================================================================================

<h3>Scopa : 2 player game (can be more than 2, but this app is for 2)</h3>
<h4> <a href="http://en.wikipedia.org/wiki/Scopa"> Wikipedia: Scopa</a> </h4>
<h4>Italian card deck</h4>
<ul>
    <li> Italian deck has 40 cards and 4 suites (Cups, Clubs, Swords, Coins)</li>
    <li> 10 cards in a suits are from 1 - 10. 1 is Ace(A), 10 is King(K), 9 is Queen(Q) and 8 is Knight (N)</li>
</ul>
<h4> Scopa: Rules</h4>
<ul>
    <li>3 cards are dealt, table has 4 cards to begin with</li>
    <li>Cards are played to match with table cards</li>
    <li>Numbers are matched 3 to 3, Q to Q  or one card to match multiple card e.g. :  7 matches 3 and 4</li>
    <li>You get 1 point by capturing more cards than the other player</li>
    <li>You get 1 point by capturing more cards from the coin suit than the other player</li>
    <li>You get 1 point by matching 7 of coins (Sette Bello)</li>
    <li>You get 1 point by clearing out the table more than the other player (Scopa)</li>
    <li>Primera: who ever has the sum of best card from each of the four suits</li>
</ul>
<h4>Primera scoring</h4>
<ul>
    <li>Seven (sette) = 21 points</li>
    <li>Six (sei) = 18 points</li>
    <li>Ace (asso) = 16 points</li>
    <li>Five (cinque) = 15 points</li>
    <li>Four (quattro) = 14 points</li>
    <li>Three (tre) = 13 points</li>
    <li>Two (due) = 12 points</li>
    <li>Two (due) = 12 points</li>
    <li>King (re) = 10 points</li>
</ul>
<p>If a player captures the sevens of cups and coins, the six of clubs and the ace of swords, that team's prime is (21 + 21 + 18 + 16) = 76. Player with higher prime gets the point</p>