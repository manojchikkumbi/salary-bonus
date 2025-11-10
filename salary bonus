# salary_bonus.py

import sys

# Check if salary is provided as a command-line argument
if len(sys.argv) == 2:
    salary = float(sys.argv[1])
    print("User provided salary value:")
else:
    # Default salary if not provided
    salary = 50000.0
    print("No input given - using default salary:")

# Calculate bonus
bonus = 0.10 * salary
total_salary = salary + bonus

# Display results
print("\n--- Salary Details ---")
print(f"Salary: ₹{salary:.2f}")
print(f"Bonus amount: ₹{bonus:.2f}")
print(f"Total salary after adding bonus: ₹{total_salary:.2f}")
