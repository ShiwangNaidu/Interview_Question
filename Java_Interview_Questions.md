# Question 1
##### Given a square matrix, the task is that we turn it by 180 degrees in an anti-clockwise direction without using any extra space. 
Examples : 
```js
Input :  1  2  3
         4  5  6
         7  8  9
```
```js
Output : 9 8 7 
         6 5 4 
         3 2 1
```
```js
Input :  1 2 3 4 
         5 6 7 8 
         9 0 1 2 
         3 4 5 6 
```
```js
Output : 6 5 4 3 
         2 1 0 9 
         8 7 6 5 
         4 3 2 1
```


# Question 2
#####  Given an unsorted array of integers, sort the array into a wave like array. An array ‘arr[0..n-1]’ is sorted in wave form if arr[0] >= arr[1] <= arr[2] >= arr[3] <= arr[4]

Example
```js
Input:  arr[] = {10, 5, 6, 3, 2, 20, 100, 80}
```
```js
 Output: arr[] = {10, 5, 6, 2, 20, 3, 100, 80} OR
                 {20, 5, 10, 2, 80, 6, 100, 3} OR
                 any other array that is in wave form
```

```js
10		6		20		100
	5		2		3			80
```

```js
Input:  arr[] = {2, 4, 6, 8, 10, 20}
```
```js
 Output: arr[] = {4, 2, 8, 6, 20, 10} OR
                 any other array that is in wave form
```
```js
 Input:  arr[] = {3, 6, 5, 10, 7, 20}
 ```
 ```js
 Output: arr[] = {6, 3, 10, 5, 20, 7} OR
                 any other array that is in wave form
```




# Question 3
#####  A frog is crossing a river. The river is divided into x units and at each unit there may or may not exist a stone. The frog can jump on a stone, but it must not jump into the water.
##### Given a list of stones’ positions (in units) in sorted ascending order, determine if the frog is able to cross the river by landing on the last stone. Initially, the frog is on the first stone and assume the first jump must be 1 unit.
##### If the frog’s last jump was k units, then its next jump must be either k — 1, k, or k + 1 units. Note that the frog can only jump in the forward direction.
```js
Constraints :

2≤Number of Stones<1100
Each Stone’s position will be a non negative value < 2³¹
1st stone’s position is always 0.

Example :
[0,1,3,5,6,8,12,17]

There are a total of 8 stones.
The first stone at the 0th unit, second stone at the 1st unit,
third stone at the 3rd unit, and so on...
The last stone at the 17th unit.

Return true. The frog can jump to the last stone by jumping
1 unit to the 2nd stone, then 2 units to the 3rd stone, then
2 units to the 4th stone, then 3 units to the 6th stone,
4 units to the 7th stone, and 5 units to the 8th stone.
```


# Question 4
##### Partition problem is to determine whether a given set can be partitioned into two subsets such that the sum of elements in both subsets is the same. 
```js
Examples: 
arr[] = {1, 5, 11, 5}
Output: true 
The array can be partitioned as {1, 5, 5} and {11}
```
```js
arr[] = {1, 5, 3}
Output: false 
The array cannot be partitioned into equal sum sets.
```

# Question 5

##### Minimum number of deletion in a string to make it a palindrome
```js
Input : aebcbda
Output : 2
Remove characters 'e' and 'd'
Resultant string will be 'abcba'
which is a palindromic string
```

# Question 6
##### Given an array which is sorted, but after sorting some elements are moved to either of the adjacent positions, i.e., arr[i] may be present at arr[i+1] or arr[i-1]. Write an efficient function to search an element in this array. Basically the element arr[i] can only be swapped with either arr[i+1] or arr[i-1].


```js
For example consider the array {2, 3, 10, 4, 40}, 4 is moved to next position and 10 is moved to previous position.
```
```js
* HINT -Efficient Program ,user should use Binary Search approach
```

```js
Example : 
 
Input: arr[] =  {10, 3, 40, 20, 50, 80, 70}, key = 40
Output: 2 
Output is index of 40 in given array

Input: arr[] =  {10, 3, 40, 20, 50, 80, 70}, key = 90
Output: -1
-1 is returned to indicate element is not present
```

# Question 7
##### Given a Positive Number. Find The Number is even or odd without using Modulus(%) or Divide(/).


# Question 8

##### Given N lines and one starting point and destination point in 2-dimensional space. These N lines divide the space into some blocks. We need to print the minimum number of jumps to reach destination point from starting point. We can jump from one block to other block only if they share a side.

```js
Examples:
Input : Lines = [x = 0, y = 0, x + y – 2 = 0]
        Start point = [1, 1], 
        Dest point  = [-2, -1]
Output : 2    
```
```js
We need to jump 2 times (B4 -> B3 then B3 -> B5 
or B4 -> B6 then B6 -> B5) to reach destination 
point from starting point shown in below diagram. 
Each block i is given an id Bi in the diagram.


```
![SpaceByBlock](https://user-images.githubusercontent.com/59438970/162400479-7795db52-339c-4592-aec9-7bff05546e1c.jpg)


