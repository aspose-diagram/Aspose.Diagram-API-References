---
title: Layer
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, определяющие один слой и его свойства для страницы.
type: docs
weight: 212
url: /ru/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Содержит элементы, определяющие один слой и его свойства для страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Layer()](#Layer--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Указывает, активен ли слой. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Индекс цвета в таблице цветов, используемый для отображения слоя, или значение RGB, указывающее пользовательский цвет, отсутствующий в таблице цветов (например, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Определяет степень прозрачности цвета текста слоя или фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный). |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getGlue()](#getGlue--) | Указывает, могут ли фигуры, принадлежащие слою, быть приклеены. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getLock()](#getLock--) | Указывает, заблокированы ли фигуры, принадлежащие слою, от выбора или редактирования. |
| [getName()](#getName--) | Элемент Name указывает имя слоя. |
| [getNameUniv()](#getNameUniv--) | Указывает универсальное имя слоя. |
| [getPrint()](#getPrint--) | Указывает, печатаются ли фигуры, принадлежащие слою, при печати чертежа. |
| [getSnap()](#getSnap--) | Указывает, могут ли другие фигуры привязываться к фигурам, назначенным слою. |
| [getStatus()](#getStatus--) | Указывает, является ли слой допустимым слоем для документа. |
| [getVisible()](#getVisible--) | Указывает, видимы ли фигуры, принадлежащие слою, на странице чертежа. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Флаг, указывающий, был ли элемент проверен локально. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Для описания этого свойства см. [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства см. [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Указывает, активен ли слой. Фигуры, не предопределённые слоям, назначаются активному(ым) слою(ам) при размещении на странице чертежа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Индекс цвета в таблице цветов, используемый для отображения слоя, или значение RGB, указывающее пользовательский цвет, отсутствующий в таблице цветов (например, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Определяет степень прозрачности цвета текста слоя или фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Указывает, могут ли фигуры, принадлежащие слою, быть приклеены.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Указывает, заблокированы ли фигуры, принадлежащие слою, от выбора или редактирования.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Элемент Name указывает имя слоя.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Указывает универсальное имя слоя.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Указывает, печатаются ли фигуры, принадлежащие слою, при печати чертежа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Указывает, могут ли другие фигуры привязываться к фигурам, назначенным слою. Фигуры, назначенные слою, могут привязываться к другим фигурам, но другие фигуры не могут привязываться к ним.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Указывает, является ли слой допустимым слоем для документа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Указывает, видимы ли фигуры, принадлежащие слою, на странице чертежа.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Флаг, указывающий, был ли элемент проверен локально. Значение 1 указывает, что элемент был проверен локально.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Для описания этого свойства см. [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства см. [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

