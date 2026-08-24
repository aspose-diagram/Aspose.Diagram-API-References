---
title: RelEllipticalArcTo
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, которые указывают информацию об эллиптической дуге. Координаты задаются как относительные координаты.
type: docs
weight: 318
url: /ru/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

Содержит элементы, которые указывают информацию об эллиптической дуге. Координаты задаются как относительные координаты.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | Создаёт экземпляр класса [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | x‑координата контрольной точки дуги. |
| [getB()](#getB--) | y‑координата контрольной точки дуги. |
| [getC()](#getC--) | Угол главной оси дуги относительно оси x её родителя. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Отношение главной оси дуги к её второстепенной оси. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getX()](#getX--) | x‑координата конечной вершины эллиптической дуги. |
| [getY()](#getY--) | y‑координата конечной вершины эллиптической дуги. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getA()](../../com.aspose.diagram/relellipticalarcto\\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getB()](../../com.aspose.diagram/relellipticalarcto\\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getC()](../../com.aspose.diagram/relellipticalarcto\\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getD()](../../com.aspose.diagram/relellipticalarcto\\#getD--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/relellipticalarcto\\#getDel--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/relellipticalarcto\\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getX()](../../com.aspose.diagram/relellipticalarcto\\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getY()](../../com.aspose.diagram/relellipticalarcto\\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


Создаёт экземпляр класса [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


Координата x контрольной точки дуги. Контрольная точка лучше всего располагается примерно посередине между начальной и конечной вершинами дуги. В противном случае дуга может разрастись до экстремального размера, чтобы пройти через контрольную точку, что приводит к непредсказуемым результатам.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


y‑координата контрольной точки дуги.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


Угол главной оси дуги относительно оси x её родителя.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


Отношение большой оси дуги к её малой оси. Несмотря на обычное значение этих слов, большая ось не обязана быть больше малой, поэтому это отношение не обязано быть больше 1. Установка этого элемента в значение, меньшее или равное 0, или большее 1000, может привести к непредсказуемым результатам.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getX() {#getX--}
```
public DoubleValue getX()
```


x‑координата конечной вершины эллиптической дуги.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


y‑координата конечной вершины эллиптической дуги.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getA()](../../com.aspose.diagram/relellipticalarcto\\#getA--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getB()](../../com.aspose.diagram/relellipticalarcto\\#getB--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getC()](../../com.aspose.diagram/relellipticalarcto\\#getC--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getD()](../../com.aspose.diagram/relellipticalarcto\\#getD--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/relellipticalarcto\\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/relellipticalarcto\\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getX()](../../com.aspose.diagram/relellipticalarcto\\#getX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getY()](../../com.aspose.diagram/relellipticalarcto\\#getY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

