
--- question ---

---
legend: Питання 2 з 3
---

У твоєму проєкті натискання на кнопку передає повідомлення. Який(-і) спрайт(-и) змінять розмір, коли ти натиснеш кнопку «Збільшити»?

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

- ( ) Той спрайт, що першим отримає повідомлення

 --- feedback ---

 Ні, всі спрайти бачать повідомлення. На одне й те ж повідомлення можуть зреагувати декілька спрайтів.

 --- /feedback ---

- (x) Обидва спрайти — Ripley та Robot

 --- feedback ---

 Так, коли повідомлення передається за допомогою `оповіщення`{:class="block3events"}, усі спрайти, що мають блок `коли я отримую`{:class="block3events"}, відреагують на це повідомлення.

 --- /feedback ---

- ( ) Жоден зі спрайтів

 --- feedback ---

 Спробуй ще раз. Код правильно передає повідомлення за допомогою `оповіщення`{:class="block3events"}.

 --- /feedback ---

--- /choices ---

--- /question ---
