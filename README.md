🎉 Fun Calculator 🧮

A simple yet fun Python calculator that performs basic arithmetic operations — Addition, Subtraction, Multiplication, and Division — on two numbers entered by the user.

🚀 Features
Accepts decimal numbers using float() input.

Performs:

Addition ➕

Subtraction ➖

Multiplication ✖

Division ➗

Outputs all results clearly to the console.

📋 How It Works
User Inputs:
Prompts the user to enter two numbers, which can include decimals.

Arithmetic Operations:
Computes and stores:

sum_result → the sum of the two numbers

difference_result → the result of subtracting the second number from the first

product_result → the product of both numbers

quotient_result → the result of dividing the first number by the second

Display Results:
Prints all four results to the console in a friendly format.

📝 Code Usage
bash
Copy
Edit
$ python fun_calculator.py
Example interaction:

yaml
Copy
Edit
Enter the first number: 8
Enter the second number: 2

Results of your two numbers:
Sum: 10.0
Difference: 6.0
Product: 16.0
Quotient: 4.0
⚠️ Important Notes
Division by Zero is not handled explicitly in the script. If the second number is 0, it will raise a ZeroDivisionError. Add a check if needed for production use.

💡 Suggestions for Improvement
Add exception handling to prevent crashes (e.g., try/except for invalid input or division by zero).

Extend it to support more operations like exponentiation or modulus.

Add a user-friendly loop to allow multiple calculations without restarting the script.

👨‍💻 Author
Crafted with fun by Azeez Yusuf
(https://github.com/TechTrader001)
