# TASK1- TASK2
# 1. Check whether employee age is above 21 and salary is above 30000
age = int(input("Enter age: "))
salary = int(input("Enter salary: "))

if age > 21 and salary > 30000:
    print("Eligible")
else:
    print("Not Eligible")


# 2. Check whether student passed in two subjects
mark1 = int(input("Enter first subject marks: "))
mark2 = int(input("Enter second subject marks: "))

if mark1 >= 35 and mark2 >= 35:
    print("Passed")
else:
    print("Failed")


# 3. Check whether entered value is between two ranges
num = int(input("Enter number: "))

if num > 10 and num < 50:
    print("Number is within range")
else:
    print("Number is outside range")


# 4. Check whether username and password are correct
username = "admin"
password = "1234"

u = input("Enter username: ")
p = input("Enter password: ")

if u == username and p == password:
    print("Login Successful")
else:
    print("Invalid Username or Password")


# 5. Check whether temperature is within safe range
temp = int(input("Enter temperature: "))

if temp > 20 and temp < 40:
    print("Temperature is safe")
else:
    print("Temperature is not safe")


# 6. Check whether both entered numbers are even
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

if a % 2 == 0 and b % 2 == 0:
    print("Both are even")
else:
    print("Both are not even")


# 7. Check whether both entered numbers are positive
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

if a > 0 and b > 0:
    print("Both are positive")
else:
    print("Both are not positive")


# 8. Check whether person is eligible for driving
age = int(input("Enter age: "))
license = input("Do you have license (yes/no): ")

if age >= 18 and license == "yes":
    print("Eligible for driving")
else:
    print("Not eligible for driving")


# 9. Check whether project progress meets deadline condition
days = int(input("Enter remaining days: "))
progress = int(input("Enter progress percentage: "))

if days > 5 and progress >= 80:
    print("Project is on track")
else:
    print("Project is delayed")


# 10. Check whether attendance and marks satisfy eligibility
attendance = int(input("Enter attendance percentage: "))
marks = int(input("Enter marks: "))

if attendance >= 75 and marks >= 35:
    print("Eligible")
else:
    print("Not Eligible")


# 11. Check whether entered role is Admin or Manager
role = input("Enter role: ")

if role == "Admin" or role == "Manager":
    print("Access Granted")
else:
    print("Access Denied")


# 12. Check whether student scored distinction in any one subject
sub1 = int(input("Enter first subject marks: "))
sub2 = int(input("Enter second subject marks: "))

if sub1 > 75 or sub2 > 75:
    print("Distinction")
else:
    print("No Distinction")


# 13. Check whether entered day is weekend
day = input("Enter day: ")

if day == "Saturday" or day == "Sunday":
    print("Weekend")
else:
    print("Weekday")


# 14. Check whether selected category matches two possible values
category = input("Enter category: ")

if category == "Gold" or category == "Silver":
    print("Category matched")
else:
    print("Category not matched")


# 15. Check whether salary or experience satisfies requirement
salary = int(input("Enter salary: "))
experience = int(input("Enter experience: "))

if salary >= 50000 or experience >= 5:
    print("Requirement satisfied")
else:
    print("Requirement not satisfied")


# 16. Check whether temperature is extremely low or high
temp = int(input("Enter temperature: "))

if temp < 10 or temp > 40:
    print("Extreme temperature")
else:
    print("Normal temperature")


# 17. Check whether entered username matches predefined values
username = input("Enter username: ")

if username == "admin" or username == "manager":
    print("Valid Username")
else:
    print("Invalid Username")


# 18. Check whether selected option belongs to given choices
option = input("Enter option: ")

if option == "A" or option == "B" or option == "C":
    print("Valid Option")
else:
    print("Invalid Option")


# 19. Check whether entered city matches allowed cities
city = input("Enter city: ")

if city == "Hyderabad" or city == "Chennai":
    print("Allowed City")
else:
    print("Not Allowed")


# 20. Check whether entered number matches predefined values
num = int(input("Enter number: "))

if num == 10 or num == 20 or num == 30:
    print("Matched")
