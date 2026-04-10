---
title: ConValue
second_title: Aspose.Diagram for Java API 参考
description: 指定控制柄移动后，其 x 或 y 坐标的行为类型。
type: docs
weight: 74
url: /zh/java/com.aspose.diagram/convalue/
---

**Inheritance:**
java.lang.Object
```
public final class ConValue
```

指定控制柄移动后，其 x 或 y 坐标的行为类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [OFFSET_FROM_CENTER](#OFFSET-FROM-CENTER) | 相对于中心的偏移。 |
| [OFFSET_FROM_CENTER_HIDDEN](#OFFSET-FROM-CENTER-HIDDEN) | 相对于中心的偏移，隐藏。 |
| [OFFSET_FROM_LEFT_EDGE](#OFFSET-FROM-LEFT-EDGE) | 相对于左边缘的偏移。 |
| [OFFSET_FROM_LEFT_EDGE_HIDDEN](#OFFSET-FROM-LEFT-EDGE-HIDDEN) | 相对于左边缘的偏移，隐藏。 |
| [OFFSET_FROM_RIGHT_EDGE](#OFFSET-FROM-RIGHT-EDGE) | 相对于右边缘的偏移。 |
| [OFFSET_FROM_RIGHT_EDGE_HIDDEN](#OFFSET-FROM-RIGHT-EDGE-HIDDEN) | 从右边缘偏移，隐藏。 |
| [PROPORTIONAL](#PROPORTIONAL) | 比例。 |
| [PROPORTIONAL_HIDDEN](#PROPORTIONAL-HIDDEN) | 比例，隐藏。与 0 相同，但控制手柄不可见。 |
| [PROPORTIONAL_LOCKED](#PROPORTIONAL-LOCKED) | 比例锁定。 |
| [PROPORTIONAL_LOCKED_HIDDEN](#PROPORTIONAL-LOCKED-HIDDEN) | 比例锁定，隐藏。 |
| [UNDEFINED](#UNDEFINED) | 未定义。 |
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
### OFFSET_FROM_CENTER {#OFFSET-FROM-CENTER}
```
public static final int OFFSET_FROM_CENTER
```


从中心偏移。控制手柄相对于形状中心保持固定距离偏移。

### OFFSET_FROM_CENTER_HIDDEN {#OFFSET-FROM-CENTER-HIDDEN}
```
public static final int OFFSET_FROM_CENTER_HIDDEN
```


从中心偏移，隐藏。与 3 相同，但控制手柄不可见。

### OFFSET_FROM_LEFT_EDGE {#OFFSET-FROM-LEFT-EDGE}
```
public static final int OFFSET_FROM_LEFT_EDGE
```


从左边缘偏移。控制手柄相对于形状左侧保持固定距离偏移。

### OFFSET_FROM_LEFT_EDGE_HIDDEN {#OFFSET-FROM-LEFT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_LEFT_EDGE_HIDDEN
```


从左边缘偏移，隐藏。与 2 相同，但控制手柄不可见。

### OFFSET_FROM_RIGHT_EDGE {#OFFSET-FROM-RIGHT-EDGE}
```
public static final int OFFSET_FROM_RIGHT_EDGE
```


从右边缘偏移。控制手柄相对于形状右侧保持固定距离偏移。

### OFFSET_FROM_RIGHT_EDGE_HIDDEN {#OFFSET-FROM-RIGHT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_RIGHT_EDGE_HIDDEN
```


从右边缘偏移，隐藏。与 4 相同，但控制手柄不可见。

### PROPORTIONAL {#PROPORTIONAL}
```
public static final int PROPORTIONAL
```


比例。控制手柄可以移动，并且在形状拉伸时按比例移动。

### PROPORTIONAL_HIDDEN {#PROPORTIONAL-HIDDEN}
```
public static final int PROPORTIONAL_HIDDEN
```


比例，隐藏。与 0 相同，但控制手柄不可见。

### PROPORTIONAL_LOCKED {#PROPORTIONAL-LOCKED}
```
public static final int PROPORTIONAL_LOCKED
```


比例锁定。控制手柄随形状按比例移动，但手柄本身不可移动。

### PROPORTIONAL_LOCKED_HIDDEN {#PROPORTIONAL-LOCKED-HIDDEN}
```
public static final int PROPORTIONAL_LOCKED_HIDDEN
```


比例锁定，隐藏。与 1 相同，但控制手柄不可见。

### UNDEFINED {#UNDEFINED}
```
public static final int UNDEFINED
```


未定义。

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

