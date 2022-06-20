-----PIZZA DELIVERY-----

print("welcome to precious pizza delivery")
size = input("which size would you like? s, m, l: ")
bill = 0
if size == "s":
  print("your bill is #1500")
  bill = 1500
elif size == "m":
  print("your bill is #2000")
  bill = 2000
elif size == "l":
  print("your bill is #2500")
  bill = 2500
  sauce = input("do you want more more sauce? y or n: ")
  if sauce == "y":
    bill += 100
    print(f"your bill is #{bill}")

drinks = input("would you like youguth or coke? ")
if drinks == "youguth":
  bill += 400
  print(f"your total bill is #{bill}")
elif drinks == "coke":
  bill += 200
  print(f"your total bill is #{bill}")
