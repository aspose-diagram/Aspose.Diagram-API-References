---
title: Внешний
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio.
type: docs
weight: 163
url: /ru/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. Также включает элементы, указывающие расстояние смещения изображения объекта внутри его границ.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getImgHeight()](#getImgHeight--) | Определяет высоту изображения объекта внутри его границы. |
| [getImgOffsetX()](#getImgOffsetX--) | Определяет расстояние, на которое объект смещён по горизонтали от начала границы объекта. |
| [getImgOffsetY()](#getImgOffsetY--) | Определяет расстояние, на которое объект смещён по вертикали от начала границы объекта. |
| [getImgWidth()](#getImgWidth--) | Определяет ширину изображения объекта внутри его границы. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/foreign\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт глубокую копию этого экземпляра.

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


Определяет высоту изображения объекта внутри его границы. Формула по умолчанию: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


Определяет расстояние, на которое объект смещён по горизонтали от начала границы объекта. Значение по умолчанию равно 0; формула по умолчанию: F="ImgWidth\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


Определяет расстояние, на которое объект смещён по вертикали от начала границы объекта. Значение по умолчанию равно 0; формула по умолчанию: F="ImgHeight\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


Определяет ширину изображения объекта внутри его границы. Формула по умолчанию: F="Width\*1".

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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/foreign\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

