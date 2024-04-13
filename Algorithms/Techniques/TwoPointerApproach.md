# Two Pointer Approach

1. use two pointers - usually one starts at **index 0** and at **input.length-1**
2. This can change depending on the problem. its not always as mentioned in pointer #1, but the basic idea is using two pointers to effectively iterate through the array.
3. loop through the array until two pointers meet or cross each other.

```
function fn(arr):
    left = 0
    right = arr.length - 1

    while left < right:
        Do some logic here depending on the problem
        Do some more logic here to decide on one of the following:
            1. left++
            2. right--
            3. Both left++ and right--
```