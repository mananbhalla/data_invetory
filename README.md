# day 18 python code with Harry https://youtu.be/-tCFyIyKVx0?si=XpiJxicIZZxNYdRd

a = input("Enter name: ")
b = input("Enter the year of birth: ")
if len(b) != 4:
    print("Enter a valid year of birth")
    b = input("Enter the year of birth again: ")
else:
    print("")
b = int(b)
c = input("Enter the country name: ")
d = input("Enter the city name: ")
e = input("Enter the address: ")
f = input("Enter the phone number: ")
if len(f) != 10:
    print("enter a valid phone number")

g = input("Enter the email ID: ")
h = input("Enter the age: ")
i = input("Enter the current year: ")

if len(i) != 4:

    print("enter a valid year")

j = [a, b, c, d, e, f, g, h, i]
print("The items in the list are:", len(j))
for i in j:
    print(i)
