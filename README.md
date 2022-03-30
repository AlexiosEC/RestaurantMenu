# RestaurantMenu
Final Project

Imagine you have started up a small restaurant and are trying to make it easier to take and calculate orders. Since your restaurant only sells 9 different items, you assign each one to a number, as shown below.

0. Exit the Order menu
1. Chicken Strips - $3.50
2. French Fries - $2.50
3. Hamburger - $4.00
4. Hotdog - $3.50
5. Large Drink - $1.75
6. Medium Drink - $1.50
7. Milk Shake - $2.25
8. Salad - $3.75
9. Small Drink - $1.25

To quickly take orders, your program should allow the user to type in a string of numbers and then it should calculate the cost of the order. For example, if one large drink, two small drinks, two hamburgers, one hotdog, and a salad are ordered, the user should type in 5993348, and the program should say that it costs $19.50. Error check to make sure that the user did not enter a 0 when ordering.

You should put the menu and associated costs in a file. 

When the program starts, check if the menu file exists. If so, open the file and read it to get the menu items and associated prices. If the file does not exist, create it.

In addition to the menu file, your program will also need a separate file to store the customer's name and order. 

When the program starts, read and print the previous customer's name and display the previous order information. For example, "Previous customer: John Doe; order included milk shake and hot dog. Price was: $5.75". If there is no previous customer, display the message “This is the first customer of the day!”

Your program should show the menu option after every order until ‘0’ is pressed to exit.
