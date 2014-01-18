how-many-coins-problem
======================
amount= float(input("Enter an amount: "))

quarters=0
dimes= 0
nickels = 0
pen= 0 

while amount >= .25:
	amount = amount - .25
	quarters += 1
while amount >= .1:
	amount = amount - .1
	dimes += 1
while amount >= .05:
	amount = amount - .05
	nickels += 1
while amount >= 0.01:
	amount = amount - .01
	pen += 1

if quarters > 0:
	print str(quarters)+ " quarters"
if dimes > 0:
	print str(dimes)+ " dimes"
if nickels > 0:
	print str(nickels)+ " nickels"
if pen > 0:
	print str(pen) + " pennies"



