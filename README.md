# feb-17-ass-1
Assignment1
 n = int(input("Enter n value:"))
a = 0
b = 1
Sum = 0
for Num in range(0, n):
    print(a, end = '  ')
    Sum = Sum + a
    Next = a + b
    a = b
    b = Next
print("\n Sum of the fibonacci series is %d" %Sum)
 output:
 Enter n value: 10
 0 1 1 2 3 5 8 13 21 34
