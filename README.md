# HW_1-22

bubble sort homework(python)

import random

length = 10

num = [90,28,92,1,4,9,32,48,20,75]

print("題目:",num)

for i in range(len(num)):

    for j in range(len(num)-1-i):

      if num[j] > num[j+1]:

        num[j], num[j+1] = num[j+1], num[j]


print("bubble sort:",num)
