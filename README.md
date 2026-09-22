name = input("Enter customer name: ")
contact = input("Enter contact number: ")
address = input("Enter address: ")

Product1 = input("Enter item: ")
price1 = int(input("Enter price: "))
quantity1 = int(input("Enter quantity: "))

Product2 = input("Enter item: ")
price2 = int(input("Enter price: "))
quantity2 = int(input("Enter quantity: "))

Product3 = input("Enter item: ")
price3 = int(input("Enter price: "))
quantity3 = int(input("Enter quantity: "))

amount1 = price1 * quantity1
amount2 = price2 * quantity2
amount3 = price3 * quantity3

subtotal = amount1 + amount2 + amount3
discount = subtotal * 0.10
total = subtotal - discount

print("======================================")
print("            ECHO'S STORE              ")
print("======================================")


print("Customer Name:", name)
print("Contact No.:", contact)
print("Address:", address)

print("======================================")
print("Product   Price   Qty   Amount")
print("======================================")

print(Product1, "       ", price1, "   ", quantity1, "   ", amount1)
print(Product2, "       ", price2, "   ", quantity2, "   ", amount2)
print(Product3, "       ", price3, "   ", quantity3, "   ", amount3)

print("======================================")
print("Subtotal:       ", subtotal)
print("Discount (10%): ", discount)
print("======================================")
print("Total:          ", total)
print("======================================")