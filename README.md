# Problem.-5
# Problem 5: Break Even Point

# Input fixed costs, price per unit, and cost per unit
fixed_costs = float(input("Enter fixed costs: "))
price_per_unit = float(input("Enter price per unit: "))
cost_per_unit = float(input("Enter cost per unit: "))

# Calculate break even point
break_even_point = fixed_costs / (price_per_unit - cost_per_unit)

# Display break even point
print(f"\nBreak Even Point: {break_even_point}")
