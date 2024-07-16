# Step By Step Directions From a Binary Tree Node to Another

LeetCode Q # 2096.

You are given the root of a binary tree with n nodes. Each node is uniquely assigned a value from 1 to n. You are also given an integer startValue representing the value of the start node s, and a different integer destValue representing the value of the destination node t.

Find the shortest path starting from node s and ending at node t. Generate step-by-step directions of such path as a string consisting of only the uppercase letters 'L', 'R', and 'U'. Each letter indicates a specific direction:

- 'L' means to go from a node to its left child node.</br>
- 'R' means to go from a node to its right child node.</br>
- 'U' means to go from a node to its parent node.</br>

Return the step-by-step directions of the shortest path from node s to node t.

Example 1:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/70e34036-b0fe-4bd8-9911-d01b159257dd)

</div>

> Input: root = [5,1,2,3,null,6,4], startValue = 3, destValue = 6</br>
> Output: "UURL"</br>
> Explanation: The shortest path is: 3 → 1 → 5 → 2 → 6.

Example 2:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/02f90e92-8533-4b8a-9469-47ffba3e91d7)

</div>

> Input: root = [2,1], startValue = 2, destValue = 1</br>
> Output: "L"</br>
> Explanation: The shortest path is: 2 → 1.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/fb9b12d3-08c2-49e9-b4f1-7aafbde724e3)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
