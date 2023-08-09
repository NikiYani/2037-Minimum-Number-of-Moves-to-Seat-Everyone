# 2037. Minimum Number of Moves to Seat Everyone

There are n seats and n students in a room. You are given an array seats of length n, </br>
where seats[i] is the position of the ith seat. You are also given the array students of length n, </br>
where students[j] is the position of the jth student. </br>

You may perform the following move any number of times: </br>

Increase or decrease the position of the ith student by 1 (i.e., moving the ith student from position x to x + 1 or x - 1) </br>
Return the minimum number of moves required to move each student to a seat such that no two students are in the same seat. </br>

Note that there may be multiple seats or students in the same position at the beginning. </br>

## Example 1:

Input: seats = [3,1,5], students = [2,7,4] </br>
Output: 4 </br>
Explanation: The students are moved as follows: </br>
- The first student is moved from from position 2 to position 1 using 1 move. </br>
- The second student is moved from from position 7 to position 5 using 2 moves. </br>
- The third student is moved from from position 4 to position 3 using 1 move. </br>
In total, 1 + 2 + 1 = 4 moves were used. </br>

## Example 2:

Input: seats = [4,1,5,9], students = [1,3,2,6] </br>
Output: 7 </br>
Explanation: The students are moved as follows: </br>
- The first student is not moved. </br>
- The second student is moved from from position 3 to position 4 using 1 move. </br>
- The third student is moved from from position 2 to position 5 using 3 moves. </br>
- The fourth student is moved from from position 6 to position 9 using 3 moves. </br>
In total, 0 + 1 + 3 + 3 = 7 moves were used. </br>

## Example 3:

Input: seats = [2,2,6,6], students = [1,3,2,6] </br>
Output: 4 </br>
Explanation: Note that there are two seats at position 2 and two seats at position 6. </br>
The students are moved as follows: </br>
- The first student is moved from from position 1 to position 2 using 1 move. </br>
- The second student is moved from from position 3 to position 6 using 3 moves. </br>
- The third student is not moved. </br> 
- The fourth student is not moved. </br>
In total, 1 + 3 + 0 + 0 = 4 moves were used. </br>

## Constraints:

n == seats.length == students.length </br>
1 <= n <= 100 </br>
1 <= seats[i], students[j] <= 100 </br>
