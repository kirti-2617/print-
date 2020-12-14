nums= [34, 1, 0, -23]
nums= [28 ,30 ,-65 ,0 , 50]
print ("Original numbers in the list: ",nums)
new_nums = list(filter(lambda x: x >0, nums))
print("positive numbers in the list: ",new_nums)
