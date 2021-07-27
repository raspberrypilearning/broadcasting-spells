
--- question ---

---
legend: Question 2 of 3
---

In your project, clicking on a button broadcast a message. Which sprite or sprites would change size when the grow button is clicked?

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (grow v)
``` 

![](images/Ripley-icon.png)

```blocks3
when I receive [grow v]
change size by [10]
``` 

![](images/Robot-icon.png)

```blocks3
when I receive [grow v]
change size by [10]
``` 

--- choices ---

- ( ) Whichever sprite receives the message first.

 --- feedback ---

 No, messages are seen by all sprites. More than one sprite can respond to the same message.

 --- /feedback ---

- (x) Both the Ripley and Robot sprites.

 --- feedback ---

 Yes, when a message is `broadcast`{:class="block3events"}, all sprites that have a `when I receive`{:class="block3events"} block will react to the message.

 --- /feedback ---

- ( ) Neither of the sprites.

 --- feedback ---

 Have another look. The code does correctly `broadcast`{:class="block3events"} a message.

 --- /feedback ---

--- /choices ---

--- /question ---
