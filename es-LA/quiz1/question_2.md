
--- question ---

---
legend: Pregunta 2 de 3
---

En tu proyecto, hacer clic en un botón transmitira un mensaje. ¿Qué sprite o sprites cambiarían de tamaño al hacer clic en el botón de crecimiento?

![](images/grow-icon.png)

```blocks3
when this sprite clicked
broadcast (crecer v)
```

![](images/Ripley-icon.png)

```blocks3
when I receive [crecer v]
change size by [10]
```

![](images/Robot-icon.png)

```blocks3
when I receive [crecer v]
change size by [10]
```

--- choices ---

- ( ) Cualquier sprite que reciba el mensaje primero

 --- feedback ---

 No, todos los sprites ven los mensajes. Más de un sprite puede responder al mismo mensaje.

 --- /feedback ---

- (x) Ambos, los sprites de Ripley y del Robot

 --- feedback ---

 Sí, cuando un mensaje es `transmite`{:class="block3events"}, todos los sprites que tienen un bloque `cuando recibo`{:class="block3events"} reaccionarán al mensaje.

 --- /feedback ---

- ( ) Ninguno de los sprites

 --- feedback ---

 Echa otro vistazo. El código `transmite`{:class="block3events"} correctamente un mensaje.

 --- /feedback ---

--- /choices ---

--- /question ---
