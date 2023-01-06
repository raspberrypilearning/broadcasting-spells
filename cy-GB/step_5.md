## Trawsnewid llyfant

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Nawr mae'n amser bwrw swyn arall. Y tro hwn rwyt ti'n mynd i fwrw swyn trawsnewid drwy ddarlledu neges `toad`{:class="block3events"} sy'n troi'r corlun **Fairy** yn llyffant! 

Falle ei bod hi'n mynd ar antur lle bydd bod yn llyffant yn fwy defnyddiol.
</div>
<div>
![](images/toad-transformation.png){:width="300px"}
</div>
</div>

--- task ---

Ychwanega sgript at gorlun y botwm **toad** i ddarlledu'r neges 'toad':

![](images/toad-icon.png)

```blocks3 
when this sprite clicked
broadcast [toad v]
```

--- /task ---

--- task ---

Dewisa'r corlun **Fairy** a chlicio'r tab **Gwisgoedd**.

I drawsffurfio'r corlun **Fairy** yn llyffant byddi di'n defnyddio'r gwisgoedd **Fairy-a** a **Fairy-toad-a**.

![Mae gan y rhestr o Wisgoedd sy'n dangos y corlun Fairy ail wisg.](images/toad-costume-added.png)

--- /task ---

--- task ---

Clicia'r tab **Code** ac ychwanegu bloc `newid gwisg i`{:class="block3looks"} at ddiwedd dy sgript `pan fydd y faner werdd wedi'i chlicio`{:class="block3events"} fel fod y Fairy yn ei ffurf dynol pan fyddi di'n rhedeg dy brosiect:

![](images/fairy-icon.png)

```blocks3
when flag clicked
set size to [100] %
+ switch costume to [Fairy-a v]
```

--- /task ---

--- task ---

Ychwanega sgript newydd i'r corlun **Fairy** i'w droi yn llyffant:

![](images/fairy-icon.png)

```blocks3  
when I receive [toad v]
switch costume to [Fairy-toad-a v]
```

--- /task ---

--- task ---

Ychwanega'r sain **Croak** at y corlun **Wand**.

Ail-enwa'r sain i `toad`:

![](images/wand-sprite-icon.png)

![Y tab Sounds gyda'r sain Croak wedi'i rhestru.](images/croak-sound-added.png)

--- /task ---

--- task ---

Ychwanega sgript at y corlun **Wand** sy'n chwarae'r sain `toad`{:class="block3sound"} pan gaiff y swyn llyffant ei bwrw:

![](images/wand-sprite-icon.png)

```blocks3  
when I receive [toad v]
play sound [toad v] until done
```

--- /task ---

--- task ---

**Prawf:** Gwna'n siŵr dy fod yn gallu troi'r corlun **Fairy** yn llyffant, gydag effaith sain, pan fyddi di'n clicio'r botwm **toad**. Clicia ar y faner werdd eto i droi corlun **Fairy** yn ôl yn berson.

![Y Llwyfan yn dangos y corlun Fairy yn y wisg Fairy-toad-a.](images/toad-transformation.png)

--- /task ---

Y gwrthwyneb i'r swyn 'toad' yw'r swyn 'untoad'.

--- task ---

Ychwanega sgript i gorlun y botwm **untoad** i `ddarlledu`{:class="block3events"} y neges 'untoad'{:class="block3events"}:

![](images/untoad-icon.png)

```blocks3 
when this sprite clicked
broadcast [untoad v]
```

--- /task ---

--- task ---

Ychwanega sgript newydd i `untoad`{:class="block3events"} y corlun **Fairy**:

![](images/fairy-icon.png)

```blocks3  
when I receive [untoad v]
switch costume to [Fairy-a v]
```

--- /task ---

--- task ---

Dewisa'r corlun **Wand** a newid i'r tab **Seiniau**.

**Dyblyga'r** sain **toad** a newid ei henw i `untoad`.

Clicia'r eicon **Gwrthdroi** fel bod y sain **untoad** yn chwarae am yn ôl.

![](images/wand-sprite-icon.png)

![Y tab Sounds gyda'r sain untoad wedi'i gwrthdroi yn y rhestr.](images/untoad-sound.png)

--- /task ---

--- task ---

Ychwanega sgript at y corlun **Wand** i chwarae'r sain `untoad`{:class="block3sound"}:

![](images/wand-sprite-icon.png)

```blocks3  
when I receive [untoad v]
play sound [untoad v] until done
```

--- /task ---

--- task ---

**Prawf:** Rho gynnig ar fwrw'r swynau **toad** ac **untoad**, a rho gynnig ar **crebachu** a **thyfu** pan fydd y **Fairy** ar ffurf llyffant.

--- /task ---

--- save ---