else:
    print("Not Matched")


# 21. Check whether user is not admin
user = input("Enter role: ")

if not user == "admin":
    print("User is not admin")
else:
    print("User is admin")


# 22. Check whether entered number is not positive
num = int(input("Enter number: "))

if not (num > 0):
    print("Number is not positive")
else:
    print("Number is positive")


# 23. Check whether entered value is not empty
value = input("Enter value: ")

if not value == "":
    print("Value is not empty")
else:
    print("Value is empty")


# 24. Check whether file is not available
file_available = False

if not file_available:
    print("File is not available")
else:
    print("File is available")


# 25. Check whether employee is not active
active = False

if not active:
    print("Employee is not active")
else:
    print("Employee is active")


# 26. Check whether project status is not completed
status = input("Enter project status: ")

if not status == "completed":
    print("Project not completed")
else:
    print("Project completed")


# 27. Check whether password is not correct
password = input("Enter password: ")

if password != "1234":
    print("Incorrect Password")
else:
    print("Correct Password")


# 28. Check whether temperature is not safe
temp = int(input("Enter temperature: "))
safe = temp > 20 and temp < 40

if not safe:
    print("Temperature is not safe")
else:
    print("Temperature is safe")


# 29. Check whether selected option is not allowed
option = input("Enter option: ")

if not option == "allowed":
    print("Option not allowed")
else:
    print("Option allowed")


# 30. Check whether marks are not passing marks
marks = int(input("Enter marks: "))

if not (marks >= 35):
    print("Fail")
else:
    print("Pass")
#Task2 -
# 1. Check Employee promotion eligibility
age = int(input("Enter age: "))
experience = int(input("Enter experience: "))
salary = int(input("Enter salary: "))

if age > 25 and experience > 5 and salary > 50000:
    print("Eligible for Promotion")
else:
    print("Not Eligible")


# 2. Check student distinction category
maths = int(input("Enter maths marks: "))
science = int(input("Enter science marks: "))
english = int(input("Enter english marks: "))

if maths >= 75 and science >= 75 and english >= 75:
    print("Distinction")
elif maths >= 35 and science >= 35 and english >= 35:
    print("Pass")
else:
    print("Fail")


# 3. Check website login system
username = "admin"
password = "1234"
otp = "5678"

u = input("Enter username: ")
p = input("Enter password: ")
o = input("Enter OTP: ")

if u == username and p == password and o == otp:
    print("Login Successful")
else:
    print("Invalid Credentials")


# 4. Check internet package category
speed = int(input("Enter speed: "))
data = int(input("Enter data usage: "))
days = int(input("Enter remaining days: "))

if speed > 100 and data > 500 and days > 20:
    print("Premium Plan")
elif speed > 50 and data > 200 and days > 10:
    print("Standard Plan")
else:
    print("Basic Plan")


# 5. Check job eligibility
degree = input("Do you have degree (yes/no): ")
experience = int(input("Enter experience: "))
age = int(input("Enter age: "))

if degree == "yes" and experience >= 2 and age > 21:
    print("Eligible for Interview")
else:
    print("Not Eligible")


# 6. Check flight boarding eligibility
ticket = input("Ticket available (yes/no): ")
passport = input("Passport available (yes/no): ")
luggage = int(input("Enter luggage weight: "))

if ticket == "yes" and passport == "yes" and luggage < 30:
    print("Boarding Allowed")
else:
    print("Boarding Denied")


# 7. Check scholarship eligibility
marks = int(input("Enter marks: "))
attendance = int(input("Enter attendance: "))
income = int(input("Enter family income: "))

if marks >= 85 and attendance >= 90 and income < 300000:
    print("Scholarship Approved")
else:
    print("Scholarship Rejected")


# 8. Check mobile unlock system
pin = "1234"

p = input("Enter PIN: ")
face = input("Face detected (yes/no): ")
finger = input("Fingerprint detected (yes/no): ")

if p == pin and face == "yes" and finger == "yes":
    print("Mobile Unlocked")
else:
    print("Access Denied")


