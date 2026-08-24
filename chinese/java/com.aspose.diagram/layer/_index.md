---
title: Layer
second_title: Aspose.Diagram for Java API 参考
description: 包含定义页面单个图层及其属性的元素。
type: docs
weight: 212
url: /zh/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

包含定义页面单个图层及其属性的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Layer()](#Layer--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | 指定图层是否处于活动状态。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 用于显示图层的颜色表中颜色的索引，或指定颜色表中不存在的自定义颜色的 RGB 值（例如，\#ff9900）。 |
| [getColorTrans()](#getColorTrans--) | 确定图层或形状文本颜色的透明度，范围从 0（完全不透明）到 1（完全透明）。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getGlue()](#getGlue--) | 指定属于该层的形状是否可以粘附。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getLock()](#getLock--) | 指定属于该层的形状是否被锁定，无法被选中或编辑。 |
| [getName()](#getName--) | Name 元素指定层的名称。 |
| [getNameUniv()](#getNameUniv--) | 指定层的通用名称。 |
| [getPrint()](#getPrint--) | 指定在打印图纸时是否打印属于该层的形状。 |
| [getSnap()](#getSnap--) | 指定其他形状是否可以捕捉到分配给该层的形状。 |
| [getStatus()](#getStatus--) | 指定该层是否为文档的有效层。 |
| [getVisible()](#getVisible--) | 指定属于该层的形状是否在绘图页面上可见。 |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | 指示元素是否已在本地检查的标志。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | 有关此属性的描述，请参阅 [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


构造函数。

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


指定层是否处于活动状态。当形状未预先分配到层时，放置在绘图页面上会被分配到活动层。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


用于显示图层的颜色表中颜色的索引，或指定颜色表中不存在的自定义颜色的 RGB 值（例如，\#ff9900）。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


确定图层或形状文本颜色的透明度，范围从 0（完全不透明）到 1（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


指定属于该层的形状是否可以粘附。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


元素在其父元素中的零基索引。

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


指定属于该层的形状是否被锁定，无法被选中或编辑。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name 元素指定层的名称。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


指定层的通用名称。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


指定在打印图纸时是否打印属于该层的形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


指定其他形状是否可以捕捉到分配给该层的形状。分配给该层的形状可以捕捉到其他形状，但其他形状不能捕捉到它们。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


指定该层是否为文档的有效层。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


指定属于该层的形状是否在绘图页面上可见。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


指示元素是否已在本地检查的标志。值为 1 表示该元素已在本地检查。

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


有关此属性的描述，请参阅 [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

