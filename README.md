# TASK1-
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
