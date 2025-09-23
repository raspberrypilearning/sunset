## Make it grow

--- task ---
From the looks menu add the set size to block to your blocks
```blocks3
when green flag clicked
forever
 go to x: (mouse x) y: ((200) - ([abs v] of (mouse x)))
+ set size to () %
```
--- /task ---


--- task ---
In the first fiedl type in 50. In the second field add and abs of block.

```blocks3
when green flag clicked
forever
 go to x: (mouse x) y: ((200) - ([abs v] of (mouse x)))
 set size to ((50) + ([abs v] of ())) %
```
--- /task ---


--- task ---
Add a divide by operator to the abs of, and add a mouse x and type the number 4 into to the empty fields. 
```blocks3
when green flag clicked
forever
 go to x: (mouse x) y: ((200) - ([abs v] of (mouse x)))
 set size to ((50) + (([abs v] of (mouse x)) / (4))) %
```
--- /task ---

--- task ---
Test you code and play around with diffenrt numbers to divide the mouse x by to how you want to change the size
--- /task ---