# ASS-2-19-02-22
PRIME COUNT
T=int(input())
while(T>0):
    N=int(input())
    sum=0
    for num in range(2,N+1): #num=1 num=2 num=3 num=4
        c=0
        for var in range(1,1+num): #(1,1) (1,2) (1,2) (1,4)
            if(num%var==0):
                c+=1
        if(c==2):
            sum=sum+1
    T-=1
    print(sum)
    OUTPUT:
    1
    4
    2
    8
    
