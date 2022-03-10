
--- question ---
---
legend: Question 2 sur 3
---

Dans ton projet, cliquer sur un bouton envoyer à tous un message. Quel sprite ou sprites changeraient de taille lorsque le bouton d'agrandissement est cliqué ?

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (grandir v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [grandir v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [grandir v]
change size by [10]
```

--- choices ---

- ( ) Quel que soit le sprite qui reçoit le message en premier

 --- feedback ---

 Non, les messages sont vus par tous les sprites. Plusieurs sprites peuvent répondre au même message.

 --- /feedback ---

- (x) Les sprites Ripley et Robot

 --- feedback ---

 Oui, lorsqu'un message est `envoyé à tous`{:class="block3events"}, tous les sprites qui ont un bloc `quand je reçois`{:class="block3events"} réagiront au message.

 --- /feedback ---

- ( ) Aucun des sprites

 --- feedback ---

 Jette un autre coup d'œil. Le code `envoie à tous`{:class="block3events"} un message correctement.

 --- /feedback ---

--- /choices ---

--- /question ---
