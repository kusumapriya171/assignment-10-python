# assignment-10-python
python
lower=input("lower value:")
upper=input("upper value:")
print("prime numbers between", lower,"and", upper, "are:")
for num in range (lower, upper+1):
 if num>1:
  for i in range (2,num):
   if num % i==0:
    break
  else: print(num)
def  count_prime(num,lower,upper):
  count_prime= 0
  for x in num:
    if lower <= x <= upper:
      count_prime += 1
print ( "count_prime:",count_prime )
