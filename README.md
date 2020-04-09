# m2003 Corona and Masks
## Problem Statement
There are N pharmacies that sell masks. The *i*-th pharmacy is located at X<sub>i</sub> on the number line and have A<sub>i</sub> masks initially. In each second, all pharmacies will sell 1 mask (if the pharmacy still have stock). Corona's home is located at position 0 and she can make up to two round trips to visit the pharmacies. Each round trip is defined as traveling from her home to a location on the number line in a single direction, and then return to home in the opposite direction. Corona can travel 1 unit per second. It takes no time for her to buy all the masks available at a pharmacy which she passes through (or arrives at).

How many masks can Corona possibly buy?

## Input
The first line contains an integer N.<br>
The second line contains N integers X<sub>1</sub>, X<sub>2</sub>,..., X<sub>N</sub>.<br>
X<sub>i</sub> ≠ 0 for all 1 ≤ i ≤ N and  X<sub>i</sub> < X<sub>i+1</sub> for all 1 ≤ i ≤ N.<br>
The third line contains N integers A<sub>1</sub>, A<sub>2</sub>,..., A<sub>N</sub>.
 
## Output
Output a single integer: the maximum possible number of masks Corona can buy.

## Sample Tests
**Input 1**
```
4
-2 -1 5 15
10 5 20 8
```
**Output 1**
```
23
```
**Input 2**
```
2
-100 100
1 1
```
**Output 2**
```
0
```

## Subtasks
For all cases: 1 ≤ A<sub>i</sub> ≤ 10<sup>6</sup><br>

\# | Points | Constraints
--- | --- | ---
1 | 10 | 1 ≤ N ≤ 100<br>1 ≤ X<sub>i</sub> ≤ 1000
2 | 20 | 1 ≤ N ≤ 4<br>-100 ≤ X<sub>i</sub> ≤ 100
3 | 25 | 1 ≤ N ≤ 100<br>-1000 ≤ X<sub>i</sub> ≤ 1000
4 | 45 | 1 ≤ N ≤ 100000<br>-10<sup>6</sup> ≤ X<sub>i</sub> ≤ 10<sup>6</sup>

Original version from [HKOI Online Judge](https://judge.hkoi.org/task/M2003)<br>
Source: Hong Kong Olympiad in Informatics Organizing Committee. This problem is under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) licence.
