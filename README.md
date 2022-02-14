# 14-02-22-ass-2
#find sum of digits in a given number
n=int(input('enter number:'))
sum=0
while(n>0):
    rem=n%10
    sum=sum+rem
    n=n//10
print('The sum of digits:',sum)

output:
enter number:7541
The sum of digits: 17
