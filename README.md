# learning-python
#conditional statement on light:
light = input("light:")
if(light=="red"):
    print("stop")
elif(light=="orange"):
    print("wait")
elif(light=="blue"):
    print("heylo")
else:
    print("go")
#conditional statement on marks:
marks = input("marks:")
if(marks>"90"):
    print("excellent")
elif(marks<="90"):
    print("well done")
else:
    print("good attempt")

#ternary operator
food =input("food:")
eat = "yes" if (food == "cake") else "no"
print (eat)
food =input("food:")
print("sweet") if food=="sugar made" else print ("not sweet")

#clever condition
age = int(input("age:"))
vote = ("yes" , "no") [18>=age]
print (vote)
salary = float(input("salary:"))
taxsystem = salary*(0.10 , 0.20) [salary<30000.00]
print (taxsystem)
salary = float(input("salary:"))
taxsystem = ("yes" , "no") [salary<30000.00]
print (taxsystem)

note: take care of indentation



    
