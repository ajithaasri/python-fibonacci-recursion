# python-fibonacci-recursion

# Python program to find the Nth term in a Fibonacci series using recursion

def Fib(n):
    if n < 0:
        print("The input is incorrect.")
        return None
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return Fib(n - 1) + Fib(n - 2)

# Example usage
n = 7
result = Fib(n)
if result is not None:
    print(f"The {n}th term in the Fibonacci series is:", result)

OUTPUT:

The 7th term in the Fibonacci series is: 8
