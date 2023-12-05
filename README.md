# python-2
project 2
height = int(input())
bill = 0

if height >= 120:
  print("you can ride the roller coaster!")
  
  age = int(input("what is your age?"))
  
  if age < 12:
     bill = 5
     print("Child ticket is $5.")
  elif age <= 18:
    bill = 7
    print("Teenage ticket is $7.")
  else:
    bill = 12
    print("Adult ticket is $12.")
    
  wants_photo = input("Do you want a photo taken? Y OR N.")
  if wants_photo == "Y":
     bill += 3
  print(f"your final bill is {bill}")
else: 
  print("sorry, you have to grow taller before you can ride")
