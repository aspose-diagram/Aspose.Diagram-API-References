---
title: TextXForm
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, которые указывают информацию о позиционировании текстового блока фигуры.
type: docs
weight: 405
url: /ru/java/com.aspose.diagram/textxform/
---

**Inheritance:**
java.lang.Object
```
public class TextXForm
```

Содержит элементы, указывающие информацию о позиционировании текстового блока фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getTxtAngle()](#getTxtAngle--) | Указывает текущий угол поворота текстового блока относительно оси X фигуры. |
| [getTxtHeight()](#getTxtHeight--) | Указывает высоту текстового блока. |
| [getTxtLocPinX()](#getTxtLocPinX--) | Указывает координату X центра вращения текстового блока относительно его начала. |
| [getTxtLocPinY()](#getTxtLocPinY--) | Указывает координату Y центра вращения текстового блока относительно его начала. |
| [getTxtPinX()](#getTxtPinX--) | Указывает координату X центра вращения текстового блока относительно начала фигуры. |
| [getTxtPinY()](#getTxtPinY--) | Указывает координату Y центра вращения текстового блока относительно начала фигуры. |
| [getTxtWidth()](#getTxtWidth--) | Указывает ширину текстового блока. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/textxform\#getDel--) |
| [setTxtAngle(DoubleValue value)](#setTxtAngle-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--) |
| [setTxtHeight(DoubleValue value)](#setTxtHeight-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--) |
| [setTxtLocPinX(DoubleValue value)](#setTxtLocPinX-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--) |
| [setTxtLocPinY(DoubleValue value)](#setTxtLocPinY-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--) |
| [setTxtPinX(DoubleValue value)](#setTxtPinX-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--) |
| [setTxtPinY(DoubleValue value)](#setTxtPinY-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--) |
| [setTxtWidth(DoubleValue value)](#setTxtWidth-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--) |
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
### getTxtAngle() {#getTxtAngle--}
```
public DoubleValue getTxtAngle()
```


Указывает текущий угол поворота текстового блока относительно оси X фигуры. По умолчанию 0 градусов.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtHeight() {#getTxtHeight--}
```
public DoubleValue getTxtHeight()
```


Указывает высоту текстового блока. Формула по умолчанию, вычисляющая высоту фигуры, выглядит так: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinX() {#getTxtLocPinX--}
```
public DoubleValue getTxtLocPinX()
```


Указывает координату X центра вращения текстового блока относительно его начала. Формула по умолчанию, вычисляющая горизонтальный центр текстового блока, выглядит так: F="TxtWidth\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinY() {#getTxtLocPinY--}
```
public DoubleValue getTxtLocPinY()
```


Указывает координату Y центра вращения текстового блока относительно его начала. Формула по умолчанию, вычисляющая вертикальный центр текстового блока, выглядит так: F="TxtHeight\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinX() {#getTxtPinX--}
```
public DoubleValue getTxtPinX()
```


Указывает координату X центра вращения текстового блока относительно начала фигуры. Формула по умолчанию, вычисляющая горизонтальный центр фигуры, выглядит так: F="Width\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinY() {#getTxtPinY--}
```
public DoubleValue getTxtPinY()
```


Указывает координату Y центра вращения текстового блока относительно начала фигуры. Формула по умолчанию, вычисляющая вертикальный центр фигуры, выглядит так: F="Height\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtWidth() {#getTxtWidth--}
```
public DoubleValue getTxtWidth()
```


Указывает ширину текстового блока. Формула по умолчанию, вычисляющая ширину фигуры, выглядит так: F="Width\*1".

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


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/textxform\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTxtAngle(DoubleValue value) {#setTxtAngle-com.aspose.diagram.DoubleValue-}
```
public void setTxtAngle(DoubleValue value)
```


Для описания этого свойства см. [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtHeight(DoubleValue value) {#setTxtHeight-com.aspose.diagram.DoubleValue-}
```
public void setTxtHeight(DoubleValue value)
```


Для описания этого свойства см. [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinX(DoubleValue value) {#setTxtLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinX(DoubleValue value)
```


Для описания этого свойства см. [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinY(DoubleValue value) {#setTxtLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinY(DoubleValue value)
```


Для описания этого свойства см. [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinX(DoubleValue value) {#setTxtPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinX(DoubleValue value)
```


Для описания этого свойства см. [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinY(DoubleValue value) {#setTxtPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinY(DoubleValue value)
```


Для описания этого свойства см. [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtWidth(DoubleValue value) {#setTxtWidth-com.aspose.diagram.DoubleValue-}
```
public void setTxtWidth(DoubleValue value)
```


Для описания этого свойства см. [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--)

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

