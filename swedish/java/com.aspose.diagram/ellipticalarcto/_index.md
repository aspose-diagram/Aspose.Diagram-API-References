---
title: EllipticalArcTo
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som specificerar information om en elliptisk båge.
type: docs
weight: 140
url: /sv/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

Innehåller element som specificerar information om en elliptisk båge.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | Skapar en instans av klassen [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | x-koordinaten för bågens kontrollpunkt. |
| [getB()](#getB--) | y-koordinaten för en bågs kontrollpunkt. |
| [getC()](#getC--) | Vinkeln på en bågs huvudaxel i förhållande till förälderns x‑axel. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Förhållandet mellan en bågs huvudaxel och dess sekundära axel. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getX()](#getX--) | x-koordinaten för den avslutande hörnet av en elliptisk båge. |
| [getY()](#getY--) | y-koordinaten för den avslutande hörnet av en elliptisk båge. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av den här egenskapen, se [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | För beskrivningen av den här egenskapen, se [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


Skapar en instans av klassen [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


x-koordinaten för bågens kontrollpunkt. Kontrollpunkten bör placeras ungefär halvvägs mellan bågens start- och slutvertexer. Annars kan bågen växa till en extrem storlek för att passera genom kontrollpunkten, med oförutsägbara resultat.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


y-koordinaten för en bågs kontrollpunkt.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


Vinkeln på en bågs huvudaxel i förhållande till förälderns x‑axel.

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


Förhållandet mellan en bågs huvudaxel och dess sekundära axel. Trots den vanliga betydelsen av dessa ord behöver huvudaxeln inte vara större än den sekundära axeln, så detta förhållande behöver inte vara större än 1. Att sätta detta element till ett värde mindre än eller lika med 0 eller större än 1000 kan leda till oförutsägbara resultat.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


x-koordinaten för den avslutande hörnet av en elliptisk båge.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


y-koordinaten för den avslutande hörnet av en elliptisk båge.

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


För beskrivningen av den här egenskapen, se [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


För beskrivningen av den här egenskapen, se [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


För beskrivningen av den här egenskapen, se [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


För beskrivningen av den här egenskapen, se [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av den här egenskapen, se [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


För beskrivningen av den här egenskapen, se [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


För beskrivningen av den här egenskapen, se [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--)

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

