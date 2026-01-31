class Solution(object):
    def intersect(self, nums1, nums2):
        
        from collections import Counter
        
        count1 = Counter(nums1)
        count2 = Counter(nums2)
        
        result = []
        for num in count1:
            if num in count2:
                result.extend([num] * min(count1[num], count2[num]))
        
        return result
