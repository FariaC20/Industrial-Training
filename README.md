# Industrial-Training

# Write a python code to print from 1 to 10
print("Print the number from 1 to 10:")
for i in range(1, 11):
    print(i)

# Write a program to print fibonacci numbers
n_num = int(input("How many numbers to print? "))

#First two terms
n1, n2 = 0, 1
count = 0
print("Fibonacci sequence:")
while count < n_num:
    print(n1)
    nth = n1 + n2
    #update values
    n1 = n2
    n2 = nth
    count += 1