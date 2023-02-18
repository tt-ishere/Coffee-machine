# Coffee-machine
 This code simulates a coffee machine (OOP) and allows the user to select a type of coffee they want to purchase. It makes use of three classes: Menu, CoffeeMaker, and MoneyMachine, each with their own specific responsibilities.
     from menu import Menu: Imports the Menu class from a file called "menu.py".

    from coffee_maker import CoffeeMaker: Imports the CoffeeMaker class from a file called "coffee_maker.py".

    from money_machine import MoneyMachine: Imports the MoneyMachine class from a file called "money_machine.py".

    coffeemaker = CoffeeMaker(): Instantiates a new CoffeeMaker object.

    money = MoneyMachine(): Instantiates a new MoneyMachine object.

    menu = Menu(): Instantiates a new Menu object.

    is_off = False: Initializes a boolean variable to keep track of whether the coffee machine should be turned off or not.

    def make_drink():: Defines a function named make_drink() that checks if the requested drink can be made by checking if there are enough ingredients and if the payment is successful, and then makes the drink if both conditions are met.

    while not is_off:: This is the main loop that keeps the program running until the user chooses to turn off the coffee machine.

    choice = input("What would you like? (espresso, latte, or cappuccino): ").lower(): Takes the user's choice of drink as input and converts it to lowercase.

    if choice == "report":: If the user types "report", the CoffeeMaker and MoneyMachine classes will print out the current status of the machine.

    elif choice == "espresso":, elif choice == "latte":, elif choice == "cappuccino":: If the user types the name of a drink, the make_drink() function is called with the corresponding drink object.

    elif choice == "off":: If the user types "off", the program ends and the coffee machine is turned off.
