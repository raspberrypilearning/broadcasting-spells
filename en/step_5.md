## Toad transformation

Now for another spell. This times you're going to cast a 'toad' spell by broadcasting a 'toad' message and the Wizard will turn into a toad!

--- task ---

Add a script to the **toad** button sprite to broadcast the 'toad' message:

```blocks3 
when this sprite clicked
broadcast [toad v]
```
--- /task ---

--- task ---
Select the Wizard sprite and click on the 'Costumes' tab. 

Add the 'Wizard-toad-a' costume.

--- /task ---

--- task ---
Switch to the normal Wizard costume when the green flag is clicked:

```blocks3
when flag clicked
set size to [100] %
+ switch costume to [wizard-a v]
```

--- /task ---

--- task ---
Add a script to the **Wizard** sprite to turn into a toad:

```blocks3  
when I receive [toad v]
switch costume to [Wizard-toad-a v]
```

--- /task ---

--- task ---

Add the 'croak' sound to the **Wand** sprite.

Rename the sound to 'toad'.
--- /task ---

--- task ---
Add a script to the **Wand** sprite to play the 'toad' sound when the toad spell is cast:

```blocks3  
when I receive [toad v]
play sound [toad v] until done
```
--- /task ---

--- task ---
**Test:** Test that you can turn the Wizard into a toad, with a sound effect, when you click the 'toad' button. 
--- /task ---

The oppsite of a 'toad' spell is an 'untoad' spell.

--- task ---
Add a script to the **untoad** button sprite to broadcast the 'untoad' message.

```blocks3 
when this sprite clicked
broadcast [untoad v]
```
--- /task ---


--- save ---