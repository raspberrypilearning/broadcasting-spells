
--- question ---

---
legend: 質問2/3
---

プロジェクトでは、ボタンをクリックするとメッセージが発信されます。 拡がるボタンがクリックされたときにサイズが変わるスプライトはどれですか？

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (拡がる v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [拡がる v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [拡がる v]
change size by [10]
```

--- choices ---

- ( ) 最初にメッセージを受信したスプライト

 --- feedback ---

 いいえ、メッセージはすべてのスプライトが見ることができます。 複数のスプライトが同じメッセージに応答できます。

 --- /feedback ---

- (x) RipleyスプライトとRobotスプライトの両方

 --- feedback ---

 そうです、メッセージが `送られた`{:class="block3events"}とき、`を受け取ったとき`{:class="block3events"}ブロックのある、すべてのスプライトは、メッセージに反応します。

 --- /feedback ---

- ( ) どちらのスプライトも変わらない

 --- feedback ---

 もう一度見てください。 コードは正しくメッセージを`送って`{:class="block3events"}います。

 --- /feedback ---

--- /choices ---

--- /question ---
