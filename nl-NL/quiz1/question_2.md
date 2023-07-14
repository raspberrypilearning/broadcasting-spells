
--- question ---

---
legend: Vraag 2 van 3
---

In jouw project, klik je op een knop om een bericht te verzenden. Welke sprite of sprites zouden van grootte veranderen als op de groei-knop wordt geklikt?

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

- ( ) Welke sprite het bericht het eerst ontvangt

 --- feedback ---

 Nee, berichten worden door alle sprites gezien. Meer dan één sprite kan op hetzelfde bericht reageren.

 --- /feedback ---

- (x) Zowel de Ripley- als de Robot-sprite

 --- feedback ---

 Ja, wanneer een bericht `verzonden`{:class="block3events"} is, zullen alle sprites die een `wanneer ik een signaal ontvang`{:class="block3events"}-blok op het bericht reageren.

 --- /feedback ---

- ( ) Geen van de sprites

 --- feedback ---

 Kijk nog eens. De code `zendt` {:class="block3events"} een correct bericht uit.

 --- /feedback ---

--- /choices ---

--- /question ---
