def calculator():
    print("Welcome to the Basic Calculator!")
    
    # Prompt the user to enter two numbers
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    # Display the operation options
    print("\nChoose an operation:")
    print("1. Addition (+)")
    print("2. Subtraction (-)")
    print("3. Multiplication (*)")
    print("4. Division (/)")

    # Get the user's choice
    operation = input("\nEnter the number corresponding to the operation (1/2/3/4): ")

    # Perform the selected operation and display the result
    if operation == '1':
        result = num1 + num2
        print(f"\nResult: {num1} + {num2} = {result}")
    elif operation == '2':
        result = num1 - num2
        print(f"\nResult: {num1} - {num2} = {result}")
    elif operation == '3':
        result = num1 * num2
        print(f"\nResult: {num1} * {num2} = {result}")
    elif operation == '4':
        if num2 != 0:
            result = num1 / num2
            print(f"\nResult: {num1} / {num2} = {result}")
        else:
            print("\nError: Division by zero is not allowed.")
    else:
        print("\nInvalid operation selected. Please try again.")

# Run the calculator
calculator()
