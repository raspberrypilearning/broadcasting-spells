## The shrinking spell

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Now you will get the Wizard to shrink when you click on the shrink button.
</div>
<div>
![](images/shrinking-wizard.png){:width="300px"}
</div>
</div>

--- task ---

Click on the **shrink** sprite in the Sprite list below the stage. 

Add a `when this sprite clicked`{:class="block3events"} block:

![](images/shrink-icon.png)

```blocks3
when this sprite clicked
```

--- /task ---

When you click on the shrink button you want the **Wizard** sprite to shrink. 

The **shrink** sprite needs to `broadcast`{:class="block3events"} a `message`{:class="block3events"} so that the **Wizard** sprite knows that the shrink spell has been cast.

--- task ---

Add a `broadcast`{:class="block3events"} block:

![](images/shrink-icon.png)

```blocks3
when this sprite clicked
+ broadcast (message v)
```

--- /task ---

--- task ---

Click on 'message' and choose 'New message'. Name the new message 'shrink'.

![New message dialog with shrink entered.](images/new-message.png)

Your code should look like this:

![](images/shrink-icon.png)

```blocks3
when this sprite clicked
broadcast (shrink v)
```

--- /task ---

Now when you click on the button, Scratch will broadcast the 'shrink' message. But nothing will happen until you get the **Wizard** sprite to do something when it recieves the message.

--- task ---

Add code to the **Wizard** sprite to shrink when it recieves a 'shrink' message:

![](images/wizard-icon.png)

```blocks3
when I receive [shrink v]
change size by [-10] // negative numbers decrease the size
```
--- /task ---

--- task ---

**Test:** Click on the shrink button to shrink the Wizard. Do this as many times as you like.

**Debug:** If your Wizard grows instead of shrinks, add a minus `-` before the number `10` to make a negative number `-10`.

--- /task ---

--- task ---

Add a script to set the **Wizard** sprite to normal size `when the green flag`{:class="block3events"} is clicked:

![](images/wizard-icon.png)

```blocks3
when flag clicked
set size to [100] %
```
--- /task ---

Messages are `broadcast`{:class="block3events"} to all sprites. When the **Wand** `receives`{:class="block3events"} the 'shrink' message it should `play a sound `{:class="block3sound"}.

--- task ---

Click on the **Wand** sprite and then the **Sounds** tab.

Add the **Slide whistle** sound.

Rename the sound to `shrink` so it is easy to find.

![](images/wand-icon.png)

![The Sounds tab with added slide whistle sound renamed to shrink in the Sound property.](images/slide-whistle.png)

--- /task ---

--- task ---

Add a script to play the sound:

![](images/wand-icon.png)

```blocks3
when I receive [shrink v]
play sound [shrink v] until done

```
--- /task ---

--- task ---

**Test:** Click on the green flag to run your project. Click on the 'shrink' button to hear the sound and see the Wizard shrink.

--- /task ---

The **shrink** button `broadcast`{:class="block3events"} a `shrink`{:class="block3events"} message and both the **Wizard** and the **Wand** sprite `received`{:class="block3events"} the message and responded.

--- save ---