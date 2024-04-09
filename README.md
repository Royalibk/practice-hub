-My recent code:

  print("Type 1 to convert Celcius to Fahrenheit")
  print("Type 2 to convert Fahrenheit to Celcius")

  User_input= int(input("Enter your choice: "))

  if User_input==1:
    request1= float(input("Enter your temp in Celcius: "))
    converter= round((request1* 9/5)+32,2)
    print(f'{request1}°C is {converter}°F')

  elif User_input==2:
    request2= float(input("Enter your temp in Fahrenheit: "))
    converter2= round((request2 - 32)*5/9,2)
    print(f'{request2}°F is {converter2}°C')
except Exception as e:
  print(f"Your input is wrong! exception: {e}")
