print("------------------------------")
print("MINI STORE POS SYSTEM")
print("------------------------------")
print("\nPRODUCT MENU:")
print("------------------------------")
print ("1. Burger - PHP 50.00")
print ("2. Fries - PHP 35.00")
print ("3. Soft Drink - PHP 25.00")
print ("------------------------------")

products = []
ask = "y"
while ask == "y":
    product = input("Enter product (1-3): ")
    if product == "1":
        product_name = "Burger"
        price = 50.00
    elif product == "2":
        product_name = "Fries"
        price = 35.00
    elif product == "3":
        product_name = "Soft Drink"
        price = 25.00
    else:
        print("Invalid product selection.")
        exit()
    quantity = int(input("Enter quantity: "))
    print ("Added: " + product_name + " " + str(quantity) + "x")
    ask = input("Do you want to add another product? (y/n): ")
    subtotal = price * quantity
    products.append((product_name, quantity, price, subtotal))
    
print("==============================")
print("ORDER RECEIPT")
print("==============================")

print("Products ordered:")
print("Product Name | Quantity | Price | Subtotal")

for product in products:
    print(f" - {product[0]} --- x{product[1]} --- PHP {product[2]:.2f} = PHP {product[3]:.2f}")
print("Total Amount: PHP {:.2f}".format(sum(item[3] for item in products)))
print("================================================================")
print("Thank you for your purchase! We hope to see you again soon.")
print("================================================================")

