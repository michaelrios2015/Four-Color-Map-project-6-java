# project-6-java

This is the assignment the project was based on

Something did not work the way it was supposed to I cannot remember at the moment but I used pointers to construct the whole thing which I was pretty happy with

You are to write a Java program that constructs a map of the United States excluding Hawaii and Alaska. According to the theory of Four Colors, you only need to use four colors to mark adjacent states with different colors. Use the breadth first traversal and depth first traversal to visit each state, displaying its name along with its color assigned. 

INPUT:

A subset of input data is shown below:
1. There will be exactly one line of data for each state on the map. The number of states N on the map is determined when the end of the file is reached.
2. The ith line contains the numbers representing the states that share a border with state i.
For example, a portion of the map can be represented by the following input file:


1: 2 5 
2: 1 3 4 5
3: 2 4 8
4: 2 3 5 7 8
5: 1 2 4 6 7 9
6: 5 9 12 13
7: 4 5 8 9 10 11
8: 3 4 7 10 11
9: 5 6 7 10 13 14
10: 7 8 9 11 14 15 16
11: 7 8 10 16 17
12: 6 13 18
13: 6 9 12 14 18 19
14: 9 10 13 15 19 20
15: 10 14 16 20
16: 10 11 15 17 20 21
17: 11 16 21 22
18: 12 13 19 23
19: 13 14 18 20 23 24
20: 14 15 16 19 21 24 25
21: 16 17 20 22 26 27
22: 17 21 27
23: 18 19 24 37
24: 19 20 23 25 36
25: 20 24 26 33 34 35 36
26: 20 21 25 27 28 29 32 33 
27: 21 22 26 28
28: 26 27 29 30
29: 26 28 30 31 32
30: 28 29
31: 29 32
32: 26 29 31 33
33: 25 26 32 34 48
34: 25 33 35 38 48
35: 25 34 36 37 38
36: 24 25 35 37
37: 23 35 36
38: 34 35 39 45 47 48
39: 38 40 43 44 45
40: 39 41 43 
41: 40 42 43
42: 41
43: 39 40 41 44
44: 43 45
45: 39 43 44
46: 38 39 47
47: 38 45 48
48: 33 34 38 47 

1 2 5
2 3 4 5
5 1 2 4 6 7 9
3 2 4 8

4 2 3 5 7 8
6 1 5 9
7 4 5 8 9 10 11
9 5 6 7 10
8 3 4 7 10 11
10 7 8 9 11
11 7 8 10


where 
	1	Washington
	2	Oregon
	3	California
	4	Nevada
	5	Idaho
	6	Montana
	7	Utah
	8	Arizona
	9	Wyoming
	10	Colorado
	11	New Mexico

OUTPUT:

A sequence of states according to the order they were visited, along with their color assignments and level numbers.

