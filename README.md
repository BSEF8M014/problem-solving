# problem-solving
Top Problems must be revised before interview
- [Array](README.md#Array)
- [Linked List](README.md#Linked-List)
- [Math & Stats](README.md#Math-&-Stats)
- [Strings](README.md#Strings)
- [Trees](README.md#Trees)
- [Stack & Queues](README.md#Stack-&-Queues)
- [Graph](README.md#Graph)
- [Back Tracking](README.md#Back-Tracking)
- [Dynamic Programming](README.md#Dynamic-Programming)
- [Miscellaneous](README.md#Miscellaneous)

## Array 
### Binary Search On Sorted Array
  Binary Search is the most efficient way to search in Sorted array.  
  **Time Complexity :** O(*log*n)  
  **Space Complexity :** O(1) (iterative Solution), O(*log*n) recursive Solution
  #### Iterative Solution
  ```
    def binary_search(nums, target):
	    low = 0
	    high = len(nums) - 1
	    while low <= high:
    		mid = low + ((high - low) // 2)
    		if nums[mid] == target:
    			return mid
    		elif target < nums[mid]:
    			high = mid - 1
    		elif target > nums[mid]:
    			low = mid + 1
    	return -1
  ```
### Rotate An Array By N Elements
### Rotated Binary Search
### Smallest Common Number Between Three Arrays
### Find Low and High Index of a key in sorted array
### Move all Zeros to the beging of the Array
### Best Time to Buy and Sell Stock to Maximize Profit
### Merge An Array with Overlapping Intervals
### Find Pair With Given Sum in Array
### Squares Of a Sorted Array
### Container With Most Water
### Quick Sort Algorithm
### Sort Colors
### Arrange The Largest Number
### Shuffle An Array
### First Missing Positive Integer
## Linked-List
## Math-&-Stats
## Strings
## Trees
## Stack-&-Queues
## Graph
## Back-Tracking
## Dynamic-Programming
## Miscellaneous
