# Tip_calculator
# PROJECT
print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10 12 15 "))
people = int(input("How many people to split the bill? "))

#providing the tip in percentage that coverts into percentage by 100
tip_in_percentage=bill/100

#assigning the total tip by occured bill * percentage tip
total_tip=bill*tip_in_percentage

#total bill is calculated by occured bill + tip bill total
total_bill=bill+total_tip

#calculating the bill for each person; assigning total bill / total people shared
bill_per_person=total_bill/people

#overall bill is calculated by rounding the per person bill to two digits
final_money=round(bill_per_person,2)

#printing the output for final bill for each person
print(f"each person should pay: $ {final_money}")



