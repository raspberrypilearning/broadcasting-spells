
--- question ---
---
legend: Ερώτηση 2 από 3
---

Στο έργο σου, κάνοντας κλικ σε ένα κουμπί μεταδίδεται ένα μήνυμα. Ποιο αντικείμενο ή αντικείμενα θα άλλαζαν μέγεθος όταν κάνεις κλικ στο κουμπί αύξησης;

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (αύξηση v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [αύξηση v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [αύξηση v]
change size by [10]
```

--- choices ---

- ( ) Όποιο αντικείμενο λάβει πρώτο το μήνυμα

 --- feedback ---

 Όχι, τα μηνύματα λαμβάνονται από όλα τα αντικείμενα. Περισσότερα από ένα αντικείμενα μπορούν να ανταποκριθούν στο ίδιο μήνυμα.

 --- /feedback ---

- (x) Και το αντικείμενο Ripley και το αντικείμενο Robot

 --- feedback ---

 Ναι, όταν ένα μήνυμα `μεταδίδεται`{:class="block3events"}, όλα τα αντικείμενα που έχουν μπλοκ `όταν λάβω`{:class="block3events"} θα αντιδράσουν στο μήνυμα.

 --- /feedback ---

- ( ) Κανένα από τα αντικείμενα

 --- feedback ---

 Ρίξε μια άλλη ματιά. Ο κώδικας `μεταδίδει`{:class="block3events"} σωστά ένα μήνυμα.

 --- /feedback ---

--- /choices ---

--- /question ---
