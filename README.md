name=input("enter your name:")
year_of_birth=int(input("enter your year_of_birth:"))
current_year=2025
age=current_year-year_of_birth
print("hello,",name)
print("your age is:", age)
if age>=60:
  print("you are a senior citizen")
else:
  print("you are not a senior 