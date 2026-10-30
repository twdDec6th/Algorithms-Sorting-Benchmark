
##Student Information
##Name:هبة خالد قدح
##UniversityID:3168038
##Group:A
## Results Table (Execution Time in microseconds)
| Algorithm | Random | Reverse | Fully Sorted | Partially Sorted |
|-----------|--------|---------|--------------|------------------|
| Selection Sort | 3870930 | 2967545 | 1808517 | 1813650 |
| Insertion Sort | 753951 | 1532757 | 101 | 151754 |
| Bubble Sort | 21823153 | 8120407 | 4768501 | 7658591 |
| Merge Sort | 23337 | 9301 | 9002 | 16821 |
| Quick Sort | 16326 | 14635 | 10032 | 7182 |
#Comparative Chart Illustrating Performance Across Different Cases.
<img width="3730" height="1923" alt="chart" src="https://github.com/user-attachments/assets/05b6c9da-e4ee-4ad4-b6c8-4c053a056391" />
## Comparison of the Performance Difference Between O(N²) and O(N log N) Algorithms

### 1. O(N²) Algorithms
These include: Selection Sort, Insertion Sort, Bubble Sort.

Their execution time increases significantly as the number of elements grows, because the number of operations increases approximately with the square of the input size.

### 2. O(N log N) Algorithms
These include: Merge Sort, Quick Sort (on average).

They generally provide faster performance when dealing with large amounts of data, because their number of operations grows more slowly than O(N²).

## Identifying the Best Algorithm for Fully Sorted and Partially Sorted Data, with Justification

- **Fully Sorted:** Insertion Sort is the best because it takes advantage of the fact that the data is already sorted.
- **Partially Sorted:** Quick Sort is the best based on the experimental results, because it achieved the lowest execution time.

## Explaining the Behavior of Quick Sort with Reverse-Sorted and Fully Sorted Data, and the Effect of the Pivot Element

Quick Sort performs efficiently with both reverse-sorted and fully sorted data when using a Random Pivot.

The Pivot divides the data into two parts. A good Pivot creates balanced partitions, resulting in faster execution, while a poor Pivot creates unbalanced partitions and increases execution time. Using a Random Pivot helps reduce the chance of poor performance.
