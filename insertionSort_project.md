# Patika.dev Data Structures and Algorithms Projects
Data Structures and Algorithms Project-1

- Insertion Sort

[22,27,16,2,18,6]</b>

1- Write the stages of the above given sequence according to the sort type.

| 22  | 27  | 16  | 2  | 18  | 6  |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 22  | 27  | 2  | 16  | 18  | 6  |
| 22  | 2  | 27  | 16  | 18  | 6  |
| 2  | 22  | 27  | 16  | 18  | 6  |
| 2  | 22  | 16  | 27  | 18  | 6  |
| 2  | 16  | 22  | 27  | 18  | 6  |
| 2  | 16  | 22  | 18  | 27  | 6  |
| 2  | 16  | 18  | 22  | 27  | 6  |
| 2  | 16  | 18  | 22  | 6  | 27  |
| 2  | 16  | 18  | 6  | 22  | 27  |
| 2  | 16  | 6  | 18  | 22  | 27  |
| 2  | 6  | 16  | 18  | 22  | 27  |

2- Write the Big-O notation.

- Big O Notation -> n*(n+1)/2 --> O(n^2)

3- Time Complexity: Average case: The number we are looking for is in the middle. Worst case: The number we are looking for is at the end. Best case: The number we are looking for is at the beginning of the series.

4- After the array is sorted, please write if the number 18 is the average case, worst case or best case.

- Average case. (18 is one of the two numbers in the middle of the array.)
