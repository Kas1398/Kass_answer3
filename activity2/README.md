# Activities

## Task 1

- Refer to the following link. Discuss how Insertion sort works:
  https://opendsa-server.cs.vt.edu/ODSA/AV/Sorting/insertionsortAV.html

Ans: 
  - In Insertion sort, you compare the key element with the previous elements. If the previous elements are greater than the key element, then you move the previous element to the next position.

## Task 2

- The following snippet is from `./src/insertion.cpp` lines 12-22. Discuss in groups how the code works:

```cpp
    for (int k = 1; k < 10; k++)
    {
        int temp = myarray[k];
        int j = k - 1;
        while (j >= 0 && temp <= myarray[j])
        {
            myarray[j + 1] = myarray[j];
            j = j - 1;
        }
        myarray[j + 1] = temp;
    }
```
Ans: 
  - The first part of the code initializes an array of 10 integers, myarray, and prints the input list.
  - The second part of the code performs the actual sorting of the array using the Insertion sort algorithm. The outer loop 'for (int k = 1; k < 10; k++)' iterates through the array starting from the second element (index 1) to the last element (index 9). 
  - The inner loop "while (j >= 0 && temp <= myarray[j])" compares the current element "temp" with the previous elements in the sorted part of the array and moves them one position to the right if they are greater than "temp". 

## Task 3

- Discuss the complexity analysis of insertion sort. Refer to the link below:
  https://www.softwaretestinghelp.com/insertion-sort/

  Ans: 
    - Insertion sort works the best and can be completed in fewer passes if the array is partially sorted. But as the list grows bigger, its performance decreases. Another advantage of Insertion sort is that it is a Stable sort which means it maintains the order of equal elements in the list.
    - Insertion sort is the most efficient of all the three techniques discussed so far. Here, we assume that the first element is sorted and then repeatedly compare every element to all its previous elements and then place the current element in its correct position in the array.

## Links

- https://cpp.sh/
