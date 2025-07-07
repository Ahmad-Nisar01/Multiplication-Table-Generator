# Multiplication-Table-Generator
Ask the user for a number, then print its multiplication table from 1 to 10.
user = int(input("Enter the number :"))

print(f"the number is {user }")
for i in range (1 , 11):
    print(f" {user} X {i} = { i*user }")