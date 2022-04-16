# Fibonacci_number
#rabbit newborn female and 1 month manture and start to produce offring next month 
#month 
#number of female in a given month 
def fib(n):
    if n==0 or n==1:
        return 1 
    else: 
        return fib(n-1)+fib(n-2)
fib(4)
