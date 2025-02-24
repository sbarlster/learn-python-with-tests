# Cafe with menu items and seats and customers

We have a Cafe with seats and menu items.

1. Customers can enter the cafe unless all the seats are taken
2. Customer can eat a menu item, if it exists on the menu and they are in the Cafe
3. The Cafe owner can add or remove seats

# Attributes
1. Create a class to represent the Cafe
2. Add simple number attribute: number_seats
3. Add list attribute for the: menu_items (will be a list of strings e.g. dohnut, pancakes, flat-white, capuccino)
4. Add list attribute for the: customers (list of customer names e.g. John, Bob, Sarah)

# Methods
5. Add methods to add or remove a menu item (throw Error if menu item is already in the menu or if removing and not in the menu)
6. Add method to add a customer to the cafe (throw an error if no free tables exist)
7. Add a method to allow customer X to eat item Y (throw a custom Error _InvalidCafeOrder_ if customer or menu item does not exist)
