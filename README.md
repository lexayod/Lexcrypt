#AYODELE Alexander Adedotun
#FE/23/39321642
#Data Science Week1 Assignment

#Ages of Students in Data Science Class of Twelve.

ages = [17, 18, 19, 20, 22, 21, 26, 25, 24, 23, 26, 27]

#Script1: Calculate Basic Statistics

#SUM
sum_total = sum(ages)

print(sum_total)

#AVERAGE
avg = sum_total / len(ages)

print(avg)

#roundup Average to 2 decimal places
print("Average:", round(avg, 2))

#MIN
minimum = min(ages)
print(minimum)

#MAX
maximum = max(ages)
print(maximum)

#RANGE
range = max(ages) - min(ages)
print("Range:", range)


#MEAN
from statistics import mean

ages = [17, 18, 19, 20, 22, 21, 26, 25, 24, 23, 26, 27]

result = mean(ages)

print("Mean:", round (result, 2))


#MEDIAN
from statistics import median

ages = [17, 18, 19, 20, 22, 21, 26, 25, 24, 23, 26, 27]

result = median(ages)

print("Median:", result)

#MODE
from statistics import mode

ages = [17, 18, 19, 20, 22, 21, 26, 25, 24, 23, 26, 27]

result = mode(ages)

print("Mode:", result)

#convert mode result to float
print("Mode_Float:", float(result))

#Script 2: Convert Integer to Float

ages = [17, 18, 19, 20, 22, 21, 26, 25, 24, 23, 26, 27]


print(float(ages[0]))

print(float(ages[4]/2.5))

print(float(25/5))

#In the case of converting float to integer
print(int(25/5))

#LEXCRYPT 
#X_handle(@lexzayo)
