[Week3_4_P2_arriaga.py for MPG code.docx](https://github.com/Arriaga8022/week3/files/8612406/Week3_4_P2_arriaga.py.for.MPG.code.docx)

Problem 2: Calculate the average miles per gallon obtained on a trip. Given/inputs vehicle name, trip name, the amount of gas used, gas price, and the number of miles driven. (The formula to calculate miles per gallon is miles per gallon = number of miles driven / amount of gas used.) Display/outputs vehicle name, trip name, gas used, miles driven, gas price and MPG
 
![image](https://user-images.githubusercontent.com/102768674/166506621-d3f2c095-c595-462a-9bc8-ceb4f8261516.png)


gasamount =16
milesdriven=1750
gasmileage= milesdriven/gasamount
print("amount of gas used:")
print(gasamount)
print("nuber of miles driven:")
print(milesdriven)
print("gas mileage:")
print(gasmileage)
milesdriven= float (input ("How many miles did you drive?"))
gasamount = float(input ("How many gallons of gas did you use?"))
gasMileage = float ( (milesdriven / gasamount))
print ("you drove %s miles, and used %s gallons of gas, so your gas mileage is: %s MPG" % (milesDriven, gasamount, gasmileage))
