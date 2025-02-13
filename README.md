# python-ka-kaam-kiet
auther-himanshu mishra 
python case study 
print("Welcome to the Grocery Store Calculator!")

total_cost = 0  # Initialize total cost

while True:
    print("\n1. Add Item\n2. Calculate Total\n3. Exit")
    choice = input("Enter your choice: ")
    if choice == "1":  # Add item
        item_name = input("Enter item name: ")
        price = float(input("Enter item price: "))
        quantity = int(input("Enter item quantity: "))
        total_cost += price * quantity  # Add to total cost
        print(f"{item_name} added! Subtotal: ₹{total_cost}")
    elif choice == "2":  # Show total cost
        print(f"Total cost of items: ₹{total_cost}")
    elif choice == "3":  # Exit
        print("Thank you for shopping!")
        break
    else:
        print("Invalid choice. Try again.")
        
