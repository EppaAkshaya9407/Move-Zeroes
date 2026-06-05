# Move-Zeroes
nums = list(map(int,input("Enter integers separated by spaces:").split()))
c= 0
n=len(nums)
for i in range(n):
    if nums[i] != 0:
        nums[c] = nums[i]
         c+= 1
while c <n:
    nums[c] = 0
    c+= 1
print(nums)
