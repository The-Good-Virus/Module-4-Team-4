# Module-4-Team-4
This repository is a teamwork assignment to create a numbered a program to print options presented to the user and allow the user to select an option from the list.

Pseudocode

Your team is to write a program to print a number of options presented to the user and allow the user to select an option from the list.

The options should be numbered from 1 – 9; although your team can use less than 9 options, but make sure there are at least 5 options. If the user selects a valid choice, the program should print a short message. The message should include the value that the user typed.

number = int(input("Choose a number from 1-5!"))

if number == 1:
    print("Learn Python")
elif number == 2:
    print("Learn Java")
elif number == 3:
    print("Go swimming")
elif number == 4:
    print("Have dinner")
elif number == 5:
    print("Go to bed")
elif number == 0:
    print("Exit")
else:
    print("Wrong number!")
