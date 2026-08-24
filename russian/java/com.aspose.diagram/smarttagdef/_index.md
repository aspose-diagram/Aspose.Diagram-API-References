---
title: SmartTagDef
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, содержащие информацию для каждой умной метки, определённой для фигуры или страницы.
type: docs
weight: 374
url: /ru/java/com.aspose.diagram/smarttagdef/
---

**Inheritance:**
java.lang.Object
```
public class SmartTagDef
```

Содержит элементы, содержащие информацию для каждой умной метки, определённой для фигуры или страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SmartTagDef()](#SmartTagDef--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getButtonFace()](#getButtonFace--) | Содержит идентификатор изображения лица кнопки, которое отображается на кнопке смарт‑тега. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDescription()](#getDescription--) | Элемент Description содержит строку, описывающую смарт‑тег, которая отображается как всплывающая подсказка, когда пользователь удерживает курсор мыши над тегом. |
| [getDisabled()](#getDisabled--) | Элемент Disabled определяет, отображается ли смарт‑тег в окне чертежа. |
| [getDisplayMode()](#getDisplayMode--) | Элемент DisplayMode определяет, появляется ли смарт‑тег, когда пользователь удерживает курсор мыши над тегом, когда фигура выбрана, или постоянно. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getTagName()](#getTagName--) | Содержит имя смарт‑тега, которое используется в качестве ключа для связывания смарт‑тега с его действиями. |
| [getX()](#getX--) | Позиция по оси x в локальных координатах фигуры, вокруг которой размещается кнопка смарт‑тега. |
| [getXJustify()](#getXJustify--) | Смещение по оси x кнопки смарт‑тега относительно точки, определенной элементами X и Y. |
| [getY()](#getY--) | Позиция по оси y в локальных координатах фигуры, вокруг которой размещается кнопка смарт‑тега. |
| [getYJustify()](#getYJustify--) | Указывает смещение по оси y кнопки смарт‑тега относительно точки, определенной элементами X и Y. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/smarttagdef\#getDel--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/smarttagdef\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/smarttagdef\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/smarttagdef\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartTagDef() {#SmartTagDef--}
```
public SmartTagDef()
```


Конструктор.

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
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Содержит идентификатор изображения лица кнопки, которое отображается на кнопке смарт‑тега.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Элемент Description содержит строку, описывающую смарт‑тег, которая отображается как всплывающая подсказка, когда пользователь удерживает курсор мыши над тегом.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Элемент Disabled определяет, отображается ли смарт‑тег в окне чертежа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDisplayMode() {#getDisplayMode--}
```
public DisplayModeSmartTagDef getDisplayMode()
```


Элемент DisplayMode определяет, появляется ли смарт‑тег, когда пользователь удерживает курсор мыши над тегом, когда фигура выбрана, или постоянно.

**Returns:**
[DisplayModeSmartTagDef](../../com.aspose.diagram/displaymodesmarttagdef)
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Имя элемента.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Универсальное имя элемента.

**Returns:**
java.lang.String
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Содержит имя смарт‑тега, которое используется в качестве ключа для связывания смарт‑тега с его действиями.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


Позиция по оси x в локальных координатах фигуры, вокруг которой размещается кнопка смарт‑тега.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXJustify() {#getXJustify--}
```
public XJustify getXJustify()
```


Смещение по оси x кнопки смарт‑тега относительно точки, определенной элементами X и Y.

**Returns:**
[XJustify](../../com.aspose.diagram/xjustify)
### getY() {#getY--}
```
public DoubleValue getY()
```


Позиция по оси y в локальных координатах фигуры, вокруг которой размещается кнопка смарт‑тега.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYJustify() {#getYJustify--}
```
public YJustify getYJustify()
```


Указывает смещение по оси y кнопки смарт‑тега относительно точки, определенной элементами X и Y.

**Returns:**
[YJustify](../../com.aspose.diagram/yjustify)
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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/smarttagdef\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/smarttagdef\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/smarttagdef\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/smarttagdef\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

