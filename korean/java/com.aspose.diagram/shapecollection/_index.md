---
title: ShapeCollection
second_title: Aspose.Diagram for Java API 참조
description: 도형 컬렉션.
type: docs
weight: 356
url: /ko/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

도형 컬렉션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Add the shape in the collection. |
| [clear()](#clear--) | 컬렉션에서 모든 요소를 제거합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [getShape(String name)](#getShape-java.lang.String-) | Gets the element at the specified name. |
| [getShape(long ID)](#getShape-long-) | Gets the element at the specified ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Gets the element including it's child shape at the specified id. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Gets the element including it's child shape at the specified name. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Group the shapes. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | 컬렉션에 항목이 존재합니다. |
| [iterator()](#iterator--) | 비제네릭 컬렉션에 대한 간단한 반복을 지원합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | 컬렉션에서 도형을 제거합니다. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | 컬렉션에서 DEPENDSON 도형을 포함한 도형들을 제거합니다. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | 도형의 그룹을 해제합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Add the shape in the collection.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


컬렉션에서 모든 요소를 제거합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |

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


컬렉션에 실제로 포함된 요소 수를 가져옵니다.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Gets the element at the specified name.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


도형들을 그룹화합니다. groupItems에 있는 도형은 그룹화되지 않아야 합니다. 도형은 이 Shapes 컬렉션에 있어야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | 그 그룹 항목들. |

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


컬렉션에 항목이 존재합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 요소의 인덱스. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


비제네릭 컬렉션에 대한 간단한 반복을 지원합니다.

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


컬렉션에서 도형을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | 도형 |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


컬렉션에서 DEPENDSON 도형을 포함한 도형들을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | 도형 |

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


도형의 그룹을 해제합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | 그 그룹 도형. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

