---
title: ShapeCollection
second_title: Aspose.Diagram for Java API 参考
description: 形状集合。
type: docs
weight: 356
url: /zh/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

形状集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | 在集合中添加形状。 |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getShape(String name)](#getShape-java.lang.String-) | 获取指定名称的元素。 |
| [getShape(long ID)](#getShape-long-) | 获取指定 ID 的元素。 |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | 获取指定 id 的元素，包括其子形状。 |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | 获取指定名称的元素，包括其子形状。 |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | 对形状进行分组。 |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | 支持对非泛型集合进行简单迭代。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | 从集合中移除形状。 |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | 从集合中移除包括 DEPENDSON 形状的形状。 |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | 取消对形状的分组。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


在集合中添加形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Gets the element at the specified index.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |

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


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


获取指定名称的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


获取指定 ID 的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


获取指定 id 的元素，包括其子形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


获取指定名称的元素，包括其子形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


对形状进行分组。groupItems 中的形状不应被分组。该形状必须在此 Shapes 集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | group items。 |

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


Is exist item in the collection.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 元素的索引。 |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


支持对非泛型集合进行简单迭代。

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


从集合中移除形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


从集合中移除包括 DEPENDSON 形状的形状。

**Parameters:**
| 参数 | 类型 | 描述 |
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


取消对形状的分组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | group shape。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

