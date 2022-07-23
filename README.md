# vending-machine

This was my first capstone project at Tech Elevator

It's a CLI vending machine program, with money handling, inventory management, and transaction logging, along with unit tests.

When provided a pipe dilineated set up items to sell, app reads in and populates an inventory of items and a count for each.

Each unique item inherits from a superclass sale item and is polymorphic in the sound the machine makes when each item is vended.

Running balance is calculated, and at end of transaction, correct change is dispensed in coins,

in as few coins as possible, largest to smallest.


