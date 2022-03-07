## ಪುನರ್ಮನನ

ಭೇಷ್, ಕಥೆಗಳಲ್ಲಿನ ಆಲೋಚನೆಗಳನ್ನು ಆಧರಿಸಿ ನೀವು ಒಂದು ಆಪ್‌ ರಚಿಸಿದ್ದೀರಿ!

ನೀವು `Events`{:class="block3events"}, `Control`{:class="block3control"}, `Motion`{:class="block3motion"}, `Looks`{:class="block3looks"}, ಮತ್ತು `Sound`{:class="block3sound"} ಬ್ಲಾಕ್‌ಗಳನ್ನು ಉಪಯೋಗಿಸಿದ್ದೀರಿ!

ಈಗ ಪುನರ್ಮನನ ಮಾಡುವ ಸಮಯ — ಪುನರ್ಮನನ ಕಲಿಕೆಯ ಒಂದು ಮಹತ್ವದ ಭಾಗ, ಏಕೆಂದರೆ ಅದು ನಿಮ್ಮ ಮೆದುಳಿನಲ್ಲಿ ಹೊಸ ಸಂಪರ್ಕಗಳನ್ನು ಮಾಡಲು ಸಹಾಯ ಮಾಡುತ್ತದೆ.

ನೀವು ಕಲಿತಿದ್ದನ್ನು ಪುನರ್ಮನನ ಮಾಡಲು ಈ ಕೆಳಗಿನ ಮೂರು ಪ್ರಶ್ನೆಗಳಿಗೆ ಉತ್ತರಿಸಿ.

ಪ್ರತಿಯೊಂದು ಪ್ರಶ್ನೆಯ ನಂತರ, ಸಬ್ಮಿಟ್‌ ಒತ್ತಿ. ಸರಿಯಾದ ಉತ್ತರದ ಕಡೆಗೆ ನಿಮಗೆ ಮಾರ್ಗದರ್ಶನ ನೀಡಲಾಗುತ್ತದೆ. ಈ ಚಟುವಟಿಕೆಯನ್ನು ನೀವು ಎಷ್ಟು ಸಲ ಬೇಕಾದರೂ ಮಾಡಬಹುದು.

ಆನಂದಿಸಿ!

--- question ---

---
legend: ಪ್ರಶ್ನೆ 1 ರಲ್ಲಿ 3
---

ಬಟನ್‌ ಕ್ಲಿಕ್‌ ಮಾಡಿದಾಗ ಸಂದೇಶವನ್ನು `broadcast`{:class="block3events"} ಮಾಡಲು ನೀವು ಬರಹ ಬರೆದಿದ್ದೀರಿ.

![](images/button-icon.png)

```blocks3
when this sprite clicked
broadcast (invisible v)
```

ಬಟನ್‌ನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ಯಾವ ಬರಹ ಸ್ಪ್ರೈಟ್‌ನ್ನು ಮರೆಮಾಡುತ್ತದೆ?

--- choices ---

- ( )

```blocks3
when I receive [message1 v]
hide
```

 --- feedback ---

 ಇಲ್ಲ, ಇದು Scratch ನಲ್ಲಿ ಪೂರ್ವನಿಯೋಜಿತ ಸಂದೇಶ, ಆದರೆ ಇದು ಕೋಡ್‌ನಿಂದ ಕಳುಹಿಸಲಾದ ಸಂದೇಶವಲ್ಲ.

 --- /feedback ---

- ( )

```blocks3
when I receive [hide v]
hide
```

 --- feedback ---

 ಇಲ್ಲ, ನೀವು ಸ್ವೀಕರಿಸಬೇಕಾದ ಸಂದೇಶವನ್ನು 'hide' ಎಂದು ಕರೆಯುವುದಿಲ್ಲ.

 --- /feedback ---

- (x)

```blocks3
when I receive [invisible v]
hide
```

 --- feedback ---

ಹೌದು, ಅದು ಸರಿಯಾಗಿದೆ. `when I receive`{:class="block3events"} ಬ್ಲಾಕ್‌ `broadcast`{:class="block3events"} ಬ್ಲಾಕ್‌ನಂತೆ ಅದೇ ಸಂದೇಶದ ಹೆಸರನ್ನು ಉಪಯೋಗಿಸಬೇಕು.

 --- /feedback ---

- ( )

```blocks3
when I receive [invisable v]
hide
```

 --- feedback ---

 ಹಾಗೆನಿಲ್ಲ. ಸಂದೇಶದ ಹೆಸರುಗಳು ಹೊಂದಿಕೆಯಾಗಲು Scratch ಗೆ ನಿಮ್ಮ ಸ್ಪೆಲ್ಲಿಂಗ್‌ಗಳು ಅತ್ಯಂತ ನಿಖರವಾಗಿರಬೇಕು. ಎಚ್ಚರಿಕೆಯಿಂದ ಪರಿಶೀಲಿಸಿ.

 --- /feedback ---

--- /choices ---

--- /question ---
