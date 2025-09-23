## Light it


<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Light up the city
</div>
<div>

![ADD](images/ADD.png){:width="300px"}

</div>
</div>

<html>
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/1JV6m_1x9CE?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div><br>
</html>


--- task ---
Select the city sprite
--- /task ---

--- task ---
Add a green flag block to the code area and drag a forever block under. 

```blocks3
+when green flag clicked
 +forever
```
--- /task ---

--- task ---
Add an if then else block inside the forever. Add mouse x and type in 230. 

```blocks3
when green flag clicked
 forever
  +if <(mouse x) > (230)> then
  else
  end
end
```
--- /task ---

--- task ---
Add the set effect block and selcet bringness from the menu. Type 100 to the field. Add another set effect block and choose color fromt the menu. Type 255 to the field.

Add a clear graphics effect after else

```blocks3
when green flag clicked
 forever
  if <(mouse x) > (230)> then
   +set [brightness v] effect to (100)
   +set [color v] effect to (255)
  else
   +clear graphic effects
  end
end
```
--- /task ---

--- task ---
Test code and change the brightness and colour affect to make your city light up at night
--- /task ---

