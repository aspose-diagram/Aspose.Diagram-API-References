---
title: Skydd
second_title: Aspose.Diagram för Java API-referens
description: Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer.
type: docs
weight: 312
url: /sv/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer. Det skyddar inte heller mot ändringar som görs i ShapeSheet-fönstret.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getLockAspect()](#getLockAspect--) | Anger om bildförhållandet för formen är låst. |
| [getLockBegin()](#getLockBegin--) | Anger om startpunkten för en 1‑D‑form är låst till en specifik plats. |
| [getLockCalcWH()](#getLockCalcWH--) | Anger om en formes markeringsrektangel är låst så att den inte kan beräknas om när en hörnpunkt redigeras eller en elementtyp ändras i Geom‑elementet. |
| [getLockCrop()](#getLockCrop--) | Anger om ett främmande objekt är låst så att det inte kan beskäras med Beskär‑verktyget i Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Bestämmer om användaren kan lägga till, ta bort eller ändra anpassade egenskaper i användargränssnittet (UI) genom att använda dialogrutan Definiera anpassade egenskaper. |
| [getLockDelete()](#getLockDelete--) | Anger om en form är låst så att den inte kan tas bort. |
| [getLockEnd()](#getLockEnd--) | Anger om slutpunkten för en 1‑D‑form är låst till en specifik plats. |
| [getLockFormat()](#getLockFormat--) | Anger om formateringen av en form är låst så att den inte kan ändras. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Tillåter en delform att blockera formateringsändringar som appliceras på en överordnad gruppform i Visio‑användargränssnittet och som annars skulle spridas ner till enskilda gruppformer. |
| [getLockGroup()](#getLockGroup--) | Anger om en grupp är låst så att den inte kan avgrupperas. |
| [getLockHeight()](#getLockHeight--) | Anger om formens höjd är låst. |
| [getLockMoveX()](#getLockMoveX--) | Anger om formens horisontella position är låst så att den inte kan flyttas horisontellt. |
| [getLockMoveY()](#getLockMoveY--) | Anger om formens vertikala position är låst så att den inte kan flyttas vertikalt. |
| [getLockRotate()](#getLockRotate--) | Anger om formen är låst så att den inte kan roteras med Rotations‑verktyget eller kommandona Rotera vänster eller Rotera höger i Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Anger om en formes markeringsrektangel är låst så att den inte kan beräknas om när en hörnpunkt redigeras eller en elementtyp ändras i Geom‑elementet. |
| [getLockTextEdit()](#getLockTextEdit--) | Anger om texten i en form är låst så att den inte kan redigeras. |
| [getLockThemeColors()](#getLockThemeColors--) | Förhindrar att användare tillämpar temafärger på formen. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Förhindrar att användare applicerar temaeffekter på formen. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Anger om hörnen på en form är låsta så att de inte kan redigeras med några verktyg i verktygsfältet. |
| [getLockWidth()](#getLockWidth--) | Anger om formens bredd är låst så att den förblir oförändrad när formen ändras i storlek. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/protection\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Anger om bildförhållandet för formen är låst. Om låst kan formen endast storleksändras proportionellt; den kan inte storleksändras i en enda dimension.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Anger om startpunkten för en 1‑D‑form är låst till en specifik plats.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Anger om en formes markeringsrektangel är låst så att den inte kan beräknas om när en hörnpunkt redigeras eller en elementtyp ändras i Geom‑elementet.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Anger om ett främmande objekt är låst så att det inte kan beskäras med Beskär‑verktyget i Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Bestämmer om användaren kan lägga till, ta bort eller ändra anpassade egenskaper i användargränssnittet (UI) genom att använda dialogrutan Definiera anpassade egenskaper.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Anger om en form är låst så att den inte kan tas bort.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Anger om slutpunkten för en 1‑D‑form är låst till en specifik plats.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Anger om formateringen av en form är låst så att den inte kan ändras. Specifikt skyddar detta element mot att ändra text-, linje- och fyllningsformatering, eller att ändra vilket Stil‑element formen ärver från.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Tillåter en delform att blockera formateringsändringar som appliceras på en överordnad gruppform i Visio‑användargränssnittet och som annars skulle spridas ner till enskilda gruppformer.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Anger om en grupp är låst så att den inte kan avgrupperas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Anger om formens höjd är låst. Om låst förblir dess höjd oförändrad när formen ändras i storlek.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Anger om formens horisontella position är låst så att den inte kan flyttas horisontellt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Anger om formens vertikala position är låst så att den inte kan flyttas vertikalt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Anger om formen är låst så att den inte kan roteras med Rotations‑verktyget eller kommandona Rotera vänster eller Rotera höger i Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Anger om en formes markeringsrektangel är låst så att den inte kan beräknas om när en hörnpunkt redigeras eller en elementtyp ändras i Geom‑elementet.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Anger om texten i en form är låst så att den inte kan redigeras. Texten kan dock fortfarande formateras genom att tillämpa en stil, med Stil‑alternativen på fliken Teckensnitt i textrutan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Förhindrar att användare tillämpar temafärger på formen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Förhindrar att användare applicerar temaeffekter på formen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Anger om hörnen på en form är låsta så att de inte kan redigeras med några verktyg i verktygsfältet.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Anger om formens bredd är låst så att den förblir oförändrad när formen ändras i storlek.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/protection\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

