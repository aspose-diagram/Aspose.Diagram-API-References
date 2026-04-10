---
title: Поле
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, указывающие функции и формулы, вставленные в текст фигур.
type: docs
weight: 147
url: /ru/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Содержит элементы, задающие функции и формулы, вставленные в текст фигуры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Field()](#Field--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Определяет календарь, используемый для пользовательских свойств, текстовых полей и формул элементов. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDisplayValue()](#getDisplayValue--) | Получает отформатированное строковое значение этого поля. |
| [getEditMode()](#getEditMode--) | Зарезервировано для будущего использования. |
| [getFormat()](#getFormat--) | Элемент Format задает форматирование текстового поля, которое является строкой, числом, датой или временем, длительностью или валютой. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getObjectKind()](#getObjectKind--) | Указывает тип текстового поля. |
| [getType()](#getType--) | Тип указывает тип данных для значения текстового поля. |
| [getUICat()](#getUICat--) | Указывает категорию вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000. |
| [getUICod()](#getUICod--) | Указывает код вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000. |
| [getUIFmt()](#getUIFmt--) | Указывает формат вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000. |
| [getValue()](#getValue--) | Содержит значение для текстового поля. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Определяет календарь, используемый для пользовательских свойств, текстовых полей и формул элементов.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Получает отформатированное строковое значение этого поля.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Зарезервировано для будущего использования.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Элемент Format указывает форматирование текстового поля, которое является строкой, числом, датой или временем, длительностью или валютой. Тип текстового поля указывается в соответствующем элементе Type.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Указывает тип текстового поля.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Тип указывает тип данных для значения текстового поля.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Указывает категорию вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Указывает код вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Указывает формат вставленного поля в версиях Microsoft Visio, предшествующих Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Содержит значение для текстового поля.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/field\#getIX--)

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

