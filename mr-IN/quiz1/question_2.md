
--- question ---

---
legend: प्रश्न 3 पैकी 2
---

In your project, clicking on a button broadcasts a message. grow बटनावर क्लिक केल्यावर कोणता स्प्राईट किंवा कोणते स्प्राईट्स साईज बदलतील?

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

- ( ) कोणत्या स्प्राईटला पहिल्यांदा मेसेज प्राप्त होतो

 --- feedback ---

 नाही, मेसेज सर्व स्प्राईटकडून बघितले जातात. एक पेक्षा जास्त स्प्राईट सारख्याच मेसेजचा प्रतिसाद देऊ शकतात.

 --- /feedback ---

- (x) Ripley आणि Robot दोन्ही स्प्राईट्स

 --- feedback ---

 हो, जेव्हा मेसेज `broadcast`{:class="block3events"}, सर्व स्प्राईट्स ज्यांना `when I receive`{:class="block3events"} ब्लॉक असतात ते मेसेजला उत्तर देतील.

 --- /feedback ---

- ( ) स्प्राइट्सपैकी एकही नाही

 --- feedback ---

 आणखी एक लूक. कोड योग्यपणे मेसेज `broadcast`{:class="block3events"} करतो.

 --- /feedback ---

--- /choices ---

--- /question ---
