---
title: Controle
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen voor de x- en y-coördinaten van elke besturingshandvat die voor een vorm is gedefinieerd en elementen die de manier specificeren waarop het besturingshandvat zich moet gedragen.
type: docs
weight: 87
url: /nl/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

Bevat elementen voor de x- en y-coördinaten van elke controlehandgreep die voor een vorm is gedefinieerd, en elementen die de manier specificeren waarop de controlehandgreep zich moet gedragen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Control()](#Control--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [canGlue()](#canGlue--) | Bepaalt of een besturingshandvat aan andere vormen kan worden geplakt. |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getPrompt()](#getPrompt--) | Prompt-element specificeert beschrijvende tekst die verschijnt als een tool tip wanneer de muisaanwijzer wordt gepauzeerd boven het besturingshandvat van een vorm. |
| [getX()](#getX--) | De x-coördinaat die de locatie van het besturingshandvat van een vorm aangeeft. |
| [getXCon()](#getXCon--) | Specificeert het type gedrag dat de x-coördinaat van het besturingshandvat vertoont nadat het handvat is verplaatst. |
| [getXDyn()](#getXDyn--) | Specificeert de x-coördinaat voor het ankerpunt van een besturingshandvat in lokale coördinaten. |
| [getY()](#getY--) | De y-coördinaat die de locatie van het besturingshandvat van een vorm aangeeft. |
| [getYCon()](#getYCon--) | Specificeert het type gedrag dat de x-coördinaat van het besturingshandvat vertoont nadat het handvat is verplaatst. |
| [getYDyn()](#getYDyn--) | Specificeert de y-coördinaat voor het ankerpunt van een besturingshandvat in lokale coördinaten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | Voor de beschrijving van deze eigenschap, zie [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | Voor de beschrijving van deze eigenschap, zie [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | Voor de beschrijving van deze eigenschap, zie [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | Voor de beschrijving van deze eigenschap, zie [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


Constructor.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


Bepaalt of een besturingshandvat aan andere vormen kan worden geplakt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


De nulgebaseerde index van het element binnen zijn bovenliggende element.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt-element specificeert beschrijvende tekst die verschijnt als een tool tip wanneer de muisaanwijzer wordt gepauzeerd boven het besturingshandvat van een vorm.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


De x-coördinaat die de locatie van het besturingshandvat van een vorm aangeeft.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


Specificeert het type gedrag dat de x-coördinaat van het besturingshandvat vertoont nadat het handvat is verplaatst.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


Specificeert de x-coördinaat voor het ankerpunt van een controlehandvat in lokale coördinaten. Het ankerpunt wordt gebruikt voor rubberbanden tijdens dynamiek.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


De y-coördinaat die de locatie van het besturingshandvat van een vorm aangeeft.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


Specificeert het type gedrag dat de x-coördinaat van het besturingshandvat vertoont nadat het handvat is verplaatst.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


Specificeert de y-coördinaat voor het ankerpunt van een controlehandvat in lokale coördinaten. Het ankerpunt wordt gebruikt voor rubberbanden tijdens dynamiek.

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


Voor de beschrijving van deze eigenschap, zie [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


Voor de beschrijving van deze eigenschap, zie [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


Voor de beschrijving van deze eigenschap, zie [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


Voor de beschrijving van deze eigenschap, zie [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

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

