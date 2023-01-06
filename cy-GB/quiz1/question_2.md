
--- question ---

---
legend: Cwestiwn 2 o 3
---

Yn dy brosiect di, roedd clicio ar fotwm yn darlledu neges. Pa gorlun neu gorluniau fyddai'n newid maint ar ôl i'r botwm tyfu gael ei glicio?

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

- ( ) Pa bynnag gorlun sy'n derbyn y neges gyntaf

 --- feedback ---

 Na, mae negeseuon yn cael eu gweld gan bob corlun. Gall mwy nag un corlun ymateb i'r un neges.

 --- /feedback ---

- (x) Corluniau Ripley a Robot

 --- feedback ---

 Cywir, pan gaiff neges ei `darlledu`{:class="block3events"}, bydd pob corlun sydd â bloc `pan rwy'n derbyn`{:class="block3events"} yn ymateb i'r neges.

 --- /feedback ---

- ( ) Y naill na'r llall o'r corluniaid

 --- feedback ---

 Cymer olwg arall. Mae'r cod yn `darlledu`{:class="block3events"} neges.

 --- /feedback ---

--- /choices ---

--- /question ---
