## Move the sun

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Move the sun accross the sky with your mouse.
</div>
<div>

![ADD](images/move-sun-step.png){:width="300px"}

</div>
</div>

<html>
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/wZU1QGnKG8c?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div><br>
</html>


--- task ---
Open the starter project ADD LINK rpf.io/sunset-go
--- /task ---


--- task ---
Select the Sun sprite ![ALT TEXT](images/1-2-ol.png)
--- /task ---


--- task ---
Open the `Events`{:class="block3events"} menu and drag the `When flag clicked`{:class="block3events"} block to the Code area.

```blocks3
+when green flag clicked
```
--- /task ---

--- task ---
From the `Control`{:class="block3control"} menu drag a `forever`{:class="block3control"} block under the `when this sprite clicked`{:class="block3events"} block. 

```blocks3
when green flag clicked
+forever 
```

The blocks will snap together.
--- /task ---

--- task ---
From the `Motion`{:class="block3motion"} menu drag an `go to x: y:`{:class="block3motion"} block inside the `forever`{:class="block3control"} block. 

```blocks3
when green flag clicked
forever 
+go to x: () y: ()
```
--- /task ---



--- task ---
The `go to x: y:`{:class="block3motion"} block has two empty fields. In the first drag in a mouse x. In the second drag in a divde operator

![ALT TEXT](images/step1-1.gif)
--- /task ---



--- task ---
In the y BOX?? input a minus operator, and add 200 into the first box
--- /task ---

![ALT TEXT](images/1-5-ol.png)

--- task ---
drag in a abs of for the second box, and use the mouse x. This moves the mouse in an arc accross the sky.
--- /task ---

![ALT TEXT](images/1-7-nol.png)


--- task ---
test your code again - the sun should start low, and then rise and fall in a arc shape.
--- /task ---


Test the code by pressing the green flag - the sun should follow your mouse movment from side to side