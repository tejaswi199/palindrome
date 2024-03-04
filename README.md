#approach-1
n = input()
if n == n[::-1]:
  print("Palindrome")
else:
  print("Not a Palindrome")
#approach-2
n = int(input())
temp = n
res = 0
while n > 0:
  r = n%10
  res = (res*10)+r
  n = n // 10
if temp == res:
  print("Palindrome")
else:
  print("Not a Palindrome")
