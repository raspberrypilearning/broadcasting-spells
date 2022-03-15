
--- question ---

---
legend: 3 में से दूसरा प्रश्न
---

आपके प्रोजेक्ट में, एक बटन पर क्लिक करने से एक संदेश प्रसारित होता है। Grow बटन पर क्लिक करने पर कौन से स्प्राइट या स्प्राइट्स का आकार बदल जाएगा?

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

- ( ) जो भी स्प्राइट पहले संदेश प्राप्त करता है

 --- feedback ---

 नहीं, संदेश सभी स्प्राइट्स द्वारा देखे जाते हैं। एक से अधिक स्प्राइट एक ही संदेश का उत्तर दे सकते हैं।

 --- /feedback ---

- (x) दोनों Ripley और Robot स्प्राइट्स

 --- feedback ---

 हां, जब कोई संदेश `broadcast`{:class="block3events"} होता है, तो सभी स्प्राइट्स जिनमें `when I receive`{:class="block3events"} ब्लॉक है वह संदेश पर प्रतिक्रिया करेंगे।

 --- /feedback ---

- ( ) स्प्राइट्स में से कोई भी नहीं

 --- feedback ---

 एक और नज़र डालें। कोड सही ढंग से एक संदेश `broadcast`{:class="block3events"} करता है।

 --- /feedback ---

--- /choices ---

--- /question ---
