# Fibonachii
#circuitous path to fibonacci numbers.
def fibo(s,a=0,b=1): #(desired number of terms,start,stop) last two are optional
    if a+b==1:
        print(1,end=' ')
    print(a+b,end=' ')
    if s-2==0:
        return 'done'
    fibo(s-1,b,a+b)
