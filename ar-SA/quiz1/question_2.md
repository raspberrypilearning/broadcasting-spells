
--- question ---

---
legend: السؤال 2 من 3
---

في مشروعك، يؤدي النقر فوق الزر إلى بث رسالة. ما هو الكائن أو الكائنات الّتي سيتغيّر حجمها عند النقر على زرّ التكبير؟

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (تكبير v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [تكبير v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [تكبير v]
change size by [10]
```

--- choices ---

- () الكائن الذي سيتلقى الرسالة اولاً

 --- feedback ---

 خطأ، الرسائل تُرى من قِبَل كلا الكائنَين. يمكن لأكثر من كائن أن يستقبل نفس الرسالة.

 --- /feedback ---

- (x) الكائنين كلاهما، Ripley وRobot

 --- feedback ---

 إجابة صحيحة! عندما تتمّ عمليّة `بثّ`{:class="block3events"} رسالة، كلّ الكائنات الّتي تملك المقطع البرمجيّ `عندما أتلقّى`{:class="block3events"} ستتفاعل مع الرسالة.

 --- /feedback ---

- () لن يتلقّى أيّ كائن الرسالة

 --- feedback ---

 حاول مجدّدًا. الكود البرمجيّ يؤدّي عمليّة `بثّ`{:class="block3events"} الرسالة بشكل سليم.

 --- /feedback ---

--- /choices ---

--- /question ---
