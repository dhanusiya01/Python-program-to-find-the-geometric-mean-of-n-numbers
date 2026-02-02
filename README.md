# Python-program-to-find-the-geometric-mean-of-n-numbers
c = 0
p = 1.0
count = int(input("Enter the number of values: "))
while(c<count):
    x = float(input("Enter a real number: "))
    c = c+1
    p = p * x
gm = pow(p,1.0/count)
print("The geometric mean is: ",gm)

output:
Enter the number of values: 5
Enter a real number: 6
Enter a real number: 6
Enter a real number: 7
Enter a real number: 9
Enter a real number: 3
The geometric mean is:  5.841883083691009

