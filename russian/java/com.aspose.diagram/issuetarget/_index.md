---
title: IssueTarget
second_title: Справочник API Aspose.Diagram for Java
description: В зависимости от цели родительской проблемы проверки указывает либо страницу, либо и страницу, и фигуру, с которыми связана родительская проблема проверки.
type: docs
weight: 210
url: /ru/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

В зависимости от цели родительской проблемы проверки указывает либо страницу, либо и страницу, и фигуру, с которыми связана родительская проблема проверки. Если целью родительской проблемы проверки является документ, IssueTarget не указывает ни страницу, ни фигуру.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Указывает уникальный идентификатор страницы, связанной с родительской проблемой проверки. |
| [getShapeId()](#getShapeId--) | Указывает уникальный идентификатор фигуры, связанной с родительской проблемой проверки. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Для описания этого свойства, пожалуйста, смотрите [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Для описания этого свойства, пожалуйста, смотрите [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Конструктор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPageId() {#getPageId--}
```
public long getPageId()
```


Указывает уникальный идентификатор страницы, связанной с родительской проблемой проверки. Если целью является документ, значение PageID может быть 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Указывает уникальный идентификатор фигуры, связанной с родительской проблемой проверки. Если целью является документ или страница, значение ShapeID может быть 0xFFFFFFFF.

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


Для описания этого свойства, пожалуйста, смотрите [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

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

