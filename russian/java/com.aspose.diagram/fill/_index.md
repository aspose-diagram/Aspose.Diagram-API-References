---
title: Заполнение
second_title: Справочник API Aspose.Diagram for Java
description: Содержит текущие значения форматирования заливки для фигуры и её теневой заливки, включая цвет переднего плана шаблона и цвет фона.
type: docs
weight: 153
url: /ru/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

Содержит текущие значения форматирования заливки для фигуры и её тени, включая шаблон, цвет переднего плана и цвет фона.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getFillBkgnd()](#getFillBkgnd--) | Указывает цвет, используемый для фона шаблона заливки фигуры. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | Указывает уровень прозрачности фонового (заливочного) цвета шаблона заливки фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный). |
| [getFillForegnd()](#getFillForegnd--) | Указывает цвет, используемый для переднего плана (обводки) шаблона заливки фигуры. |
| [getFillForegndTrans()](#getFillForegndTrans--) | Указывает уровень прозрачности переднего плана (заливочного) цвета шаблона заливки фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный). |
| [getFillPattern()](#getFillPattern--) | Указывает шаблон заливки для фигуры. |
| [getGradientFill()](#getGradientFill--) | Содержит текущие значения форматирования градиентной заливки для фигуры |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | Указывает размер размытия тени фигуры. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | Указывает угол наклонного направления тени фигуры. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | Определяет расстояние в единицах страницы, на которое тень фигуры смещена горизонтально от фигуры. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | Определяет расстояние в единицах страницы, на которое тень фигуры смещена вертикально от фигуры. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | Указывает процент, на который тень фигуры может быть увеличена или уменьшена. |
| [getShapeShdwShow()](#getShapeShdwShow--) | Указывает тип тени для фигуры. |
| [getShapeShdwType()](#getShapeShdwType--) | Указывает тип тени для фигуры. |
| [getShdwBkgnd()](#getShdwBkgnd--) | Указывает цвет, используемый для фона (заливки) шаблона теневой заливки фигуры. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | Указывает уровень прозрачности фона (заливки) шаблона теневой заливки фигуры, от 0.0 (полностью непрозрачный) до 1.0 (полностью прозрачный). |
| [getShdwForegnd()](#getShdwForegnd--) | Указывает цвет, используемый для переднего плана (обводки) шаблона теневой заливки фигуры. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | Указывает уровень прозрачности переднего плана (обводки) шаблона теневой заливки фигуры, от 0.0 (полностью непрозрачный) до 1.0 (полностью прозрачный). |
| [getShdwPattern()](#getShdwPattern--) | Указывает шаблон заливки для тени фигуры. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | Для описания этого свойства, пожалуйста, смотрите [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | Для описания этого свойства, пожалуйста, смотрите [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | Для описания этого свойства, пожалуйста, смотрите [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | Для описания этого свойства, пожалуйста, смотрите [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | Для описания этого свойства, пожалуйста, смотрите [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | Для описания этого свойства, пожалуйста, смотрите [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | Для описания этого свойства, пожалуйста, смотрите [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


Указывает цвет, используемый для фона шаблона заливки фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


Указывает уровень прозрачности фонового (заливочного) цвета шаблона заливки фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


Указывает цвет, используемый для переднего плана (обводки) шаблона заливки фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


Указывает уровень прозрачности переднего плана (заливочного) цвета шаблона заливки фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


Указывает шаблон заливки для фигуры.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Содержит текущие значения форматирования градиентной заливки для фигуры

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


Указывает размер размытия тени фигуры. Сейчас нельзя отрисовать размытие, но можно разобрать из vsdx.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


Указывает угол наклонного направления тени фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


Определяет расстояние в единицах страницы, на которое тень фигуры смещена горизонтально от фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


Определяет расстояние в единицах страницы, на которое тень фигуры смещена вертикально от фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


Указывает процент, на который тень фигуры может быть увеличена или уменьшена.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


Указывает тип тени для фигуры.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


Указывает тип тени для фигуры.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


Указывает цвет, используемый для фона (заливки) шаблона теневой заливки фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


Указывает уровень прозрачности фона (заливки) шаблона теневой заливки фигуры, от 0.0 (полностью непрозрачный) до 1.0 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


Указывает цвет, используемый для переднего плана (обводки) шаблона теневой заливки фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


Указывает уровень прозрачности переднего плана (обводки) шаблона теневой заливки фигуры, от 0.0 (полностью непрозрачный) до 1.0 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


Указывает шаблон заливки для тени фигуры.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

