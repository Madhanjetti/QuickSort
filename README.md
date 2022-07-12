# QuickSort in C:
QuickSort is a divide & conquer algorithm. 
QuickSort algorithm partitions the complete array around the pivot element. Pivot element can be picked in mulitple ways:

First element as pivot
Last element as pivot
Median element as pivot
Random element as pivot
In this blog we will be picking the last element as pivot element.
partition() is the key process behind the QuickSort algorithm. In partitioning, the pivot element plays an important role.
Pivot is placed at its correct position in the sorted array, all the elements smaller than pivot is placed before it, and all the elements greater than pivot is placed after it. 
All this operation is completed in linear time.
Then the array is divided in two parts from the pivot element (i.e. elements less than pivot & elements greater than pivot) & both the arrays are recursively sorted using Quicksort algorithm
