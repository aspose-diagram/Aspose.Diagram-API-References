---
title: Master
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, определяющие мастер для документа.
type: docs
weight: 240
url: /ru/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Содержит элементы, определяющие master для документа. Master — это фигура на шаблоне, которую вы используете многократно для создания чертежей. Когда вы перетаскиваете фигуру из шаблона на страницу чертежа, фигура становится экземпляром этого master, и локальная копия master включается в документ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Master()](#Master--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Указывает, выравнивается ли текст master в окне шаблона слева, справа или по центру. |
| [getBaseID()](#getBaseID--) | GUID (глобальный уникальный идентификатор), который идентифицирует master в разных документах. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Содержит элемент Connect для каждого соединения между двумя фигурами в чертеже. |
| [getHidden()](#getHidden--) | Указывает, скрыт ли master в пользовательском интерфейсе. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getIcon()](#getIcon--) | Указывает MIME (Multipurpose Internet Mail Extensions) закодированную бинарную иконку (в формате .ico) для элемента Master или MasterShortcut в документе. |
| [getIconSize()](#getIconSize--) | Размер иконки элемента. |
| [getIconUpdate()](#getIconUpdate--) | Указывает, генерируется ли иконка автоматически из самого master. |
| [getMatchByName()](#getMatchByName--) | Атрибут MatchByName определяет, как Microsoft Visio решает, присутствует ли master документа, когда экземпляр master помещается на страницу чертежа. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getPageSheet()](#getPageSheet--) | Содержит элементы, определяющие лист страницы для элемента Page или Master. |
| [getPatternFlags()](#getPatternFlags--) | Атрибут PatternFlags определяет, ведёт ли мастер себя как пользовательский шаблон. |
| [getPrompt()](#getPrompt--) | Строка состояния и всплывающая подсказка для элемента. |
| [getShapes()](#getShapes--) | Коллекция объектов Shape. |
| [getUniqueID()](#getUniqueID--) | GUID, идентифицирующий мастер в документе. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Для описания этого свойства см. [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Для описания этого свойства см. [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Для описания этого свойства см. [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства см. [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Для описания этого свойства см. [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Для описания этого свойства см. [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Для описания этого свойства см. [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Для описания этого свойства см. [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства см. [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства см. [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Для описания этого свойства см. [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Для описания этого свойства см. [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Для описания этого свойства см. [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Конструктор.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт глубокую копию этого экземпляра.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Указывает, выравнивается ли текст master в окне шаблона слева, справа или по центру.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


GUID (глобальный уникальный идентификатор), который идентифицирует master в разных документах.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Содержит элемент Connect для каждого соединения между двумя фигурами в чертеже.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Указывает, скрыт ли master в пользовательском интерфейсе.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Указывает MIME (Multipurpose Internet Mail Extensions) закодированную бинарную иконку (в формате .ico) для элемента Master или MasterShortcut в документе.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


Размер иконки элемента.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Указывает, генерируется ли иконка автоматически из самого master.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


Атрибут MatchByName определяет, как Microsoft Visio решает, присутствует ли уже мастер документа, когда экземпляр мастера помещается на страницу чертежа. Он позволяет изменениям, внесённым в мастер документа, применяться к новым экземплярам мастера, даже если экземпляры перетаскиваются из отдельного файла шаблона.

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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Содержит элементы, определяющие лист страницы для элемента Page или Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


Атрибут PatternFlags определяет, ведёт ли мастер себя как пользовательский шаблон.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


Строка состояния и всплывающая подсказка для элемента.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Коллекция объектов Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID, идентифицирующий мастер в документе.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Для описания этого свойства см. [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Для описания этого свойства см. [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Для описания этого свойства см. [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства см. [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Для описания этого свойства см. [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Для описания этого свойства см. [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Для описания этого свойства см. [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Для описания этого свойства см. [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства см. [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства см. [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Для описания этого свойства см. [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Для описания этого свойства см. [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Для описания этого свойства см. [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

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

