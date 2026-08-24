---
title: Act
second_title: Справочник API Aspose.Diagram for Java
description: Определяет пользовательские имена команд, которые отображаются в контекстном меню объекта, и указывает действия, выполняемые этими командами.
type: docs
weight: 11
url: /ru/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Определяет пользовательские имена команд, которые отображаются в контекстном меню объекта, и указывает действия, которые выполняют команды.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Act()](#Act--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Содержит формулу, которая выполняется, когда пользователь нажимает имя команды, определённое в соответствующем элементе Menu. |
| [getBeginGroup()](#getBeginGroup--) | Указывает, вставлен ли разделитель в меню над этим действием. |
| [getButtonFace()](#getButtonFace--) | Определяет значок, который отображается рядом с элементом в контекстном меню. |
| [getChecked()](#getChecked--) | Определяет, отображается ли галочка рядом с именем команды в контекстном меню фигуры. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDisabled()](#getDisabled--) | Элемент Disabled определяет, отображается ли имя команды в контекстном меню. |
| [getFlyoutChild()](#getFlyoutChild--) | Определяет, является ли строка действия дочерним выпадающим меню последней строки выше неё, которая не является дочерним выпадающим элементом. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getInvisible()](#getInvisible--) | Элемент Invisible указывает, видимо ли действие в смарт‑теге или контекстном меню. |
| [getMenu()](#getMenu--) | Задаёт имя команды, отображаемой в контекстном меню для фигуры или страницы. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getReadOnly()](#getReadOnly--) | Определяет, является ли действие в смарт‑теге или контекстном меню только для чтения. |
| [getSortKey()](#getSortKey--) | Указывает число, определяющее порядок действий, отображаемых в контекстном меню или меню смарт‑тега. |
| [getTagName()](#getTagName--) | It содержит имя смарт‑тега, с которым связано действие. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Содержит формулу, которая выполняется, когда пользователь нажимает имя команды, определённое в соответствующем элементе Menu.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Указывает, вставлен ли разделитель в меню над этим действием.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Определяет значок, который отображается рядом с элементом в контекстном меню.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Определяет, отображается ли галочка рядом с именем команды в контекстном меню фигуры.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Элемент Disabled определяет, отображается ли имя команды в контекстном меню.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Определяет, является ли строка действия дочерним выпадающим меню последней строки выше неё, которая не является дочерним выпадающим элементом.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Элемент Invisible указывает, видимо ли действие в смарт‑теге или контекстном меню.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Задаёт имя команды, отображаемой в контекстном меню для фигуры или страницы.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Определяет, является ли действие в смарт‑теге или контекстном меню только для чтения.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Указывает число, определяющее порядок действий, отображаемых в контекстном меню или меню смарт‑тега.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


It содержит имя смарт‑тега, с которым связано действие.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, см. [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/act\#getNameU--)

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

