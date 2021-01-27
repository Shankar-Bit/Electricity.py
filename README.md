# Electricity.py


#Electricity Bill Amount program

x = 100

#Below amt is additional amt carry
a = 75
b = 150
c = 200
unit = int(input("Enter the total units consumed : "))

if unit<=x:
	u1 = (unit * float(1.5)) + a
	print("Total Unit Amt = ", u1)
elif ( unit <= 200):
	u2 = (unit * float(2.5)-x) + b
	print("Total Unit Amt = ", u2)
elif (unit <= 300):
	u3 = (unit * 4 - (x*4)) +c
	print("Total Unit Amt = ", u3)
elif (unit > 300):
	fix = 2000
	print("Fixed amount, no additional charges :" ,fix)



