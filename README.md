```python
#Here we have the menu
menu = ("coke", "fanta", "burger", "pasta", "rice", "chicken", "cake")
print(menu)

# customer greeting
print("Hello, thank you for entering our restaurant, what would you like to order?")

current_order = [] # first create an empty list

while len(current_order)<3:  # you can only order three items
    order = input()   # input the order
    if order in menu:
        print("anything else?")
        current_order.append(order) # adds to the order list
        print(f"So you have ordered {current_order}")
    else:
        print("item not in the menu") # if item not in menu print this

```