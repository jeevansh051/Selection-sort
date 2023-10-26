# Selection-sort
A basic cpp code while describing Selection-sort

## Theory:
- Selection sort is a sorting algorithm that selects the smallest element from an unsorted list and sets it at the beginning of the unsorted list in each iteration.
- It sorts an array by repeatedly choosing the smallest member from the unsorted segment and placing it at the beginning (in ascending order).

### Advantages of Selection Sort Algorithm:
- Simple and easy to understand.
- Works well with small datasets.

### Disadvantages of the Selection Sort Algorithm:
- Selection sort has a time complexity of O(n^2) in the worst and average case.
- Does not work well on large datasets.
- Does not preserve the relative order of items with equal keys which means it is not stable.

### How it works:
- There are some important steps, lets try to sort an array buy smallest to largest as an example:
  
- IN The whole array, the values are compared and the smallest is swapped with the first element of the array.
- IN the next iteratiuon,rest of the elements excepty the first one are compared and the smallest value is put in the second index.
- Ans so on the array gets sorted.

### Explaination And Outcomes:
- We enter the no. of elements in the array.
- Then we enter those number of elementsal values.
- A user defined function named sort tales the array's address and its number of elements as arguments and sorts the array.
- Then the arrayt is printed out.
