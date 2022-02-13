# donald2
 #this is a code that checks weather a number is or isn' part of a fibonacci sequenceS
n=int(input("Enter the number: "))
c=0
a=1
b=1
if n==0 or n==1:
    print("Yes")
else:
    while c<n:
        c=a+b
        b=a
        a=c
    if c==n:
        print("Yes its a fibonacci")
    else:
        print("No its not a fibonacci")
