# Calculator-Using-Python

while True:

  # Taking Input From User.

  num1 = int(input("Enter First Number"))
  operation = input("Enter Operation")
  num2 = int(input("Enter Second Number"))
  
  # Checking Conditions.

  if operation == '+':
      print(num1 + num2)

  elif operation == '-':
      print(num1 - num2)

  elif operation == '*':
      print(num1 * num2)

  elif operation == '/':
      print(num1 / num2)

  elif operation == '//':
      print(num1 // num2)

  elif operation == '**':
      print(num1 ** num2)

  else:
      print("Syntax Error")

