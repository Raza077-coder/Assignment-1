# Assignment-1
[ ]:
Topic: print()
1) Using the python print function print any string value, integer value, boolean value, float value in single print command

In [1]:
2) Using the python print function print hyphon(-) separated any string value, integer value, boolean value, float value in single print command

In [9]:
3) Using the python print function print any string value, integer value, boolean value, float value in separate print command. But every value must be space separated and in single line

In [57]:
4) Can a python print function take no value to print???

In [61]:
print() #yes
TOPIC :Variables in Python Operators
5) One of my friends name is Mr. Ahmed. He is 30 years old. He is a lawer by profession. He has done his bachelors in law in the year 2005. He is working with a reputable law firm 'The Himalya Associates' in Karachi since 2015. He is a handsome lawer with height of 5.10 feets and weight 70600g. His monthly income is Rs. 200k PKR.
Note: Create variables from above text and also assign values from the text.
In [7]:
#Creating Variables. 
fname="Mr.Ahmed"
age=30
profession="lawer"
degree="bachelor in law"
graduation_year=2005
law_firm="The Himalya Associates"
working_since=2015
height=5.10 # in feet
weight=70600 # in gram
monthly_income=200000 #in PKR
In [37]:
#Assigning value from the text.
print (f"My friend name is = {fname}")
print (f"He is {age} yera old")
print (f"He is a {profession}")
print (f"He had done {degree}")
print (f"graduation year{graduation_year}")
print (f"working with {law_firm}")
print (f"height : {height}")
print (f"weight : {weight}")
print (f"salary :{monthly_income} PKR ")
My friend name is = Mr.Ahmed
He is 30 yera old
He is a lawer
He had done bachelor in law
graduation year2005
working with The Himalya Associates
height : 5.1
weight : 70600
salary :200000 PKR 
7) How many years has Mr. Ahmed been working with law firm 'The Himalya Associates'. Create necesary variables and print the correct number of years in working in the firm

In [94]:
print (f"He is working since {working_since}.")
He is working since 2015.
8)Convert the monthly income of Mr. Ahmed in dollars. Create necesary variables and print the income in dollars.

In [102]:
# Assigning the values : creating variables
monthly_income=200000 # in PKR
one_dollar=277

#converting PKR in to Dollar
income_in_dollar = monthly_income // one_dollar 

#display the result : income in to dollar
print (f"Monthly incomein PKR Rs:{monthly_income}")
print (f"monthly income in dollar :{income_in_dollar} $")
Monthly incomein PKR Rs:200000
monthly income in dollar :722 $
9) Check if the income in dollars is a float or integer value. if it is float, re-write the code so that income gets converted in integer. print the income in integer type value

In [166]:
#existing variables 
monthly_income_pkr=200000
conversion_rate = 278.25

#converting to dollar
monthly_income_usd=monthly_income_pkr / conversion_rate 

#checking if the value is float
if isinstance(monthly_income_usd,float):
    
    #Converting to integer
    monthly_income_usd = int(monthly_income_usd) 
    
# display value    in int value
print(f"monthly income usd in int is {monthly_income_usd}")
monthly income usd in int is 718
In [174]:
weight_in_g=70600

weight_in_KG = int(weight_in_g / 1000)

print (f"weight is {weight_in_KG} KG .")
weight is 70 KG .
In [1]:
#11) print the year of birth of Mr. Ahmed.
In [178]:
#type your code here
current_year=2024
age=30
year_of_birth=current_year-age
print (f"The year of birth of Mr. Ahmed is {year_of_birth} .")
The year of birth of Mr. Ahmed is 1994 .
12) Can Rs. 100 be divided equally among 6 students? HINT: % operator (modulo)

In [3]:
10%2
# 10 is completely divisible by2
# 10 is multiple of 2
# 2 is a factor of 10
# 10 comes in table of 2
Out [3]:
0
In [180]:
money=100

student =6

remainder = money % student

if remainder == 0:
    print("yes! it can be divided equally ")
else :
    print("no! it can't")
no! it can't
In [ ]:
