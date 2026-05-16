---
title: Line
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, указывающие общую информацию о позиционировании фигуры.
type: docs
weight: 221
url: /ru/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Содержит элементы, указывающие общую информацию о позиционировании фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Указывает, имеет ли линия наконечник‑стрелка или иной формат конца линии в своей первой вершине. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Определяет размер наконечника‑стрелки в начале линии. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Указывает тип составной линии CompoundType фигуры. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getEndArrow()](#getEndArrow--) | Указывает, имеет ли линия наконечник‑стрелка или иной формат конца линии в своей последней вершине. |
| [getEndArrowSize()](#getEndArrowSize--) | Указывает размер наконечника‑стрелки в конце линии. |
| [getGradientLine()](#getGradientLine--) | Содержит текущие значения форматирования градиентной линии для фигуры |
| [getLineCap()](#getLineCap--) | Указывает, имеет ли линия закруглённые или квадратные концы. |
| [getLineColor()](#getLineColor--) | Указывает цвет линии фигуры. |
| [getLineColorTrans()](#getLineColorTrans--) | Указывает уровень прозрачности цвета линии фигуры от 0 (непрозрачный) до 1 (полностью прозрачный). |
| [getLinePattern()](#getLinePattern--) | Указывает тип шаблона линии фигуры |
| [getLineWeight()](#getLineWeight--) | Указывает толщину линии фигуры. |
| [getRounding()](#getRounding--) | Указывает радиус закругляющей дуги, применяемой там, где два смежных сегмента пути соединяются. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | Для описания этого свойства см. [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | Для описания этого свойства см. [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | Для описания этого свойства см. [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | Для описания этого свойства см. [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | Для описания этого свойства см. [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | Для описания этого свойства см. [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | Для описания этого свойства см. [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | Для описания этого свойства см. [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Указывает, имеет ли линия наконечник‑стрелка или иной формат конца линии в своей первой вершине. Введите число от 0 до 45 или функцию USE с именем пользовательского конца линии.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Определяет размер наконечника стрелки в начале линии. Введите число от 0 до 6.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


Указывает тип составной линии CompoundType фигуры.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Указывает, имеет ли линия наконечник‑стрелка или иной формат конца линии в своей последней вершине.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Указывает размер наконечника‑стрелки в конце линии.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Содержит текущие значения форматирования градиентной линии для фигуры

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Указывает, имеет ли линия закруглённые или квадратные концы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Указывает цвет линии фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Указывает уровень прозрачности цвета линии фигуры, от 0 (непрозрачный) до 1 (полностью прозрачный). По умолчанию 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Указывает тип шаблона линии фигуры

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Указывает толщину линии фигуры. Толщина линии не зависит от масштаба чертежа. При масштабировании чертежа толщина линии остаётся прежней.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Указывает радиус скругляющей дуги, применяемой там, где встречаются два смежных сегмента пути. Например, скругление можно использовать для создания у прямоугольника скруглённых углов.

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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


Для описания этого свойства см. [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


Для описания этого свойства см. [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


Для описания этого свойства см. [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


Для описания этого свойства см. [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


Для описания этого свойства см. [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


Для описания этого свойства см. [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


Для описания этого свойства см. [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


Для описания этого свойства см. [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


Для описания этого свойства см. [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


Для описания этого свойства см. [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


Для описания этого свойства см. [getRounding()](../../com.aspose.diagram/line\#getRounding--)

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

