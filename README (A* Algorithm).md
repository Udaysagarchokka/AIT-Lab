Algorithm: 
Step 1: start
Step 2: Place the starting node into open and find its f(n) [start node] value.
Step 3: Remove the node from OPEN, having the smallest f(n) value, if it is x goal node, then stop and return to success.
Step 4: Else remove the node from OPEN, and find all its successors.
Step 5: Find the f(n) value of all the successors, Place them into OPEN and place the removed node into close
Step 6: Go to step 2.
Step 7: Exit
