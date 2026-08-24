---
title: Группа
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, которые управляют тем, как вы добавляете фигуры в группу, перемещаете участников группы и выбираете группы.
type: docs
weight: 186
url: /ru/java/com.aspose.diagram/group/
---

**Inheritance:**
java.lang.Object
```
public class Group
```

Содержит элементы, управляющие тем, как добавлять фигуры в группу, перемещать её участников и выбирать группы.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDisplayMode()](#getDisplayMode--) | Когда он находится внутри элемента Group, элемент DisplayMode определяет, как отображается групповая фигура и её элементы. |
| [getDontMoveChildren()](#getDontMoveChildren--) | Указывает, можете ли вы перетаскивать фигуры в группе с помощью мыши. |
| [getSelectMode()](#getSelectMode--) | Указывает, как пользователь выбирает группу фигур и её элементы. |
| [hashCode()](#hashCode--) |  |
| [isDropTarget()](#isDropTarget--) | Указывает, позволяет ли группа добавить в неё фигуру, когда фигура бросается на группу. |
| [isSnapTarget()](#isSnapTarget--) | Указывает, включено ли привязывание к группе или к фигурам внутри группы. |
| [isTextEditTarget()](#isTextEditTarget--) | Указывает, как назначать текст группе. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/group\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDisplayMode() {#getDisplayMode--}
```
public DisplayMode getDisplayMode()
```


Когда он находится внутри элемента Group, элемент DisplayMode определяет, как отображается групповая фигура и её элементы.

**Returns:**
[DisplayMode](../../com.aspose.diagram/displaymode)
### getDontMoveChildren() {#getDontMoveChildren--}
```
public BoolValue getDontMoveChildren()
```


Указывает, можете ли вы перетаскивать фигуры в группе с помощью мыши.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSelectMode() {#getSelectMode--}
```
public SelectMode getSelectMode()
```


Указывает, как пользователь выбирает группу фигур и её элементы.

**Returns:**
[SelectMode](../../com.aspose.diagram/selectmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropTarget() {#isDropTarget--}
```
public BoolValue isDropTarget()
```


Указывает, позволяет ли группа добавить в неё фигуру, когда фигура бросается на группу.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isSnapTarget() {#isSnapTarget--}
```
public BoolValue isSnapTarget()
```


Указывает, включено ли привязывание к группе или к фигурам внутри группы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isTextEditTarget() {#isTextEditTarget--}
```
public BoolValue isTextEditTarget()
```


Указывает, как назначать текст группе.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/group\#getDel--)

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

