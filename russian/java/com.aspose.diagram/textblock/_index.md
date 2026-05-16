---
title: TextBlock
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, которые задают поля выравнивания и позиции табуляции по умолчанию текста в текстовом блоке фигуры.
type: docs
weight: 400
url: /ru/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

Содержит элементы, указывающие выравнивание, отступы и позиции табуляции по умолчанию текста в текстовом блоке фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Определяет расстояние между нижней границей текстового блока и последней строкой содержащегося в нём текста. |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | Указывает интервал табуляций по умолчанию в текстовом блоке. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getLeftMargin()](#getLeftMargin--) | Указывает расстояние между левой границей текстового блока и содержащимся в нём текстом. |
| [getRightMargin()](#getRightMargin--) | Указывает расстояние между правой границей текстового блока и содержащимся в нём текстом. |
| [getTextBkgnd()](#getTextBkgnd--) | Указывает цвет фона текста для фигуры. |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | Указывает уровень прозрачности цвета фона текстового блока фигуры, от 0 (полностью непрозрачно) до 1 (полностью прозрачно). |
| [getTextDirection()](#getTextDirection--) | Указывает направление символов в текстовом блоке. |
| [getTopMargin()](#getTopMargin--) | Указывает расстояние между верхней границей текстового блока и первой строкой содержащегося в нём текста. |
| [getVerticalAlign()](#getVerticalAlign--) | Указывает вертикальное выравнивание текста внутри текстового блока. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/textblock\#getDel--) |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | Для описания этого свойства, пожалуйста, см. [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | Для описания этого свойства, пожалуйста, см. [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, см. [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | Для описания этого свойства, пожалуйста, см. [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


Определяет расстояние между нижней границей текстового блока и последней строкой текста, которую он содержит. По умолчанию 4 пт. Это значение не зависит от масштаба чертежа. Если чертеж масштабируется, нижний отступ остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


Указывает интервал табуляций по умолчанию в текстовом блоке.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


Указывает расстояние между левой границей текстового блока и содержащимся в нём текстом. Это значение не зависит от масштаба чертежа. Если чертеж масштабируется, левый отступ остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


Указывает расстояние между правой границей текстового блока и содержащимся в нём текстом. Это значение не зависит от масштаба чертежа. Если чертеж масштабируется, правый отступ остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


Указывает цвет фона текста для фигуры.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


Указывает уровень прозрачности цвета фона текстового блока фигуры, от 0 (полностью непрозрачно) до 1 (полностью прозрачно).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


Указывает направление символов в текстовом блоке.

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


Указывает расстояние между верхней границей текстового блока и первой строкой содержащегося в нём текста.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


Указывает вертикальное выравнивание текста внутри текстового блока.

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/textblock\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


Для описания этого свойства, пожалуйста, см. [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


Для описания этого свойства, пожалуйста, см. [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


Для описания этого свойства, пожалуйста, см. [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


Для описания этого свойства, пожалуйста, см. [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

