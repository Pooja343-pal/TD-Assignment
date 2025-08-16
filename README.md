
# Assignment6-Task1
#Create a dictionary of students marks 
Write a Python program that:
1.   Creates a dictionary where student names are keys and their marks are values.
2.   Asks the user to input a student's name.
3.   Retrieves and displays the corresponding marks.
4.   If the student’s name is not found, display an appropriate message.

#Assignement2-Module3-Task1

# Problem Statement:  Write a Python program that:
# 1. 	Takes an integer input from the user.
# 2. 	Checks whether the number is even or odd using an if-else statement.

# Step 1: Take integer input from the user
number = int(input("Enter an integer: "))

# Step 2: Check if the number is even or odd
if number % 2 == 0:
    # Step 3: Display result for even number
    print(f"The number {number} is even.")
else:
    # Step 3: Display result for odd number
    print(f"The number {number} is odd.")

    # Assignment2-Module3-Task2

    Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.

    #  Initialize the variable total_sum by 0
total_sum = 0

# Loop  from 1 to 50
for num in range(1, 51):
    total_sum += num  # Add each number to total_sum

#  Display the final sum
print(f"The sum of integers from 1 to 50 is: {total_sum}")
