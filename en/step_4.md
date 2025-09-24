## Change the colour

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Make the sky change colour
</div>
<div>

![ADD](images/colour.gif){:width="300px"}

</div>
</div>

<html>
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/HSZQlOlowyg?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div><br>
</html>

### Switch backdrop
--- task ---
Select the backdrop from the stage pane. 

![ALT TEXT](images/backdrop.png)
--- /task ---

--- task ---
Drag a `when flag clicked`{:class="block3events"} block into the Code area.
```blocks3
+ when green flag clicked
```
--- /task ---

--- task ---
From the `Looks`{:class="block3looks"} block menu drag a `switch backdrop`{:class="block3looks"} block.

```blocks3
when green flag clicked
+switch backdrop to (sunset v)
```


Choose **sunset** from the dropdown menu.

![ALT TEXT](images/menu.gif)
--- /task ---

### Set colour

--- task ---
Add a `set color effect`{:class="block3looks"} block from the `Looks`{:class="block3looks"} menu.

Then add a `divide`{:class="block3operators"} block. 

```blocks3
when green flag clicked
switch backdrop to (sunset v)
forever
+ set [color v] effect to (() / ())
end
```
--- /task ---

--- task ---


Drag a `mouse x`{:class="block3sensing"} block into the first field.

Type **4** to the second. 

```blocks3
when green flag clicked
switch backdrop to (sunset v)
forever
+ set [color v] effect to ((mouse x) / (4))
end
```
--- /task ---


--- task ---
**Test:** Check that the background changes. You can experiment by changing the number **4** until you find a colour range that you like.
--- /task ---
