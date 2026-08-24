---
title: GluedShapesFlags
second_title: Справочник API Aspose.Diagram for Java
description: Указывает константы, определяющие, какие фигуры возвращать, исходя из размерности и направленности точек соединения, приклеенных к конкретной фигуре, переданной в метод Shape.GluedShapes.
type: docs
weight: 176
url: /ru/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

Указывает константы, определяющие, какие фигуры возвращать, исходя из размерности и направленности точек соединения, привязанных к конкретной фигуре; передаётся методу Shape.GluedShapes.
## Поля

| Поле | Описание |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | Вернуть идентификаторы всех 1‑D фигур, приклеенных к этой фигуре. |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | Вернуть все 2‑D фигуры, приклеенные к этой фигуре, и все 2‑D фигуры, к которым эта фигура приклеена. |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | Вернуть идентификаторы 1‑D фигур, концевые точки которых приклеены к этой фигуре. |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | Если исходный объект является 1‑D фигурой, вернуть идентификаторы 2‑D фигур, к которым приклеена начальная точка. |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | Верните идентификаторы 1‑D фигур, чьи начальные точки приклеены к этой фигуре. |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | Если исходный объект является 1‑D фигурой, верните идентификаторы 2‑D фигуры, к которой приклеена конечная точка. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLUED_SHAPES_ALL_1_D {#GLUED-SHAPES-ALL-1-D}
```
public static final int GLUED_SHAPES_ALL_1_D
```


Вернуть идентификаторы всех 1‑D фигур, приклеенных к этой фигуре.

### GLUED_SHAPES_ALL_2_D {#GLUED-SHAPES-ALL-2-D}
```
public static final int GLUED_SHAPES_ALL_2_D
```


Вернуть все 2‑D фигуры, приклеенные к этой фигуре, и все 2‑D фигуры, к которым эта фигура приклеена.

### GLUED_SHAPES_INCOMING_1_D {#GLUED-SHAPES-INCOMING-1-D}
```
public static final int GLUED_SHAPES_INCOMING_1_D
```


Вернуть идентификаторы 1‑D фигур, концевые точки которых приклеены к этой фигуре.

### GLUED_SHAPES_INCOMING_2_D {#GLUED-SHAPES-INCOMING-2-D}
```
public static final int GLUED_SHAPES_INCOMING_2_D
```


Если исходный объект является 1‑D фигурой, верните идентификаторы 2‑D фигуры, к которой приклеена начальная точка. Если исходный объект является 2‑D фигурой, верните идентификаторы 2‑D фигур, приклеенных к этой фигуре.

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


Верните идентификаторы 1‑D фигур, чьи начальные точки приклеены к этой фигуре.

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


Если исходный объект является 1‑D фигурой, верните идентификаторы 2‑D фигуры, к которой приклеена конечная точка. Если исходный объект является 2‑D фигурой, верните идентификаторы 2‑D фигур, к которым приклеена эта фигура.

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

