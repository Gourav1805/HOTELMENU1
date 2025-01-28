# HOTELMENU1
print("\n\nWelcome to ECLIPSE Restaurant !!")

print("-:   MENU   :-")
print("\nPizza : Rs =40 \nBurger : Rs 50 \nNoodles : Rs60 \nSandwich : Rs70\nCoffee : Rs 40\n")

menu ={
    'Pizza': 40 , 'Burger' : 50 , 'Noodles' : 60 , 'Sandwich' : 70 , 'Coffee' : 40
}


order_total = 0

item1 = input("enter the name of item you want to order : ")
if item1 in menu : 
    order_total += menu[item1]
    print("Your item has been added to the cart.")

else: 
    print("this is not available in our restaurant.\nplease order anything else. ")

another_order = input("do you want to order anything else ? (yes/no) ")

if another_order == "yes" :

    item2 = input("enter the name of item you want to order : ")
    if item2 in menu : 
        order_total += menu[item2]
        print("Your item has been added to the cart.")

else: 
    print("this is not available in our restaurant.\nplease order anything else. ")


another_order = input("do you want to order anything else ? (yes/no) ")

if another_order == "yes" :

    item3 = input("enter the name of item you want to order : ")
    if item3 in menu : 
        order_total += menu[item3]
        print("Your item has been added to the cart.")

else: 
    print("this is not available in our restaurant.\nplease order anything else. ")

print("the total amount of items to pay is  Rs " + str(order_total))

print("thanks for visiting.")
print("we would love to welcome you again.")
print("Saunf-cheeni kha lo piliz.")
