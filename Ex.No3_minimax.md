# Ex.No: 3  Implementation of Minimax Search                                                                            
## REGISTER NUMBER : 212223060029
### AIM: 
Write a mini-max search algorithm to find the optimal value of MAX Player from the given graph.
### Algorithm:
1. Start the program
2. import the math package
3. Specify the score value of leaf nodes and find the depth of binary tree from leaf nodes.
4. Define the minimax function
5. If maximum depth is reached then get the score value of leaf node.
6. Max player find the maximum value by calling the minmax function recursively.
7. Min player find the minimum value by calling the minmax function recursively.
8. Call the minimax function  and print the optimum value of Max player.
9. Stop the program. 

### Program:
```
else:
    return min(minimax(curDepth + 1, nodeIndex * 2, True, scores, targetDepth),
               minimax(curDepth + 1, nodeIndex * 2 + 1,
                 True, scores, targetDepth))
```
### Output:
![374134494-3b3cb69b-0f36-49ba-b209-5ddde00bc742](https://github.com/user-attachments/assets/89562b09-375f-4e56-a35a-bd9dc31d38a9)

### Result:
Thus the optimum value of max player was found using minimax search.
