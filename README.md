# code_rev_array

def rev_array(nums): # reverse an array
    i=0
    j=len(nums)-1
    while i<j:
        nums[i],nums[j]=nums[j],nums[i]
        i+=1
        j-=1
    return nums
print(rev_array([5,4,3,2,1]))


        
