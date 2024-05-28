#simple interest
def simple_interest(p,r,t)
print("The principle is",p)
print("The time period is",t)
print("The rate of interest",r)
SI=(p*r*t)/100
print("simple interest is",SI)
#DRIVER CODE
P= int(input("Enter the principle amount"))
R= int(input("Enter the time period"))
T= int(input("Enter rate of interest"))
simple_inyerest(P,R,T)
