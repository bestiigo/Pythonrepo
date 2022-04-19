# Pythonrepo
angle1 = int(input("Please enter the first angle: "))
angle2 = int(input("Please enter the first angle: "))
angle3 = int(input("Please enter the first angle: "))

if angle1 + angle2 + angle3 > 180:
    print("The entered values are not valid.")
if angle1 or angle2 or angle3 < 0:
    print("Angles smaller than 0 are not valid.")
else:
    print("The triangle is a right triangle")