# 9. Check hotel booking eligibility
rooms = int(input("Enter number of rooms: "))
days = int(input("Enter number of days: "))
budget = int(input("Enter budget: "))

if rooms >= 2 and days >= 3 and budget > 50000:
    print("Luxury Booking")
elif budget > 20000:
    print("Standard Booking")
else:
    print("Budget Booking")


# 10. Check exam topper category
sub1 = int(input("Enter subject 1 marks: "))
sub2 = int(input("Enter subject 2 marks: "))
sub3 = int(input("Enter subject 3 marks: "))

total = sub1 + sub2 + sub3

if total >= 270:
    print("Topper")
elif total >= 180:
    print("Average")
else:
    print("Needs Improvement")


# 11. Check gym membership category
age = int(input("Enter age: "))
weight = int(input("Enter weight: "))
height = float(input("Enter height: "))

if age > 18 and weight > 50 and height > 5.5:
    print("Fitness Category A")
elif age > 18 and weight > 40:
    print("Fitness Category B")
else:
    print("Basic Category")


# 12. Check traffic penalty system
helmet = input("Helmet available (yes/no): ")
license = input("License available (yes/no): ")
speed = int(input("Enter speed: "))

if helmet == "yes" and license == "yes" and speed < 80:
    print("No Fine")
elif speed >= 80:
    print("Heavy Fine")
else:
    print("Normal Fine")


# 13. Check movie ticket pricing
age = int(input("Enter age: "))
day = input("Enter day: ")
member = input("Membership available (yes/no): ")

if age < 18 and member == "yes" and day == "Sunday":
    print("50% Discount")
elif member == "yes":
    print("25% Discount")
else:
    print("No Discount")


# 14. Check weather alert system
temperature = int(input("Enter temperature: "))
wind = int(input("Enter wind speed: "))
rain = input("Rain status (yes/no): ")

if temperature > 40 and wind > 50 and rain == "no":
    print("Heat Alert")
elif wind > 70 and rain == "yes":
    print("Storm Alert")
else:
    print("Normal Weather")


# 15. Check online shopping offer
amount = int(input("Enter purchase amount: "))
coupon = input("Coupon available (yes/no): ")
member = input("Premium membership (yes/no): ")

if amount > 10000 and coupon == "yes" and member == "yes":
    print("Maximum Discount")
elif amount > 5000 and coupon == "yes":
    print("Medium Discount")
else:
    print("No Discount")


# 16. Check server room access
idcard = input("ID card available (yes/no): ")
fingerprint = input("Fingerprint available (yes/no): ")
accesslevel = int(input("Enter access level: "))

if idcard == "yes" and fingerprint == "yes" and accesslevel > 5:
    print("Access Granted")
else:
    print("Access Restricted")


# 17. Check sports team selection
speed = int(input("Enter speed score: "))
fitness = int(input("Enter fitness score: "))
discipline = int(input("Enter discipline score: "))

if speed > 80 and fitness > 80 and discipline > 80:
    print("Selected")
elif speed > 60 and fitness > 60:
    print("Waiting List")
else:
    print("Rejected")


# 18. Check laptop purchase recommendation
budget = int(input("Enter budget: "))
ram = int(input("Enter RAM: "))
storage = int(input("Enter storage: "))

if budget > 100000 and ram >= 16 and storage >= 512:
    print("Gaming Laptop")
elif budget > 50000 and ram >= 8:
    print("Office Laptop")
else:
    print("Basic Laptop")


# 19. Check bank loan approval
salary = int(input("Enter salary: "))
creditscore = int(input("Enter credit score: "))
experience = int(input("Enter experience: "))

if salary > 50000 and creditscore > 750 and experience > 3:
    print("Loan Approved")
elif salary > 30000 and creditscore > 650:
    print("Loan Under Review")
else:
    print("Loan Rejected")


# 20. Check smart home security system
door = input("Door status (yes/no): ")
camera = input("Camera status (yes/no): ")
alarm = input("Alarm status (yes/no): ")

if door == "yes" and camera == "yes" and alarm == "yes":
    print("Home Secure")
else:
    print("Security Warning")
