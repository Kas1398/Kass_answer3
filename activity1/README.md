# Activities

## Task 1

- Refer to the following link. Discuss how bubble sort works:
  https://opendsa-server.cs.vt.edu/embed/bubblesortAV

  Ans: 
     - Bubble sort works, Starting from the beginning of the list, Compare the first value in the list with the next one up. If the first value is bigger, swap the positions of the two values, Move to the second value in the list, Keep going until there are no more items to compare.


## Task 2

- Refer to the following link. Your task is to show the behavior for one iteration of the outer for loop of Bubble Sort (Try at least 3 cases).
  https://opendsa-server.cs.vt.edu/ODSA/Exercises/Sorting/BubsortPRO.html

  Ans: In this exercise, we are required to demonstrate the behavior of the outer for loop of the bubble sort algorithm. To do this, we simply click on entries in the array to swap them in the way that bubble sort would during its first pass. We verfiy that the output is what we expect it to be after one iteration of the outer for loop.

## Task 3

- The following snippet is from `./src/bubble.cpp` lines 16-28. Discuss in groups how the code works:

```cpp

    for (i = 0; i < 10; i++)
    {
        for (j = i + 1; j < 10; j++)
        {
            if (a[j] < a[i])
            {
                temp = a[i];
                a[i] = a[j];
                a[j] = temp;
            }
        }
        pass++;
    }
```

- The following snippet is from `./src/selection.cpp` lines 34-41. Discuss in groups how the code works:

```cpp
    for (j = i + 1; j < 10; j++)
    {
        if (myarray[j] < ele_small)
        {
            ele_small = myarray[j];
            position = j;
        }
    }
```

## Task 4: Individual, at home

- Discuss the complexity analysis of selection sort. Refer to the link below:
  https://www.softwaretestinghelp.com/selection-sort/

  Ans: 
    - Selection sort is yet another simplest sorting technique that can be easily implemented. Selection sort works best when the range of the values to be sorted is known. Thus as far as sorting of data structures using selection sort is concerned, we can only sort data structure which are linear and of finite size.
    - The time complexity of O(n2) is mainly because of the use of two for loops. Note that the selection sort technique never takes more than O(n) swaps and is beneficial when the memory write operation proves to be costly.

## Links

- https://cpp.sh/
