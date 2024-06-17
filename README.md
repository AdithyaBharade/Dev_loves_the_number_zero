y=int(input("Enter thr Y value: "))
while (y>0):
    if (y>x):
        x,y=y,x
    else:
        x,y=y,x-y 
print(x)
