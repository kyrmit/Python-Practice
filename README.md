Python-Practice
===============

Python practice exercises
# average of n number

N = 5
Total = 0
count = 0

while count < N:
    number = float(raw_input("Enter a number"))
    Total = Total + number
    count = count + 1
average = (Total/N)
print Total
print "N=%d","Total=%f" % (N, Total)
print "average=%f" % (average)
