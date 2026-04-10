---
title: Para
second_title: Aspose.Diagram för Java API-referens
description: Innehåller styckeformateringselement för figurens text, såsom indrag, radavstånd, punkter och horisontell justering av stycken.
type: docs
weight: 274
url: /sv/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Innehåller styckeformateringselement för figurens text, såsom indrag, radavstånd, punktlistor och horisontell justering av stycken.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Para()](#Para--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Bestämmer punktlistans stil. |
| [getBulletFont()](#getBulletFont--) | Representerar numret på teckensnittet som används för att formatera texten när en anpassad punktlista sträng anges och värdet i Bullet-elementet är icke-noll. |
| [getBulletFontSize()](#getBulletFontSize--) | Anger storleken på en punkt. |
| [getBulletStr()](#getBulletStr--) | \"Används för att skapa en anpassad punktstil. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getFlags()](#getFlags--) | Indikerar om textens riktning är från vänster till höger eller från höger till vänster. |
| [getHorzAlign()](#getHorzAlign--) | Anger den horisontella justeringen av text i formens textblock. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getIndFirst()](#getIndFirst--) | Anger avståndet den första raden i varje stycke i figurens textblock är indragen från styckets vänstra indrag. |
| [getIndLeft()](#getIndLeft--) | Anger avståndet alla textrader i ett stycke är indragna från den vänstra marginalen i textblocket. |
| [getIndRight()](#getIndRight--) | Anger avståndet som alla textrader i ett stycke är indragna från högermarginalen i textblocket. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Anger om punktteckensnittet ska lokaliseras (översättas till ett annat språk). |
| [getSpAfter()](#getSpAfter--) | Anger mängden utrymme som infogas efter varje stycke i figurens textblock. |
| [getSpBefore()](#getSpBefore--) | Anger mängden utrymme som infogas före varje stycke i figurens textblock. |
| [getSpLine()](#getSpLine--) | Anger avståndet mellan en textrad och nästa, där 100% är höjden på en textrad. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Representerar avståndet mellan första raden i stycket och punkten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | För beskrivningen av denna egenskap, se [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | För beskrivningen av denna egenskap, se [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | För beskrivningen av denna egenskap, se [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | För beskrivningen av denna egenskap, se [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | För beskrivningen av denna egenskap, se [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | För beskrivningen av denna egenskap, se [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Bestämmer punktlistans stil.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Representerar numret på teckensnittet som används för att formatera texten när en anpassad punktlista sträng anges och värdet i Bullet-elementet är icke-noll.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Anger storleken på en punkt.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Används för att skapa en anpassad punktstil. Ange stilen som en sträng (inom citattecken). Till exempel kan du ange strängen, ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Indikerar om textens riktning är från vänster till höger eller från höger till vänster.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Anger den horisontella justeringen av text i formens textblock.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Anger avståndet som den första raden i varje stycke i figurens textblock är indragen från styckets vänstra indrag. Detta värde är oberoende av ritningens skala. Om ritningen skalas förblir första radens indrag oförändrat.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Anger avståndet som alla textrader i ett stycke är indragna från vänstermarginalen i textblocket. Detta värde är oberoende av ritningens skala. Om ritningen skalas förblir vänsterindraget oförändrat.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Anger avståndet som alla textrader i ett stycke är indragna från högermarginalen i textblocket. Detta värde är oberoende av ritningens skala. Om ritningen skalas förblir högra indraget detsamma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Anger om punktteckensnittet ska lokaliseras (översättas till ett annat språk).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Anger mängden utrymme som infogas efter varje stycke i figurens textblock.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Anger mängden utrymme som infogas före varje stycke i figurens textblock.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Anger avståndet mellan en textrad och nästa, där 100% är höjden på en textrad.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Representerar avståndet mellan första raden i stycket och punkten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


För beskrivningen av denna egenskap, se [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


För beskrivningen av denna egenskap, se [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


För beskrivningen av denna egenskap, se [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


För beskrivningen av denna egenskap, se [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


För beskrivningen av denna egenskap, se [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


För beskrivningen av denna egenskap, se [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

