---
title: ShapeCollection
second_title: Aspose.Diagram for Java API Reference
description: Collection of Shapes.
type: docs
weight: 379
url: /java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, com.aspose.diagram.Collection
```
public class ShapeCollection extends Collection<Shape>
```

Collection of Shapes.
## Methods

| Method | Description |
| --- | --- |
| [add(T o)](#add-T-) |  |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Add the shape in the collection. |
| [clear()](#clear--) |  |
| [contains(Object o)](#contains-java.lang.Object-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) |  |
| [getInnerList()](#getInnerList--) |  |
| [getShape(String name)](#getShape-java.lang.String-) | Gets the element at the specified name. |
| [getShape(long ID)](#getShape-long-) | Gets the element at the specified ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Gets the element including it's child shape at the specified id. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Gets the element including it's child shape at the specified name. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Group the shapes. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) |  |
| [isExist(int index)](#isExist-int-) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Remove the shape from the collection. |
| [removeAt(int index)](#removeAt-int-) |  |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Remove the shapes including DEPENDSON shapes from the collection. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | UnGroup the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(T o) {#add-T-}
```
public int add(T o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | T |  |

**Returns:**
int
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Add the shape in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```




### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public T get(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
T
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




**Returns:**
int
### getInnerList() {#getInnerList--}
```
public ArrayList<T> getInnerList()
```




**Returns:**
java.util.ArrayList<T>
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Gets the element at the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Gets the element at the specified ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Gets the element including it's child shape at the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Gets the element including it's child shape at the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | the group items. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Return the group shape.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
boolean
### iterator() {#iterator--}
```
public Iterator<T> iterator()
```




**Returns:**
java.util.Iterator<T>
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


Remove the shape from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Remove the shapes including DEPENDSON shapes from the collection.

**Parameters:**
| Parameter | Type | Description |
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


UnGroup the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | the group shape. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

