# 5.1 LAB*: Program: Food receipt

This is a zybook project which type python code that performe a final cost in base of food item name, price, and quantity.

## Getting Started

Pycharm need be install on you local machine to execute the code before submit on zybook

### Prerequisites

Program: Food receipt requires Pycharm Community edition. link to download [PyCharm](https://www.jetbrains.com/pycharm/download/#section=windows)

## Running

```
After download pycharm follow the next step:
```

```
Run the exe for install Pycharm. Then click next
On the next screen, you can change or leave as default the path location
On the next scree, you could create a desktop shortcut ither for 32 or 64-bit launcher. Then click next
On the Choose Start Menu folder select JetBrain and click on Install
Once installation finish you should a receive a message that pycharm is installed.
Select the Run Pycharm Community Edition box, then click on finish
After click on Finish you can selec create New project
```

## To execute the code Program: Food Receipt
Copy the following code 
```
#This code represents the input from user

item1_name = str(input("Enter food item name:\n"))
item1_price = float(input("Enter item price:\n"))
item1_quant = int(input("Enter item quantity:"))
```
```
#Represents the calculation total cost

item1_total = float(item1_price * item1_quant)
```
```
#Print the receipt of the first items with the total cost

print ("")
print ("\nRECEIPT")
print (item1_quant, item1_name, "@ $%.2f = $%.2f"%(item1_price, item1_total))
print ("Total cost: $%.2f" % item1_total)
print ("")
print ("")
```
```
#This code represents the second input from user

item2_name = str(input("Enter second food item name:\n"))
item2_price = float(input("Enter item price:\n"))
item2_quant = int(input("Enter item quantity:"))
```
```
#Represents the second calculation of total cost

item2_total = float(item2_price * item2_quant)
```

```
#Represents the calculation for the customer gratuity

totals = item1_total + item2_total
gratuity = totals * 0.15
total_grat = totals + gratuity
print ("")
print ("")
```
```
#This print second item name cost with the total cost of both items with the gratuity percentage 

print ("RECEIPT")
print (item1_quant, item1_name, "@ $%.2f = $%.2f" %(item1_price, item1_total))
print (item2_quant, item2_name, "@ $%.2f = $%.2f" %(item2_price, item2_total))
print ("Total cost: $%.2f" %totals)
print ("")
print ("15%% gratuity: $%.2f" %gratuity)
print ("Total with tip: $%.2f" % total_grat)
```
## Inputs:
```
Enter food item name:
hot dog
Enter item price:
2.00
Enter item quantity:
5
Enter second food item name:
ice cream
Enter item price:
2.50
Enter item quantity:
4
```
## Output 
```
RECEIPT
5 hot dog @ $2.00 = $10.00
4 ice cream @ $2.50 = $10.00
Total cost: $20.00

15% gratuity: $3.00
Total with tip: $23.00
```

## Thanks
Thanks for your attention
