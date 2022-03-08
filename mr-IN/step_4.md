## grow स्पेल

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
**Fairy** स्प्राइटला सामान्य आकारात परत आणण्यासाठी किंवा एक भव्य परी बनवण्यासाठी तुम्हाला grow स्पेल देखील आवश्यक आहे!
</div>
<div>
![](images/growing-spell.png){:width="300px"}
</div>
</div>

**टीप:** या टप्प्यात, तुम्ही तीन वेगवेगळ्या स्प्राइट्समध्ये कोड जोडाल. तुम्ही Stage च्या खालील Sprite लीस्ट मधून योग्य स्प्राईठ निवडला असल्याची खात्री करा आणि**Code** टॅबवर क्लिक करा.

--- task ---

**grow** बटन स्प्राईटला स्क्रिप्ट जोडा `broadcast`{:class="block3events"} करण्यासाठी `grow`{:class="block3events"} मेसेज:

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (grow v)
```

--- /task ---

--- task ---

**Fairy** स्प्राईट वाढण्यासाठी स्क्रिप्ट जोडा:

![](images/fairy-icon.png)

```blocks3
when I receive [grow v]
change size by [10] // positive numbers increase the size
```

--- /task ---

तुम्ही 'grow' साऊंड तयार करण्यासाठी 'shrink' साऊंड उलट करू शकता!

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Songs played backwards quizzes**</span> या ट्वीस्टसह म्युझीक प्रश्नमंजुषा आहेत. ट्रॅक उलटे आहेत, आणि स्पर्धकांनी मूळ गाण्याचा अंदाज लावायचा आहे - ते वाटते तितके सोपे नाही. 
</p>

--- task ---

**Wand** स्प्राईट निवडा आणि **Sounds** टॅबवर क्लिक करा.

**shrink** साऊंडवर राईट-क्लिक करा (किंवा टॅप आणि होल्ड करा) आणि **duplicate** निवडा.

![](images/wand-icon.png)

![डुप्लीकेट दाखवणारा popup मेनूसह shrink साऊंड.](images/duplicate-sound.png)

कॉपीला `grow` नाव द्या.

साऊंड मागे प्ले करण्यासाठी **Reverse** आयकॉनवर क्लिक करा.

![हायलाईट केलेल्या reverse आयकॉनसह grow साऊंड.](images/reverse-sound.png)

--- /task ---

--- task ---

**Wand** स्प्राईटला स्क्रिप्ट जोडा `grow`{:class="block3sound"} साऊंड प्ले करण्यासाठी जेव्हा `grow`{:class="block3events"} मेसेज प्राप्त होतो:

![](images/wand-icon.png)

```blocks3
when I receive [grow v]
play sound [grow v] until done
```

--- /task ---

--- task ---

**चाचणी:** **shrink** आणि **grow** स्पेल बटनवर तुम्हाला आवडेल तेवढ्या वेळा स्पेल कास्ट करण्यासाठी क्लिक करा.

--- /task ---

--- save ---

