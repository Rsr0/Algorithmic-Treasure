# Documentation

## **Majority Element**

Asked in: 
<img src= "https://img.shields.io/badge/-Microsoft-black" height="25">&nbsp;&nbsp;
<img src= "https://img.shields.io/badge/-Yahoo-purple" height="25">&nbsp;&nbsp;
<img src= "https://img.shields.io/badge/-Google-Red" height="25">&nbsp;&nbsp;
<img src= "https://img.shields.io/badge/-Interviewbit-skyblue">&nbsp;&nbsp;
<img src= "https://img.shields.io/badge/-Python-brown">&nbsp;&nbsp;


### Problem Statement 
Given an array of size ```n```, find the majority element. The majority element is the element that appears more than ```floor(n/2)``` times.

You may assume that the array is non-empty and the majority element always exist in the array.




**Example :**

        Input : [2, 1, 2]
        
        Return  : 2 which occurs 2 times which is greater than 3/2.
        
 ### Solution :
 **Sorting :** 
 If the elements are sorted in monotonically increasing (or decreasing) order, the majority element can be found at index `[n/2]` & `([n/2]+1)` incidentally, if *n* is even.


        Sort the array
        return the element at n/2 position

 
           
 >>Time complexity : **O(nlogn)**

***[For Reference](https://www.interviewbit.com/problems/majority-element/)***
