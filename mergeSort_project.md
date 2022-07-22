# Patika.dev Data Structures and Algorithms Projects
Data Structures and Algorithms Project-2

- Merge Sort

[16,21,11,8,12,22] 

1- Write the stages of the above given sequence according to the sort type.

| 16  | 21  | 11  | 8  | 12  | 22  |
| :-: | :-: | :-: | :-: | :-: | :-: |

Step1:    

[16,21,11,8,12,22]   

Step2:

[16,21,11]    [8,12,22]

Step3:

[16,21]-[11]--------[8,12,]-[22]

Step4:

[16]-[21]-[11]--------[8]-[12]-[22]

Step5:

[16,21]-[11]--------[8,12,]-[22]

Step6:

[11,16,21]--------[8,12,22]

Step7:

[8,11,12,16,21,22]

2- Write the Big-O notation.

- Big O Notation: O(nlogn)
