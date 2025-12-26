    
d=int(input("Enter Number of Days :"))
fine=0
if(d<=5):
    fine=d*0.50
    print("fine:",float(fine))
    eilf(d>5 and d<=10)
    i=d-5
    fine=(i*1)+ (5*0.5)
    print("fine:",float(fine))
    eilf(d<10 and d<=30)
    i=d-10
    fine= (i*5)+(5*0.5)+(5*1)
    print("fine :",float(fine))
else:
    i=d-10
    fine = (i*5)+(5*0.50)+(5*1)
    print("your Membership is cancelled")
    print("Fine amount(Rs):",float(fine))

Output:
Enter Number of Days :15
your Membership is cancelled
Fine amount(Rs): 32.5


