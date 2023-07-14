
--- question ---

---
legend: 3లో 2వ ప్రశ్న
---

In your project, clicking on a button broadcasts a message. Grow బటన్‌ను క్లిక్ చేసినప్పుడు ఏ sprite లేదా spriteలు పరిమాణాన్ని మారుస్తాయి?

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

- ( ) ముందుగా మెసేజ్‌ని స్వీకరించిన ఏదైనా sprite

 --- feedback ---

 లేదు, సందేశాలు అన్ని sprite లచే చూడబడతాయి. ఒకే సందేశానికి ఒకటి కంటే ఎక్కువ sprite లు ప్రతిస్పందించగలవు.

 --- /feedback ---

- (x) Ripley మరియు Robot sprites రెండూ

 --- feedback ---

 అవును, ఒక సందేశం `broadcast`{:class="block3events"} అయినప్పుడు, `when I receive`{:class="block3events"} బ్లాక్‌ని కలిగి ఉన్న అన్ని sprite లు సందేశానికి ప్రతిస్పందిస్తాయి.

 --- /feedback ---

- ( ) sprite లు రెండూ కాదు

 --- feedback ---

 మరొకసారి చూడండి. కోడ్ సరిగ్గానే సందేశాన్ని `broadcast`{:class="block3events"} చేస్తుంది.

 --- /feedback ---

--- /choices ---

--- /question ---
