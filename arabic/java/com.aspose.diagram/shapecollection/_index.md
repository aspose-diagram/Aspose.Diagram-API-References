---
title: ShapeCollection
second_title: Aspose.Diagram لـ Java API Reference
description: مجموعة من الأشكال.
type: docs
weight: 356
url: /ar/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

مجموعة من الأشكال.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | أضف الشكل إلى المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [getShape(String name)](#getShape-java.lang.String-) | يحصل على العنصر بالاسم المحدد. |
| [getShape(long ID)](#getShape-long-) | يحصل على العنصر بالمعرف المحدد. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | يحصل على العنصر بما في ذلك الشكل الفرعي له بالمعرف المحدد. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | يحصل على العنصر بما في ذلك الشكل الفرعي له بالاسم المحدد. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | تجميع الأشكال. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | هل يوجد عنصر في المجموعة. |
| [iterator()](#iterator--) | يدعم تكرارًا بسيطًا على مجموعة غير عامة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | إزالة الشكل من المجموعة. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | إزالة الأشكال بما في ذلك الأشكال التي تعتمد على DEPENDSON من المجموعة. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | إلغاء تجميع الشكل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


أضف الشكل إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - المعرف
### clear() {#clear--}
```
public void clear()
```


يزيل جميع العناصر من المجموعة.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
### get(int index) {#get-int-}
```
public Shape get(int index)
```


يحصل على العنصر في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int |  |

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


يحصل على عدد العناصر الموجودة فعليًا في المجموعة.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


يحصل على العنصر بالاسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


يحصل على العنصر بالمعرف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


يحصل على العنصر بما في ذلك الشكل الفرعي له بالمعرف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| معرف | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


يحصل على العنصر بما في ذلك الشكل الفرعي له بالاسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


تجميع الأشكال. يجب ألا يتم تجميع الشكل الموجود في groupItems. يجب أن يكون الشكل في مجموعة Shapes هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | عناصر المجموعة. |

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


هل يوجد عنصر في المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس العنصر. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


يدعم تكرارًا بسيطًا على مجموعة غير عامة.

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


إزالة الشكل من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | شكل |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


إزالة الأشكال بما في ذلك الأشكال التي تعتمد على DEPENDSON من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | شكل |

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


إلغاء تجميع الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | شكل المجموعة. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

