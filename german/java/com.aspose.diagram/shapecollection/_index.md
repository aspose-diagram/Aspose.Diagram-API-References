---
title: ShapeCollection
second_title: Aspose.Diagram for Java API-Referenz
description: Sammlung von Formen.
type: docs
weight: 356
url: /de/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Sammlung von Formen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Füge die Form zur Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gibt das Element am angegebenen Index zurück. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. |
| [getShape(String name)](#getShape-java.lang.String-) | Liefert das Element mit dem angegebenen Namen. |
| [getShape(long ID)](#getShape-long-) | Liefert das Element mit der angegebenen ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Gibt das Element einschließlich seiner Kindform bei der angegebenen ID zurück. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Gibt das Element einschließlich seiner Kindform beim angegebenen Namen zurück. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Gruppiere die Formen. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existiert ein Element in der Sammlung. |
| [iterator()](#iterator--) | Unterstützt eine einfache Iteration über eine nicht generische Sammlung. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Entferne die Form aus der Sammlung. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Entferne die Formen einschließlich DEPENDSON-Formen aus der Sammlung. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Gruppierung der Form aufheben. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Füge die Form zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Entfernt alle Elemente aus der Sammlung.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |

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


Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Liefert das Element mit dem angegebenen Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Liefert das Element mit der angegebenen ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Gibt das Element einschließlich seiner Kindform bei der angegebenen ID zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Gibt das Element einschließlich seiner Kindform beim angegebenen Namen zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Gruppiere die Formen. Die Form in den groupItems sollte nicht gruppiert werden. Die Form muss in dieser Shapes-Sammlung sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | die group items. |

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


Existiert ein Element in der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index des Elements. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Unterstützt eine einfache Iteration über eine nicht generische Sammlung.

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


Entferne die Form aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Form |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Entferne die Formen einschließlich DEPENDSON-Formen aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Form |

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


Gruppierung der Form aufheben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | die group shape. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

