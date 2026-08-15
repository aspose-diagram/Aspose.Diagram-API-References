---
title: ShapeCollection
second_title: Aspose.Diagram för Java API-referens
description: Samling av former.
type: docs
weight: 356
url: /sv/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Samling av former.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Lägg till formen i samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Hämtar elementet på det angivna indexet. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [getShape(String name)](#getShape-java.lang.String-) | Hämtar elementet med angivet namn. |
| [getShape(long ID)](#getShape-long-) | Hämtar elementet med angivet ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Hämtar elementet inklusive dess underordnade form med angivet ID. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Hämtar elementet inklusive dess underordnade form med angivet namn. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Gruppera formerna. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Finns ett objekt i samlingen. |
| [iterator()](#iterator--) | Stöder en enkel iteration över en icke-generisk samling. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Ta bort formen från samlingen. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Ta bort formerna inklusive DEPENDSON-former från samlingen. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Avgruppera formen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Lägg till formen i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Tar bort alla element från samlingen.

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
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Hämtar elementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Hämtar antalet element som faktiskt finns i samlingen.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Hämtar elementet med angivet namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Hämtar elementet med angivet ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Hämtar elementet inklusive dess underordnade form med angivet ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Hämtar elementet inklusive dess underordnade form med angivet namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Gruppera formerna. Formen i groupItems bör inte grupperas. Formen måste finnas i denna Shapes-samling.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | gruppobjekten. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Return the group shape.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


Finns ett objekt i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | index för elementet. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Stöder en enkel iteration över en icke-generisk samling.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Shape item) {#remove-com.aspose.diagram.Shape-}
```
public void remove(Shape item)
```


Ta bort formen från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Ta bort formerna inklusive DEPENDSON-former från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unGroup(Shape groupShape) {#unGroup-com.aspose.diagram.Shape-}
```
public void unGroup(Shape groupShape)
```


Avgruppera formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | gruppformen. |

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

