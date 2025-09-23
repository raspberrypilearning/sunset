## Where are we?

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Where are we?
</div>
<div>

![ADD](images/ADD.png){:width="300px"}

</div>
</div>

<html>
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/-g3lJIF2qHs?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
</iframe>
</div><br>
</html>



--- task ---
Add `when key pressed` event and choose down arrow from the menu
```blocks3
+when [down arrow v] key pressed
```
--- /task ---

--- task ---
Add a `say` block from the `Looks` blocks menu. Choose costume name and type 1 second.
```blocks3
when [down arrow v] key pressed
+say (costume [name v]) for (1) seconds
```
--- /task ---



--- task ---
Test your project - it should say the name of the city costume when you press up arrow
--- /task ---
