# closest-pair-of-points

Generate a random pair of 100 values. Apply the closest pair algorithm to find the closest pair
(distance). A C++ or python from scratch implementation with neat documentation is expected.


1) We sort all points according to x coordinates.

2) Divide all points in two halves.

3) Recursively find the smallest distances in both subarrays.

4) Take the minimum of two smallest distances. Let the minimum be d.

5) Create an array strip[] that stores all points which are at most d distance away from the middle line dividing the two sets.

6) Find the smallest distance in strip[].

7) Return the minimum of d and the smallest distance calculated in above step 6.
