---
title: Geom
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, указывающие координаты вершин линий и дуг, составляющих фигуру.
type: docs
weight: 169
url: /ru/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Содержит элементы, указывающие координаты вершин линий и дуг, составляющих форму. Если у формы более одного контура, для каждого контура присутствует элемент Geom.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Geom()](#Geom--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Коллекция координат. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Возвращает значение IX для следующего члена коллекции координат формы. |
| [getNoFill()](#getNoFill--) | Указывает, может ли контур быть заполнен. |
| [getNoLine()](#getNoLine--) | Указывает, рисуется ли линия вокруг границы контура. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Определяет, может ли форма быть выбрана или перетащена, когда пользователь щёлкает по заполненной области, определённой в разделе Geometry. |
| [getNoShow()](#getNoShow--) | Указывает, отображается ли контур на странице чертежа. |
| [getNoSnap()](#getNoSnap--) | Указывает, привязываются ли другие формы к контуру. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, см. [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, см. [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, см. [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, см. [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, см. [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


Конструктор.

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
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Коллекция координат. Показывает последовательность координат.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Возвращает значение IX для следующего члена коллекции координат формы.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Указывает, может ли контур быть заполнен.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Указывает, рисуется ли линия вокруг границы контура.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Определяет, может ли форма быть выбрана или перетащена, когда пользователь щёлкает по заполненной области, определённой в разделе Geometry.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Указывает, отображается ли контур на странице чертежа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Указывает, привязываются ли другие формы к контуру.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


Для описания этого свойства, пожалуйста, см. [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


Для описания этого свойства, пожалуйста, см. [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


Для описания этого свойства, пожалуйста, см. [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


Для описания этого свойства, пожалуйста, см. [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


Для описания этого свойства, пожалуйста, см. [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

