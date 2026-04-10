---
title: 杂项
second_title: Aspose.Diagram for Java API 参考
description: 包含形状和组的各种元素，例如控制选择高亮和可见性的元素。
type: docs
weight: 247
url: /zh/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

包含形状和组的各种元素，例如控制选择高亮和可见性的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | 包含由 Microsoft Visio 生成的触发公式，用于确定是否移动一维形状的起点以保持其与另一个形状的连接。 |
| [getCalendar()](#getCalendar--) | 确定用于自定义属性、文本字段和元素公式的日历。 |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | 包含形状的注释文本（字符串格式）。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDropOnPageScale()](#getDropOnPageScale--) | 确定形状在放置到绘图页面时的缩放百分比。 |
| [getDynFeedback()](#getDynFeedback--) | 指定用户拖动连接线时提供的视觉反馈类型。 |
| [getEndTrigger()](#getEndTrigger--) | 包含由 Microsoft Visio 生成的触发公式。 |
| [getGlueType()](#getGlueType--) | 指定在连接到形状时是否允许动态（形状到形状）粘合。 |
| [getHideText()](#getHideText--) | 隐藏形状的文本。 |
| [getLangID()](#getLangID--) | 指示输入单元格公式、文本、自定义属性或注释的语言的区域标识符 (LCID)。 |
| [getLocalizeMerge()](#getLocalizeMerge--) | 确定在文档之间复制形状时，形状是否本地化（其 LangID 元素是否被重置）。 |
| [getNoAlignBox()](#getNoAlignBox--) | 指定在选择形状时是否显示选区矩形。 |
| [getNoCtlHandles()](#getNoCtlHandles--) | 指定在选择形状时是否显示控制手柄。 |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | 指定形状在用户操作时是否会动态调整大小或旋转。 |
| [getNoObjHandles()](#getNoObjHandles--) | 指定在选择形状时是否显示选择手柄。 |
| [getNonPrinting()](#getNonPrinting--) | 指定所选形状是否可以打印。 |
| [getObjType()](#getObjType--) | 指定在使用 Microsoft Visio 在绘图页面上布局形状时，对象是否可放置或可路由。 |
| [getShapeKeywords()](#getShapeKeywords--) | 包含已分配给自定义母版形状的搜索关键字。 |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | 指定在移动控制手柄时是否重新计算形状的选区矩形。 |
| [getWalkPreference()](#getWalkPreference--) | 指定当形状移动到模糊位置时，使用动态粘连时，1-D 形状的端点是否移动到其粘连形状的水平或垂直连接点。 |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | 指定是否可以通过将形状拖放到组上将其添加到组中。 |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | 指示在形状替换操作期间，母版形状中指定单元格的值是否覆盖被替换形状的值（包括本地值）。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


包含由 Microsoft Visio 生成的触发公式，用于确定是否移动一维形状的起点以保持其与另一个形状的连接。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


确定用于自定义属性、文本字段和元素公式的日历。

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


包含形状的注释文本（字符串格式）。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


确定形状在放置到绘图页面时的缩放百分比。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


指定用户拖动连接线时提供的视觉反馈类型。

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


包含由 Microsoft Visio 生成的触发公式。该触发公式用于确定是否移动一维形状的终点以保持其与另一个形状的连接。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


指定在连接到形状时是否允许动态（形状到形状）粘合。

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


隐藏形状的文本。您可以查看文本、编辑属性并对文本块中的文本应用样式，但这些更改只有在将 HideText 元素设置为 0 时才会显示。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


指示输入单元格公式、文本、自定义属性或注释的语言的区域标识符 (LCID)。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


确定在文档之间复制形状时，形状是否本地化（其 LangID 元素是否被重置）。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


指定在选择形状时是否显示选区矩形。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


指定在选择形状时是否显示控制手柄。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


指定形状在用户操作时是否会动态调整大小或旋转。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


指定在选择形状时是否显示选择手柄。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


指定所选形状是否可以打印。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


指定在使用 Microsoft Visio 在绘图页面上布局形状时，对象是否可放置或可路由。

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


包含已分配给自定义母版形状的搜索关键字。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


指定在移动控制手柄时是否重新计算形状的选区矩形。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


指定当形状移动到模糊位置时，使用动态粘连时，1-D 形状的端点是否移动到其粘连形状的水平或垂直连接点。

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


指定是否可以通过将形状拖放到组上将其添加到组中。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


指示在形状替换操作期间，母版形状中指定单元格的值是否覆盖被替换形状的值（包括本地值）。

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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

