# program-to-calculate-the-size-of-a-square-footing-use-python-math-module.

#program to calculate the size of a square footing, whose allowable
#footing area is 50 sq.ft. use python math module. (hints: Math.sqrt()) 


import math

def calculation(area):
    size = math.sqrt(area)
    return size

output = calculation(area = 50)
output = round(output,2)

print("The dimension of the footing in ft  = ", output)
