## The shrinking spell

Now you will get the Wizard to shrink when you click on the shrink button.

--- task ---

Click on the **shrink** sprite in the Sprite list below the stage. 

Add a `when this sprite clicked`{:class="block3events"} block:

![](images/shrink-icon.png)

```blocks3
when this sprite clicked
```

--- /task ---

When you click on the 'shrink' button you want the Wizard sprite to shrink. 

The **shrink** sprite needs to `broadcast`{:class="block3events"} a `message`{:class="block3events"} so that the Wizard knows that the shrink spell has been cast.

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

Now when you click on the button, Scratch will broadcast the 'shrink' message. But nothing will happen until you get the Wizard to do something when it recieves the message.

--- task ---

Add code to the Wizard sprite to shrink when it recieves a 'shrink' message:

![](images/wizard-icon.png)

```blocks3
when I receive [shrink v]
change size by [-10] // negative numbers decrease the size
```
--- /task ---

--- task ---

**Test:** Click on the shrink button to shrink the Wizard. Do this as many times as you like.

--- /task ---

--- task ---

Add a script to set the Wizard to normal size when the green flag is clicked:

![](images/wizard-icon.png)

```blocks3
when flag clicked
set size to [100] %
```
--- /task ---

Messages are broadcast to all sprites. The wand can play a sound when it receives the 'shrink' message.

--- task ---

Click on the Wand sprite and then the 'Sounds' tab.

Add the 'Slide whistle' sound.

Rename the sound to 'shrink' so it is easy to find.

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

**Test:** Click on the green flag to run your project and set the Wizard to 100% size. Click on the 'shrink' button to hear the sound and see the Wizard shrink.

--- /task ---

--- save ---