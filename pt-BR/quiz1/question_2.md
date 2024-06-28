
--- question ---

---
legend: Pergunta 2 de 3
---

No seu projeto, clicar em um botão transmite uma mensagem. Qual ator ou atores mudariam de tamanho quando o botão crescer fosse clicado?

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (crescer v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [crescer v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [crescer v]
change size by [10]
```

--- choices ---

- ( ) Qualquer ator que receber a mensagem primeiro

 --- feedback ---

 Não, as mensagens são vistas por todos os atores. Mais de um ator pode responder à mesma mensagem.

 --- /feedback ---

- (x) Os atores Ripley e Robot

 --- feedback ---

 Sim, quando uma mensagem é `transmitida`{:class="block3events"}, todos os atores que possuem um bloco `quando eu receber`{:class="block3events"} reagirão à mensagem.

 --- /feedback ---

- ( ) Nenhum dos atores

 --- feedback ---

 Observe novamente. O código `transmite`{:class="block3events"} corretamente uma mensagem.

 --- /feedback ---

--- /choices ---

--- /question ---
