---
title: ShapeCollection
second_title: Справочник API Aspose.Diagram for Java
description: Коллекция фигур.
type: docs
weight: 356
url: /ru/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Коллекция фигур.
## Методы

| Метод | Описание |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Добавить форму в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Получает элемент по указанному индексу. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [getShape(String name)](#getShape-java.lang.String-) | Получает элемент с указанным именем. |
| [getShape(long ID)](#getShape-long-) | Получает элемент с указанным ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Получает элемент, включая его дочернюю форму, по указанному идентификатору. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Получает элемент, включая его дочернюю форму, по указанному имени. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Группировать формы. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Элемент существует в коллекции. |
| [iterator()](#iterator--) | Поддерживает простую итерацию по необобщённой коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Удалить форму из коллекции. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Удалить формы, включая формы DEPENDSON, из коллекции. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Разгруппировать форму. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Добавить форму в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Получает элемент по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |

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


Получает количество элементов, фактически содержащихся в коллекции.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Получает элемент с указанным именем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Получает элемент с указанным ID.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Получает элемент, включая его дочернюю форму, по указанному идентификатору.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Получает элемент, включая его дочернюю форму, по указанному имени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Группировать формы. Форма в groupItems не должна быть сгруппирована. Форма должна находиться в этой коллекции Shapes.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | элементы группы. |

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


Элемент существует в коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | индекс элемента. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Поддерживает простую итерацию по необобщённой коллекции.

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


Удалить форму из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Форма |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Удалить формы, включая формы DEPENDSON, из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Форма |

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


Разгруппировать форму.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | форма группы. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

