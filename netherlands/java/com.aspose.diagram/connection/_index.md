---
title: Connection
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen voor één verbindingspunt dat voor de vorm is gedefinieerd.
type: docs
weight: 78
url: /nl/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

Bevat elementen voor één verbindingspunt dat voor de vorm is gedefinieerd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Connection()](#Connection--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | Specificeert of het verbindingspunt automatisch wordt gegenereerd. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDirX()](#getDirX--) | Specificeert de x-component voor de vereiste uitlijningsvector van een overeenkomend verbindingspunt. |
| [getDirY()](#getDirY--) | Specificeert de y-component voor de vereiste uitlijningsvector van een overeenkomend verbindingspunt. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getPrompt()](#getPrompt--) | Bevat variabele promptinformatie, gebaseerd op het element waarin het zich bevindt. |
| [getType()](#getType--) | Specificeert verschillende typen, gebaseerd op het element waarin het zich bevindt. |
| [getX()](#getX--) | Specificeert een x-coördinaat op een vorm in lokale coördinaten. |
| [getY()](#getY--) | Specificeert een y-coördinaat op een vorm in lokale coördinaten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


Specificeert of het verbindingspunt automatisch wordt gegenereerd. Een waarde van 1 geeft aan dat het verbindingspunt automatisch wordt gegenereerd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


Specificeert de x-component voor de vereiste uitlijningsvector van een overeenkomend verbindingspunt. Het DirX-element wordt ook gebruikt om de aangehechte arm van een dynamische connector te oriënteren.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


Specificeert de y-component voor de vereiste uitlijningsvector van een overeenkomend verbindingspunt. Het DirY-element wordt ook gebruikt om de aangehechte arm van een dynamische connector te oriënteren.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Bevat variabele promptinformatie, gebaseerd op het element waarin het zich bevindt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


Specificeert verschillende typen, gebaseerd op het element waarin het zich bevindt.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


Specificeert een x-coördinaat op een vorm in lokale coördinaten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Specificeert een y-coördinaat op een vorm in lokale coördinaten. Lokale coördinaten zijn die waarvan het referentiekader de vorm is, in plaats van de pagina.

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

