n=int(input("enter no of packets"))
b=[0]*n
x=0
l=6
i=4
lct=0

for j in range(0,n):
    b[j] = int(input("enter packet arrival time "))
print(b)

for t in b:
    x1 = x-(t-lct)
    print(x1)
    if(x1<0):
        x1=0
        print(f"packet is conforming {t}")
        x=x1+i
        lct=t
    else:
        if(x1>l):
            print(f"non conforming packet {t}")
        else:
            print(f"packet is conforming {t}")
            x=x1+i
            lct=t
