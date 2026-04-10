---
title: Connection
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы для одной точки соединения, определенной для фигуры.
type: docs
weight: 78
url: /ru/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

Содержит элементы для одной точки соединения, определенной для фигуры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Connection()](#Connection--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | Указывает, генерируется ли точка соединения автоматически. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDirX()](#getDirX--) | Указывает x‑компонент требуемого вектора выравнивания соответствующей точки соединения. |
| [getDirY()](#getDirY--) | Указывает y‑компонент требуемого вектора выравнивания соответствующей точки соединения. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getPrompt()](#getPrompt--) | Содержит различную подсказочную информацию в зависимости от элемента, в котором он находится. |
| [getType()](#getType--) | Указывает различные типы в зависимости от элемента, в котором он содержится. |
| [getX()](#getX--) | Указывает координату x на фигуре в локальных координатах. |
| [getY()](#getY--) | Указывает координату y на фигуре в локальных координатах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


Указывает, генерируется ли точка соединения автоматически. Значение 1 указывает, что точка соединения генерируется автоматически.

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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


Указывает x‑компонент требуемого вектора выравнивания соответствующей точки соединения. Элемент DirX также используется для ориентации присоединённой части динамического соединителя.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


Указывает y‑компонент требуемого вектора выравнивания соответствующей точки соединения. Элемент DirY также используется для ориентации присоединённой части динамического соединителя.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Содержит различную подсказочную информацию в зависимости от элемента, в котором он находится.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


Указывает различные типы в зависимости от элемента, в котором он содержится.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


Указывает координату x на фигуре в локальных координатах.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Указывает координату y на фигуре в локальных координатах. Локальные координаты — это координаты, чья система отсчёта привязана к фигуре, а не к странице.

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


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

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

