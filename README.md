a = input("Your current height in cms: ")
b = input('Gender (Male / Female): ')
 = input('Your age ( This program is for 8 to 18 year olds only): ')

a = int(a)  # Convert height input to an integer
b = int(b) # Convert gender input to an integer
c = int(c)  # Convert age input to an integer

if b == 1 :
    if c == 8:
        z = 72
    elif c == 9:
        z = 75
    elif c == 10:
        z = 78
    elif c == 11:
        z = 81
    elif c == 12:
        z = 84
    elif c == 13:
        z = 88
    elif c == 14:
        z = 92
    elif c == 15:
        z = 95
    elif c == 16:
        z = 98
    elif c == 17:
        z = 99
    elif c == 18:
        z = 100
    else:
        print('Invalid Age')  # Print an error message for invalid age
        z = 1  # Assign a default value to avoid errors
elif b == 2:
    if c == 8:
        z = 77
    elif c == 9:
        z = 81
    elif c == 10:
        z = 84
    elif c == 11:
        z = 88
    elif c == 12:
        z = 91
    elif c == 13:
        z = 95
    elif c == 14:
        z = 98
    elif c == 15:
        z = 99
    elif c == 16:
        z = 99
    elif c == 17:
        z = 100
    elif c == 18:
        z = 100
    else:
        print('Invalid Age ')  # Print an error message for invalid age 
        z = 1  # Assign a default value to avoid errors
else:
    print('Invalid Gender')  
    z = 1 # Assign a default value to avoid errors

if z != 1:  
    final_height = (a / z) * 100
    print("Your final height will approximately be", final_height, "cms")
