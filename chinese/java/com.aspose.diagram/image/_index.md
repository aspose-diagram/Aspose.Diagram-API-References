---
title: 图像
second_title: Aspose.Diagram for Java API 参考
description: 包含位图的伽马、亮度、对比度、模糊、锐化、去噪和透明度值。
type: docs
weight: 196
url: /zh/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

包含位图的伽马、亮度、对比度、模糊、锐化、去噪和透明度值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | 模糊或柔化位图图像。 |
| [getBrightness()](#getBrightness--) | 调整位图图像的亮度。 |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | 指定位图图像的对比度。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDenoise()](#getDenoise--) | 从位图图像中移除噪声（像素的颜色水平随机分布）。 |
| [getGamma()](#getGamma--) | 调整或校正图像在特定输出设备（如显示器或扫描仪）上的强度。 |
| [getSharpen()](#getSharpen--) | 指定锐化位图图像的程度。 |
| [getTransparency()](#getTransparency--) | 指定图层颜色的透明度级别，范围从 0（不透明）到 1（完全透明）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参见 [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


模糊或柔化位图图像。Blur 元素包含 0 到 1 之间的值；默认值为 0。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


调整位图图像的亮度。Brightness 元素包含 0 到 1 之间的值；默认值为 0.5。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


指定位图图像的对比度。Contrast 元素包含 0 到 1 之间的值。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


从位图图像中移除噪声（像素的颜色水平随机分布）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


调整或校正图像在特定输出设备（如显示器或扫描仪）上的强度。默认值为 1（无校正）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


指定锐化位图图像的程度。锐化图像通过增加相邻像素的对比度来使其更清晰。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


指定图层颜色的透明度级别，范围从 0（不透明）到 1（完全透明）。

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


有关此属性的描述，请参见 [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

