## Move the sun

ç
--- task ---
Open the starter project ADD LINK rpf.io/sunset-go
--- /task ---


--- task ---
Select the Sun sprite ![ALT TEXT](images/sun-sprite.png)
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
From the `Motion`{:class="block3motion"} menu drag an `go to x: y:`{:class="block3motion"} block inside the `Forever`{:class="block3control"} block. 

```blocks3
when green flag clicked
forever 
+go to x: () y: ()
```
The `go to x: y:`{:class="block3motion"} block has two empty fields. In the first drag in a `mouse x`{:class="block3motion"}. In the second drag in a `minus operator` {:class="block3operators"}

```blocks3
when green flag clicked
forever 
go to x: (mouse x) y: (()-())
```
--- /task ---

**Tip:** hover over just below the empty field to drop the blocks in

![ALT TEXT](images/step1-1.gif)

--- task ---
Test your code - clcik the green flag and move your mouse over the stage - the sun should move.
--- /task ---

--- task ---
In the `minus operator` {:class="block3operators"} type in 200 to the first field, and drag in an `abs of`{:class="block3operators"} in the second.

```blocks3
when green flag clicked
forever 
go to x: (mouse x) y: ((200)-(abs of()))
```
--- /task ---


--- task ---
Drag and drop a `mouse x`{:class="block3motion"} into the `abs of`{:class="block3operators"} block.
```blocks3
when green flag clicked
forever 
go to x: (mouse x) y: ((200)-(abs of(mouse x)))
```
--- /task ---

--- task ---
test your code again - the sun should start low, and then rise and fall in a arc shape.
--- /task ---
