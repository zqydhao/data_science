# Python 3
## 41
https://leetcode-cn.com/problems/first-missing-positive/solution/que-shi-de-di-yi-ge-zheng-shu-by-leetcode/
这里告诉我们：这个missing 最小1 最大len(nums)+1

主要依据的解法（木桶原理）：
https://leetcode-cn.com/problems/first-missing-positive/solution/tong-pai-xu-python-dai-ma-by-liweiwei1419/
#把4 放到 nums[4-1] 位置去；排好之后然后找到第一个不和谐的位置所应的element 若没有就是 len(nums)+1可以取到

### 学习点1
def swap(nums, index1, index2):
      nums[index1], nums[index2] = nums[index2], nums[index1]
