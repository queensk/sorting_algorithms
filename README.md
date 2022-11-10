# 0x1B. C - Sorting algorithms & Big O

# ``` sorting_algorithms```

> a sorting algorithm is an algorithm that puts elements of a list into an order. The most frequently used orders are numerical order and lexicographical order, and either ascending or descending. Efficient sorting is important for optimizing the efficiency of other algorithms (such as search and merge algorithms) that require input data to be in sorted lists. Sorting is also often useful for canonicalizing data and for producing human-readable output.

> In other words, a sorted array is an array that is in a particular order. For example, [a,b,c,d][a,b,c,d] is sorted alphabetically, [1,2,3,4,5][1,2,3,4,5] is a list of       integers sorted in increasing order, and [5,4,3,2,1][5,4,3,2,1] is a list of integers sorted in decreasing order.
> A sorting algorithm takes an array as input and outputs a permutation of that array that is sorted.
## There are two broad types of sorting algorithms:- 
- integer sorts 
- comparison sorts.

``` 0. Bubble sort ```

> Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm

> Prototype: void bubble_sort(int *array, size_t size);
> You’re expected to print the array after each time you swap two elements (See example below)
> Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:

>in the best case
>in the average case
>in the worst case

``` 1. Insertion sort ```
 
>Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm

>Prototype: void insertion_sort_list(listint_t **list);
>You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
>You’re expected to print the list after each time you swap two elements (See example below)
>Write in the file 1-O, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:

>in the best case
>in the average case
>in the worst case

``` 2. Selection sort ```

> Write a function that sorts an array of integers in ascending order using the Selection sort algorithm

> Prototype: void selection_sort(int *array, size_t size);
> You’re expected to print the array after each time you swap two elements (See example below)
> Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

> in the best case
> in the average case
> in the worst case

``` 3. Quick sort ```
>Write a function that sorts an array of integers in ascending order using the Quick sort algorithm

> Prototype: void quick_sort(int *array, size_t size);
> You must implement the Lomuto partition scheme.
> The pivot should always be the last element of the partition being sorted.
> You’re expected to print the array after each time you swap two elements (See example below)
> Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

> in the best case
> in the average case
> in the worst case