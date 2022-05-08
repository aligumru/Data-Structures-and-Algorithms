# Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
* Root => 7
* 5<7 ------------------------> [5, 7, 1, 8, 3, 6, 0, 9, 4, 2]
* 1<7 , 1<5 ------------------> [1, 5, 7, 8, 3, 6, 0, 9, 4, 2]
* 8>7 ------------------------> [1, 5, 7, 8, 3, 6, 0, 9, 4, 2]
* 3<7 , 3<5 , 3>1 ------------> [1, 3, 5, 7, 8, 6, 0, 9, 4, 2]
* 6<7 , 6>5 ------------------> [1, 3, 5, 6, 7, 8, 0, 9, 4, 2]
* 0<7 , 0<5 , 0<1 ------------> [0, 1, 3, 5, 6, 7, 8, 9, 4, 2]
* 9>7 , 9>8 ------------------> [0, 1, 3, 5, 6, 7, 8, 9, 4, 2]
* 4<7 , 4<5 , 4<6 , 4>3 -----> [0, 1, 3, 4, 5, 6, 7, 8, 9, 2]
* 2<7 , 2<5 , 2>1 , 2<3 -----> [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]


---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;--->Root\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9\
&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4