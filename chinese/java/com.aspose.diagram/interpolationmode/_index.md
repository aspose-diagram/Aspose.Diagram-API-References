---
title: InterpolationMode
second_title: Aspose.Diagram for Java API 参考
description: InterpolationMode 枚举指定在对图像进行缩放或旋转时使用的算法。
type: docs
weight: 206
url: /zh/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

InterpolationMode 枚举指定在对图像进行缩放或旋转时使用的算法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BICUBIC](#BICUBIC) | 指定双三次插值。 |
| [BILINEAR](#BILINEAR) | 指定双线性插值。 |
| [DEFAULT](#DEFAULT) | 指定默认模式。 |
| [HIGH](#HIGH) | 指定高质量插值。 |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | 指定高质量、双三次插值。 |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | 指定高质量、双线性插值。 |
| [INVALID](#INVALID) | 等同于 QualityMode 枚举的 Invalid 元素。 |
| [LOW](#LOW) | 指定低质量插值。 |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | 指定最近邻插值。 |
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
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


指定双三次插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 25% 以下。

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


指定双线性插值。未进行预过滤。此模式不适用于将图像缩小至原始大小的 50% 以下。

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


指定默认模式。

### HIGH {#HIGH}
```
public static final int HIGH
```


指定高质量插值。

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


指定高质量、双三次插值。进行预过滤以确保高质量缩小。此模式产生最高质量的变换图像。

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


指定高质量、双线性插值。进行预过滤以确保高质量缩小。

### INVALID {#INVALID}
```
public static final int INVALID
```


等同于 QualityMode 枚举的 Invalid 元素。

### LOW {#LOW}
```
public static final int LOW
```


指定低质量插值。

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


指定最近邻插值。

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

