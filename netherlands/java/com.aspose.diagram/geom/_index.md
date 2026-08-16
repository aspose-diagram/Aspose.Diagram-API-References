---
title: Geom
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die de coördinaten van de hoekpunten specificeren voor de lijnen en boogsegmenten waaruit de vorm bestaat.
type: docs
weight: 169
url: /nl/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Bevat elementen die de coördinaten van de hoekpunten van de lijnen en boogsegmenten die de vorm vormen, specificeren. Als de vorm meer dan één pad heeft, is er voor elk pad een Geom‑element.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Geom()](#Geom--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Collectie van coördinaten. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Retourneert de IX‑waarde voor het volgende coördinatenverzamelingslid van de vorm. |
| [getNoFill()](#getNoFill--) | Specificeert of een pad kan worden gevuld. |
| [getNoLine()](#getNoLine--) | Specificeert of er een lijn wordt getekend rond de rand van het pad. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Bepaalt of een vorm kan worden geselecteerd of versleept wanneer de gebruiker klikt op het gevulde gebied dat is gedefinieerd door de Geometry‑sectie. |
| [getNoShow()](#getNoShow--) | Specificeert of een pad wordt weergegeven op de tekentabel. |
| [getNoSnap()](#getNoSnap--) | Specificeert of andere vormen aan een pad vastklikken. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


Constructor.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Collectie van coördinaten. Het toont een reeks coördinaten.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
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
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Retourneert de IX‑waarde voor het volgende coördinatenverzamelingslid van de vorm.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Specificeert of een pad kan worden gevuld.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Specificeert of er een lijn wordt getekend rond de rand van het pad.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Bepaalt of een vorm kan worden geselecteerd of versleept wanneer de gebruiker klikt op het gevulde gebied dat is gedefinieerd door de Geometry‑sectie.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Specificeert of een pad wordt weergegeven op de tekentabel.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Specificeert of andere vormen aan een pad vastklikken.

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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

