
--- question ---

---
legend: Domanda 2 di 3
---

Nel tuo progetto, facendo clic su un pulsante viene trasmesso un messaggio. Quale o quali sprite cambierebbero dimensione quando si fa clic sul pulsante di crescita?

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (cresci v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [cresci v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [cresci v]
change size by [10]
```

--- choices ---

- ( ) Qualunque sprite riceva per primo il messaggio

 --- feedback ---

 No, i messaggi vengono visti da tutti gli sprite. Più di uno sprite può rispondere allo stesso messaggio.

 --- /feedback ---

- (x) Sia gli sprite di Ripley che quelli di Robot

 --- feedback ---

 Sì, quando un messaggio viene `inviato a tutti`{:class="block3events"}, tutti gli sprite che hanno un `quando ricevo`{:class="block3events"} il blocco reagiranno al messaggio.

 --- /feedback ---

- ( ) Nessuno degli sprite

 --- feedback ---

 Dai un'altra occhiata. Il codice trasmette correttamente con `invia a tutti`{:class="block3events"} un messaggio.

 --- /feedback ---

--- /choices ---

--- /question ---
