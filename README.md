# distance-calc
import math

# Ask the user to enter the coordinates of the first point
x(1) = float(input("Enter x1: "))
y(1) = float(input("Enter y1: "))

# Ask the user to enter the coordinates of the second point
x(2) = float(input("Enter x2: "))
y(2) = float(input("Enter y2: "))

# Compute the distance using the distance formula
distance = math.sqrt(math.pow(x(2) - x(1), 2) + math.pow(y(2) - y(1), 2))

# Display the distance rounded to two decimal places
print(f"The distance between the two points is: {distance:.2f}")
