# Fibonacci-series-using-iteration
a = 0
b = 1
n = int(input("Enter the number of terms in the sequence: "))
if n <= 0:
    print("Invalid input")
elif n == 1:
    print(a)
else:
    print(a, b, end=" ")
    for _ in range(n - 2):
        c = a + b
        print(c, end=" ")
        a, b = b, c

OUTPUT:
Enter the number of terms in the sequence: 7
0 1 1 2 3 5 8
