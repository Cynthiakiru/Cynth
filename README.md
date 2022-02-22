# Chalan
This is to a create a code in python to display a chalan.
This code is created by Cynthia Kirupakaran
#################################
Code
#################################
name=input("Enter you name: ")
roll_number=int(input("Enter your roll number: "))
from datetime import date

today = date.today()

d1 = today.strftime("%d/%m/%Y")
print("Todays Date =", d1)

Amount=int(input("Enter the amount to be transferred: "))
Purpose=input("Enter the purpose of transferring: ")
from datetime import datetime

now = datetime.now()

current_time = now.strftime("%H-%M")
print("Your Form Number Is =", current_time)
print("\n\nName: {}\nroll number: {}\nTodays Date: {}\nAmount to be tranferred: {}\npurpose of transferring: {}\nYour form number: {}".format(name,roll_number,d1,Amount,Purpose,current_time))
###################################
Sample output
###################################
Name: Raj
roll number: 45
Todays Date: 22/02/2022
Amount to be tranferred: 25000
purpose of transferring: Exam Fee
Your form number: 16-09
###################################



