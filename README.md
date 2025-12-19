# Finding-the-Smallest-Number-Among-N-Inputs

n=int(input("enter the limit less than 999:"))
small=999
for i in range(1,n+1):
    print("enter",i,end='')
    a=int(input("th number:"))
    if a<small:
        small=a
print("smallest no. is:",small)


output:
enter the limit less than 999:4
enter 1th number:2
enter 2th number:4
enter 3th number:5
enter 4th number:6
smallest no. is: 2

