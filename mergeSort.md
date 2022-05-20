[16, 21, 11, 8, 12, 22]-> Merge Sort

1)Merge Sort Steps
[16, 21, 11, 8, 12, 22]

Seperate until an element left.
[16, 21, 11]    [8, 12, 22]
[16, 21]  [11]    [8, 12]  [22]
[16]  [21]  [11]    [8]  [12]  [22]

Merge until reach the same array size before seperation.
[16, 21]  [11]    [8, 12]  [22]
[11, 16, 21]    [8, 12, 22]
[8, 11, 12, 16, 21, 22]

2)Big-O Notation
O (n*(logn))