---
title: ShapeCollection
second_title: Aspose.Diagram voor Java API-referentie
description: Collectie van vormen.
type: docs
weight: 356
url: /nl/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Collectie van vormen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Voeg de vorm toe aan de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Haalt het element op op de opgegeven index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [getShape(String name)](#getShape-java.lang.String-) | Haalt het element op bij de opgegeven naam. |
| [getShape(long ID)](#getShape-long-) | Haalt het element op bij de opgegeven ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Haalt het element op inclusief de onderliggende vorm met de opgegeven id. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Haalt het element op inclusief de onderliggende vorm met de opgegeven naam. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Groepeer de vormen. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is er een item aanwezig in de collectie. |
| [iterator()](#iterator--) | Ondersteunt een eenvoudige iteratie over een niet-generieke collectie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Verwijder de vorm uit de collectie. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Verwijder de vormen, inclusief DEPENDSON-vormen, uit de collectie. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Degroepeer de vorm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Voeg de vorm toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Verwijdert alle elementen uit de collectie.

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
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Haalt het element op bij de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Haalt het element op bij de opgegeven ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Haalt het element op inclusief de onderliggende vorm met de opgegeven id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Haalt het element op inclusief de onderliggende vorm met de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Groeper de vormen. De vorm in de groupItems mag niet worden gegroepeerd. De vorm moet in deze Shapes-collectie zitten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | de groepitems. |

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


Is er een item aanwezig in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | index van element. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Ondersteunt een eenvoudige iteratie over een niet-generieke collectie.

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


Verwijder de vorm uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Vorm |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Verwijder de vormen, inclusief DEPENDSON-vormen, uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Vorm |

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


Degroepeer de vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | de groepvorm. |

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

