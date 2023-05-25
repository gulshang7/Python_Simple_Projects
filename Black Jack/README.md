# Black Jack

<p align="center">
  <img width="250" height="250" src="https://github.com/gulshang7/Python_Simple_Projects/assets/124501309/1d9f8258-9402-4632-81e5-e5fbde50345f">
</p>

Here are the requirements:

* You need to create a simple text-based BlackJack game
* The game needs to have one player versus an automated dealer.
* The player can stand or hit.
* The player must be able to pick their betting amount.
* You need to keep track of the player's total money.
* You need to alert the player of wins, losses, or busts, etc...

## STEP BY STEP PROCESS:

### Step 1: 
Import the random module. This will be used to shuffle the deck prior to dealing. Then, declare variables to store suits, ranks and values. You can develop your own system, or copy ours below. Finally, declare a Boolean value to be used to control while loops. This is a common practice used to control the flow of the game.

### Step 2: 
Create a Card Class. A Card object really only needs two attributes: suit and rank. You might add an attribute for "value" - we chose to handle value later when developing our Hand class.

### Step 3: 
Create a Deck Class. Here we might store 52 card objects in a list that can later be shuffled. First, though, we need to instantiate all 52 unique card objects and add them to our list. So long as the Card class definition appears in our code, we can build Card objects inside our Deck __init__ method. Consider iterating over sequences of suits and ranks to build out each card.

### Step 4: 
Create a Hand Class. In addition to holding Card objects dealt from the Deck, the Hand class may be used to calculate the value of those cards using the values dictionary defined above. It may also need to adjust for the value of Aces when appropriate.

### Step 5: 
Create a Chips Class. In addition to decks of cards and hands, we need to keep track of a Player's starting chips, bets, and ongoing winnings. This could be done using global variables, but in the spirit of object oriented programming, let's make a Chips class instead!

### Step 6: 
Write a function for taking bets. Since we're asking the user for an integer value, this would be a good place to use try/except. Remember to check that a Player's bet can be covered by their available chips.

### Step 7: 
Write a function for taking hits. Either player can take hits until they bust. This function will be called during gameplay anytime a Player requests a hit, or a Dealer's hand is less than 17. It should take in Deck and Hand objects as arguments, and deal one card off the deck and add it to the Hand. You may want it to check for aces in the event that a player's hand exceeds 21.

### Step 8:
Write a function prompting the Player to Hit or Stand. This function should accept the deck and the player's hand as arguments, and assign playing as a global variable.If the Player Hits, employ the hit() function above. If the Player Stands, set the playing variable to False - this will control the behavior of a while loop later on in our code.

### Step 9: 
Write functions to display cards. When the game starts, and after each time Player takes a card, the dealer's first card is hidden and all of Player's cards are visible. At the end of the hand all cards are shown, and you may want to show each hand's total value. Write a function for each of these scenarios.

### Step 10: 
Write functions to handle end of game scenarios. Remember to pass player's hand, dealer's hand and chips as needed.

### [Jupyter Notebook](https://github.com/gulshang7/Python_Simple_Projects/blob/main/Black%20Jack/Black%20Jack%20Game.ipynb)
### [Go to my LinkedIn](https://www.linkedin.com/in/gulshan-gedam-362905209/) 🌐

## My Other Projects:

- [ATLIQ Sales Insight](https://github.com/gulshang7/ATLIQ_Sales_Insight_Data_Analysis_using_SQL_and_Tableau) 💻

- [Financial Consumer Complaints Data Analysis](https://github.com/gulshang7/Financial-Consumer-Complaints-Data-Analysis-Using-Tableau-Dashboard) 📜

- [KPI Dashboard of Car Sales Opportunities](https://github.com/gulshang7/KPI_Dashboard_of_Car_sales_Win_Loss_Data_Analysis_using_Excel_and_Tableau) 🛰️

- [Github Profile](https://github.com/gulshang7) 🧮

- [Linkedin](https://www.linkedin.com/in/gulshan-gedam-362905209/) 🤝

