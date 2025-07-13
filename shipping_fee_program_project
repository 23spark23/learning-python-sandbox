# Hello! 
# This is a project that will take the weight of a package and assign the company's price based on shipping method and weight.
# You can modify the weight variable and run the code, it is going to print out the pricing for every shipping method

# Weight variable for package:
weight = 10

# Ground Shipping charges based on weight:
# if package has 2kg or less - $1.50/kg + $20
# if package has 2kg - 6kg   - $3.00/kg + $20
# if package has 6kg - 10kg  - $4.00/kg + $20
# if package has over 10kg   - $4.75/kg + $20

if weight <= 2:
  cost_ground = weight * 1.5 + 20
elif weight > 2 and weight <= 6:
  cost_ground = weight * 3 + 20
elif weight > 6 and weight <= 10:
  cost_ground = weight * 4 + 20
else:
  cost_ground = weight * 4.75 + 20
print("Ground Shipping $", cost_ground)

# Ground Shipping Premium is a fixed sum = 125$
cost_ground_premium = weight + 125
print("Ground Shipping Premium $", cost_ground_premium)

# Drone Shipping is also based on weight:
# if package has 2kg or less - $4.50/kg
# if package has 2kg - 6kg   - $9.00/kg
# if package has 6kg - 10kg  - $12.00/kg
# if package has over 10kg   - $14.25/kg

if weight <= 2:
  cost_drone = weight * 4.5
elif weight > 2 and weight <= 6:
  cost_drone = weight * 9
elif weight > 6 and weight <= 10:
  cost_drone = weight * 12
else:
  cost_drone = weight * 14.25
print("Drone Shipping $", cost_drone)
