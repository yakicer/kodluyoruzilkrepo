# MERGE SORT

## Merge Sort Steps of Given Array 

### Consider an example: {22,27,16,2,18,6}

- The merge sort divides the entire array into two equal parts iteratively until the single values are reached. The array of **6** elements is split into two arrays.
![Step 1](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort1.png "Step 1")
- This has no effect on the order in which elements appear in the original array. Now again, split these two arrays in half.
![Step 2](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort2.png "Step 2")
- Again divide these arrays until we reach the single value that can no longer be divided.
![Step 3](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort3.png "Step 3")
![Step 4](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort4.png"Step 4")
- Next, compare the elements in each list, then merge them in a sorted manner into another list. For example, in the first list, compare 11 and 6, and reverse the order. Next, compare 3 and 24; they are in the correct order. Next, again compare 46 and 22 and put 22then 46. Next, keep 7 as it is.
![Step 5](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort5.png "Step 5")
- Next, compare the lists of two data values in the following iteration of the combining phase, then merge them into a list of found data values in sorted order.
![Step 6](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort6.png "Step 6")
- The list will look like this after the final merge.
![Step 7](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/mergesort7.png "Step 7")

### The final answer is formed by combining sub-arrays as shown in the below image
![All Steps](https://github.com/yakicer/kodluyoruzilkrepo/blob/master/MergeSort/assets/MergeSort.png "All Steps")