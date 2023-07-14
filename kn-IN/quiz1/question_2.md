
--- question ---

---
legend: ಪ್ರಶ್ನೆ 2 ರಲ್ಲಿ 3
---

In your project, clicking on a button broadcasts a message. ಬೆಳೆ ಬಟನ್‌ನ್ನು ಕ್ಲಿಕ್‌ ಮಾಡಿದಾಗ ಯಾವ ಸ್ಪ್ರೈಟ್‌ ಅಥವಾ ಸ್ಪ್ರೈಟ್‌ಗಳು ಗಾತ್ರವನ್ನು ಬದಲಾಯಿಸುತ್ತವೆ?

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

- ( ) ಯಾವ ಸ್ಪ್ರೈಟ್‌ ಸಂದೇಶವನ್ನು ಮೊದಲು ಸ್ವೀಕರಿಸುತ್ತದೆಯೋ ಅದು

 --- feedback ---

 ಇಲ್ಲ, ಎಲ್ಲಾ ಸ್ಪ್ರೈಟ್‌ಗಳೂ ಸಂದೇಶವನ್ನು ನೋಡುತ್ತವೆ. ಒಂದಕ್ಕಿಂತ ಹೆಚ್ಚು ಸ್ಪ್ರೈಟ್‌ಗಳು ಅದೇ ಸಂದೇಶಕ್ಕೆ ಪ್ರತಿಕ್ರಿಯಿಸಬಹುದು.

 --- /feedback ---

- (x) Ripley ಮತ್ತು Robot ಎರಡೂ ಸ್ಪ್ರೈಟ್‌ಗಳು

 --- feedback ---

 ಹೌದು, ಸಂದೇಶವೊಂದು `broadcast`{:class="block3events"}ಆದಾಗ, `when I receive`{:class="block3events"} ಬ್ಲಾಕ್‌ ಹೊಂದಿರುವ ಎಲ್ಲಾ ಸ್ಪ್ರೈಟ್‌ಗಳು ಸಂದೇಶಕ್ಕೆ ಪ್ರತಿಕ್ರಿಯಿಸುತ್ತವೆ.

 --- /feedback ---

- ( ) ಎರಡೂ ಸ್ಪ್ರೈಟ್‌ಗಳೂ ಅಲ್ಲ

 --- feedback ---

 ಮತ್ತೊಮ್ಮೆ ನೋಡಿ. ಕೋಡ್‌ ಸರಿಯಾಗಿ ಸಂದೇಶವನ್ನು `broadcast`{:class="block3events"} ಮಾಡುತ್ತದೆ.

 --- /feedback ---

--- /choices ---

--- /question ---
