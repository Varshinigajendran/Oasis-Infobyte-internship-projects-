def calculate_bmi(weight, height):
    return weight / (height ** 2)

weight = float(input("Enter Your Weight in Kilograms: "))
height = float(input("Enter Your Height in Meters: "))

bmi = calculate_bmi(weight, height)
print("Your Body Mass Index is:", round(bmi, 2))
