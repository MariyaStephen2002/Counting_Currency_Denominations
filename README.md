# Counting_Currency_Denominations
#This program helps in determining the required counts of various denominations of currency notes and coins for a given amount.
a=int(input("Enter  the amount to count : ")) #get input from run time
b=a//500 #count for 500  (quo a/500)
c=a%500 #remi a/500 => input for next demonination
d=c//200 #200
e=c%200
f=e//100 #100
g=e%100
h=g//50 #50
i=g%50
j=i//20 #20
k=i%20
l=k//10 #10
m=k%10
n=m//5 #5
o=m%5
p=o//2 #2
q=o%2
r=q//1 #1
print('FiveHundred : ',b) # total count of 500₹ note
print('TwoHundred  : ',d) # total count of 200₹ note
print('Hundred     : ',f) # total count of 100₹ note
print('fifty       : ',h) # total count of 50₹ note
print('Twenty      : ',j) # total count of 20₹ note
print('Ten         : ',l) # total count of 10₹ note
print('Five        : ',n) # total count of 5₹ coin
print('Two         : ',p) # total count of 2₹ coin
print('One         : ',r) # total count of 1₹ coin
