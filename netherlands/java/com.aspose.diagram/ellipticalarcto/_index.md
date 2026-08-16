---
title: EllipticalArcTo
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die informatie over een elliptische boog specificeren.
type: docs
weight: 140
url: /nl/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

Bevat elementen die informatie over een elliptische boog specificeren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | Maakt een instantie van de klasse [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | De x-coördinaat van het controlepunt van de boog. |
| [getB()](#getB--) | De y-coördinaat van het controlepunt van een boog. |
| [getC()](#getC--) | De hoek van de hoofdas van een boog ten opzichte van de x-as van de bovenliggende. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | De verhouding van de hoofdas van een boog tot de kleine as. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getX()](#getX--) | De x-coördinaat van het eindpunt van een elliptische boog. |
| [getY()](#getY--) | De y-coördinaat van het eindpunt van een elliptische boog. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


Maakt een instantie van de klasse [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) aan.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getA() {#getA--}
```
public DoubleValue getA()
```


De x-coördinaat van het controlepunt van de boog. Het controlepunt is het beste ongeveer halverwege de begin- en eindpunten van de boog geplaatst. Anders kan de boog tot een extreme grootte groeien om door het controlepunt te gaan, met onvoorspelbare resultaten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


De y-coördinaat van het controlepunt van een boog.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


De hoek van de hoofdas van een boog ten opzichte van de x-as van de bovenliggende.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


De verhouding van de grote as van een boog tot de kleine as. Ondanks de gebruikelijke betekenis van deze woorden, hoeft de grote as niet groter te zijn dan de kleine as, dus deze verhouding hoeft niet groter te zijn dan 1. Het instellen van dit element op een waarde kleiner dan of gelijk aan 0 of groter dan 1000 kan tot onvoorspelbare resultaten leiden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


De nulgebaseerde index van het element binnen zijn bovenliggende element.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


De x-coördinaat van het eindpunt van een elliptische boog.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


De y-coördinaat van het eindpunt van een elliptische boog.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--)

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

