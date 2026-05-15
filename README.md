# Travel-Cost-Calc
location = input("Enter your location:")
buses = int(input("How many buses do you take daily? "))
BusFare = float(input("Cost per bus (£): "))

while buses <= 0:
    print("Error, number must be more than 0")
    exit()

DailyCost = buses * BusFare
MonthlyCost = DailyCost * 30
YearCost = DailyCost * 365

print("Monthly cost: £", MonthlyCost)
print("Yearly cost: £", YearCost)
