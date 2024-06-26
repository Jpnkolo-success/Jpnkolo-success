sales1 = input("What is your name?: ")
sales2 = input("How many cars you sold last month?: ")
if int(sales2) < 10:
  print("This month: $12 Hr")
else:
  print("This month: $15 Hr")
sales3 = input("What is your goal this month?: ")
sales4 = input("How many both New and Used are you going to sell?: ")
if int(sales4) > 10:
  print("Great!! By selling 10+ cars, you'll have BONUS of $ 2500 CASH")
else:
  print("No BONUS")
print(sales1)
print(sales2)
print(sales3)
print(sales4)
print("Thanks for your dedication. KEEP IT UP")
print(f"-{sales1}")
print(f"-${sales2}")
print(f"-{sales3} Cars")
