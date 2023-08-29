# Economic-class
# cook your dish here
for i in range (int(input())):
    n = int(input())
    arrs= list(map(int,input().split()))
    arrd= list(map(int,input().split()))
    c=0
    for i in range(n):
        if(arrs[i]==arrd[i]):
            c+=1
    print(c)
