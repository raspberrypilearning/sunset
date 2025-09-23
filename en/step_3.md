## Size of the sun

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Change the size of the sun in the sky
</div>
<div>

![ADD](images/ADD.png){:width="300px"}

</div>
</div>

<html>
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/wZU1QGnKG8c?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div><br>
</html>

--- task ---
From the looks menu add the set size to block to your blocks
```blocks3
when green flag clicked
forever
 go to x: (mouse x) y: ((200) - ([abs v] of (mouse x)))
 +set size to () %
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