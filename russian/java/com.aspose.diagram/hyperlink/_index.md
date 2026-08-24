---
title: Hyperlink
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы для создания нескольких переходов между фигурой или страницей чертежа и другой страницей чертежа, другим файлом или веб‑сайтом.
type: docs
weight: 193
url: /ru/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Содержит элементы для создания нескольких переходов между фигурой или страницей чертежа и другой страницей чертежа, другим файлом или веб‑сайтом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Указывает URL‑адрес, имя файла DOS или UNC‑путь для перехода. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Указывает гиперссылку по умолчанию для фигуры или страницы. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDescription()](#getDescription--) | Элемент Description содержит текстовую строку, описывающую гиперссылку. |
| [getExtraInfo()](#getExtraInfo--) | Содержит информацию, используемую для разрешения URL, например координаты карты изображения. |
| [getFrame()](#getFrame--) | Содержит имя кадра, на который следует перейти, когда Microsoft Visio открывается как активный документ в контейнерном приложении. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getInvisible()](#getInvisible--) | Невидимый элемент указывает, появляется ли гиперссылка в контекстном меню для фигуры или страницы. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getNewWindow()](#getNewWindow--) | Указывает, открывает ли Microsoft Visio окно в новом месте при переходе по гиперссылке для открытия веб‑страницы или другого документа Visio. |
| [getSortKey()](#getSortKey--) | Невидимый элемент указывает, появляется ли гиперссылка в контекстном меню для фигуры или страницы. |
| [getSubAddress()](#getSubAddress--) | Указывает место в целевом документе, на которое следует перейти. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Указывает URL‑адрес, имя файла DOS или UNC‑путь для перехода.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Указывает гиперссылку по умолчанию для фигуры или страницы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Элемент Description содержит текстовую строку, описывающую гиперссылку.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Содержит информацию, используемую для разрешения URL, например координаты карты изображения. Например, x=41 y=7 указывает координаты карты изображения.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Содержит имя кадра, на который следует перейти, когда Microsoft Visio открывается как активный документ в контейнерном приложении. По умолчанию это пустая строка.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Невидимый элемент указывает, появляется ли гиперссылка в контекстном меню для фигуры или страницы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Указывает, открывает ли Microsoft Visio окно в новом месте при переходе по гиперссылке для открытия веб‑страницы или другого документа Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Невидимый элемент указывает, появляется ли гиперссылка в контекстном меню для фигуры или страницы.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Указывает место в целевом документе, на которое следует перейти.

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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

