---
title: Свойство
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы для определения пользовательских свойств и элементы для связывания данных с фигурой.
type: docs
weight: 309
url: /ru/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Содержит элементы для определения пользовательских свойств и элементы для связывания данных с фигурой.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Prop()](#Prop--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Определяет календарь, используемый для пользовательских свойств, текстовых полей и формул элементов. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getFormat()](#getFormat--) | Элемент Format указывает форматирование пользовательского свойства, которое является строкой, фиксированным списком, числом, переменным списком, датой или временем, длительностью или валютой. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getInvisible()](#getInvisible--) | Элемент Invisible указывает, видимо ли пользовательское свойство в диалоговом окне Пользовательские свойства в Microsoft Visio. |
| [getLabel()](#getLabel--) | Указывает метку, отображаемую пользователям в диалоговом окне Пользовательские свойства. |
| [getLangID()](#getLangID--) | Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getPrompt()](#getPrompt--) | Элемент Prompt указывает описательный или инструктивный текст, отображаемый пользователям в диалоговом окне Пользовательские свойства при выборе свойства. |
| [getSortKey()](#getSortKey--) | Он указывает ключ, определяющий порядок, в котором пользовательские свойства перечисляются в пользовательском интерфейсе приложения. |
| [getType()](#getType--) | Тип указывает тип данных для значения пользовательского свойства. |
| [getValue()](#getValue--) | Содержит специфичные для решения, корректно сформированные XML-данные, которые имеют префикс в явном пространстве имён и хранятся вместе с документом. |
| [getVerify()](#getVerify--) | Указывает, запрашивается ли у пользователя ввод информации о пользовательском свойстве для фигуры при создании экземпляра или при дублировании или копировании фигуры. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства см. [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства см. [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства см. [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Конструктор.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Создаёт глубокую копию этого экземпляра.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Элемент Format указывает форматирование пользовательского свойства, которое может быть строкой, фиксированным списком, числом, переменным списком, датой или временем, длительностью или валютой. Тип пользовательского свойства задаётся в соответствующем элементе Type.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Элемент Invisible указывает, видимо ли пользовательское свойство в диалоговом окне Пользовательские свойства в Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Указывает метку, отображаемую пользователям в диалоговом окне Пользовательские свойства.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Элемент Prompt задаёт описательный или инструктивный текст, который отображается пользователям в диалоговом окне Пользовательские свойства при выборе свойства. Этот текст также появляется как всплывающая подсказка, когда указатель мыши задерживается над свойством в окне Пользовательские свойства.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Он указывает ключ, определяющий порядок, в котором пользовательские свойства перечисляются в пользовательском интерфейсе приложения.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Тип указывает тип данных для значения пользовательского свойства.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Содержит специфичные для решения, корректно сформированные XML-данные, которые имеют префикс в явном пространстве имён и хранятся вместе с документом.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Указывает, запрашивается ли у пользователя ввод информации о пользовательском свойстве для фигуры при создании экземпляра или при дублировании или копировании фигуры.

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


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства см. [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства см. [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства см. [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

