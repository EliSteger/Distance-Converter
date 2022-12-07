import csv
import sys

print("===Conversion Calculator===")
print("1. Miles to kilometers")
print("2. kilometers to miles")
print("3. Quit")
choice = input("Enter your choice:")

if choice == "1":
	print("You have chosen to convert to kilometers. Please input amount of miles")
	miles = input()
	miles_to_kms = float(miles)*1.60934
	print(f"{miles} miles is equal to {round(miles_to_kms, 2)} kilometers.")
elif choice == "2":
	print("You have chosen to convert to miles. Please input amount of kilometers")
	kms = input()
	kms_to_miles = float(kms)/1.60934
	print(f"{kms} kilometers is equal to {round(kms_to_miles, 2)} miles.")
elif choice == "3":
	sys.exit
else:
	print("Sorry, you can only choose 1-3. Please try again.")
