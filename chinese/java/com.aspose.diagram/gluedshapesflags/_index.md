---
title: GluedShapesFlags
second_title: Aspose.Diagram for Java API 参考
description: 指定常量，这些常量根据粘贴到传递给 Shape.GluedShapes 方法的特定形状的连接点的维度和方向性来标识要返回的形状。
type: docs
weight: 176
url: /zh/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

指定用于标识应返回哪些形状的常量，依据粘连到特定形状的连接点的维度和方向性；传递给 Shape.GluedShapes 方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | 返回粘贴到此形状的所有 1-D 形状的 ID。 |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | 返回粘贴到此形状的所有 2-D 形状以及此形状粘贴到的所有 2-D 形状。 |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | 返回端点粘贴到此形状的 1-D 形状的 ID。 |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | 如果源对象是 1-D 形状，则返回起始点粘贴到的 2-D 形状的 ID。 |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | 返回其起点粘附到此形状的 1-D 形状的 ID。 |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | 如果源对象是 1-D 形状，返回其终点粘附的 2-D 形状的 ID。 |
## 方法

| 方法 | 描述 |
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


返回粘贴到此形状的所有 1-D 形状的 ID。

### GLUED_SHAPES_ALL_2_D {#GLUED-SHAPES-ALL-2-D}
```
public static final int GLUED_SHAPES_ALL_2_D
```


返回粘贴到此形状的所有 2-D 形状以及此形状粘贴到的所有 2-D 形状。

### GLUED_SHAPES_INCOMING_1_D {#GLUED-SHAPES-INCOMING-1-D}
```
public static final int GLUED_SHAPES_INCOMING_1_D
```


返回端点粘贴到此形状的 1-D 形状的 ID。

### GLUED_SHAPES_INCOMING_2_D {#GLUED-SHAPES-INCOMING-2-D}
```
public static final int GLUED_SHAPES_INCOMING_2_D
```


如果源对象是 1-D 形状，返回其起点粘附的 2-D 形状的 ID。如果源对象是 2-D 形状，返回粘附到此形状的 2-D 形状的 ID。

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


返回其起点粘附到此形状的 1-D 形状的 ID。

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


如果源对象是 1-D 形状，返回其终点粘附的 2-D 形状的 ID。如果源对象是 2-D 形状，返回此形状粘附的 2-D 形状的 ID。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

