---
title: 保护
second_title: Aspose.Diagram for Java API 参考
description: 锁定有助于防止对形状的意外更改，但不会阻止 Microsoft Visio 在其他情况下重置值。
type: docs
weight: 312
url: /zh/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

锁定有助于防止对形状的意外更改，但不会阻止 Microsoft Visio 在其他情况下重置值。它也不能防止在 ShapeSheet 窗口中所做的更改。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getLockAspect()](#getLockAspect--) | 指定形状的宽高比是否被锁定。 |
| [getLockBegin()](#getLockBegin--) | 指定一维形状的起始点是否锁定到特定位置。 |
| [getLockCalcWH()](#getLockCalcWH--) | 指定形状的选取矩形是否被锁定，以便在编辑顶点或在 Geom 元素中更改元素类型时无法重新计算。 |
| [getLockCrop()](#getLockCrop--) | 指定外部对象是否被锁定，防止在 Microsoft Visio 中使用裁剪工具进行裁剪。 |
| [getLockCustProp()](#getLockCustProp--) | 确定用户是否可以通过“定义自定义属性”对话框在用户界面 (UI) 中添加、删除或修改自定义属性。 |
| [getLockDelete()](#getLockDelete--) | 指定形状是否被锁定，防止被删除。 |
| [getLockEnd()](#getLockEnd--) | 指定一维形状的终点是否锁定到特定位置。 |
| [getLockFormat()](#getLockFormat--) | 指定形状的格式是否被锁定，无法更改。 |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | 允许子形状阻止在 Visio 用户界面中应用于父组形状的格式更改，这些更改否则会级联到各个组形状。 |
| [getLockGroup()](#getLockGroup--) | 指定组是否被锁定，无法取消分组。 |
| [getLockHeight()](#getLockHeight--) | 指定形状的高度是否被锁定。 |
| [getLockMoveX()](#getLockMoveX--) | 指定形状的水平位置是否被锁定，无法水平移动。 |
| [getLockMoveY()](#getLockMoveY--) | 指定形状的垂直位置是否被锁定，无法垂直移动。 |
| [getLockRotate()](#getLockRotate--) | 指定形状是否被锁定，防止在 Microsoft Visio 中使用旋转工具或“向左旋转”“向右旋转”命令进行旋转。 |
| [getLockSelect()](#getLockSelect--) | 指定形状的选取矩形是否被锁定，以便在编辑顶点或在 Geom 元素中更改元素类型时无法重新计算。 |
| [getLockTextEdit()](#getLockTextEdit--) | 指定形状的文本是否被锁定，无法编辑。 |
| [getLockThemeColors()](#getLockThemeColors--) | 阻止用户对形状应用主题颜色。 |
| [getLockThemeEffects()](#getLockThemeEffects--) | 阻止用户对形状应用主题效果。 |
| [getLockVtxEdit()](#getLockVtxEdit--) | 指定形状的顶点是否被锁定，以致无法使用工具栏上的任何工具进行编辑。 |
| [getLockWidth()](#getLockWidth--) | 指定形状的宽度是否被锁定，以致在调整形状大小时保持不变。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


指定形状的宽高比是否被锁定。如果锁定，形状只能按比例缩放；不能在单一维度上调整大小。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


指定一维形状的起始点是否锁定到特定位置。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


指定形状的选取矩形是否被锁定，以便在编辑顶点或在 Geom 元素中更改元素类型时无法重新计算。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


指定外部对象是否被锁定，防止在 Microsoft Visio 中使用裁剪工具进行裁剪。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


确定用户是否可以通过“定义自定义属性”对话框在用户界面 (UI) 中添加、删除或修改自定义属性。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


指定形状是否被锁定，防止被删除。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


指定一维形状的终点是否锁定到特定位置。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


指定形状的格式是否被锁定，从而无法更改。具体而言，此元素防止更改文本、线条和填充的格式，或更改形状继承的 Style 元素。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


允许子形状阻止在 Visio 用户界面中应用于父组形状的格式更改，这些更改否则会级联到各个组形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


指定组是否被锁定，无法取消分组。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


指定形状的高度是否被锁定。如果锁定，调整形状大小时其高度保持不变。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


指定形状的水平位置是否被锁定，无法水平移动。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


指定形状的垂直位置是否被锁定，无法垂直移动。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


指定形状是否被锁定，防止在 Microsoft Visio 中使用旋转工具或“向左旋转”“向右旋转”命令进行旋转。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


指定形状的选取矩形是否被锁定，以便在编辑顶点或在 Geom 元素中更改元素类型时无法重新计算。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


指定形状的文本是否被锁定，以致无法编辑。然而，仍可以通过应用样式、使用文本对话框中“字体”选项卡的 Style 选项来格式化文本。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


阻止用户对形状应用主题颜色。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


阻止用户对形状应用主题效果。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


指定形状的顶点是否被锁定，以致无法使用工具栏上的任何工具进行编辑。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


指定形状的宽度是否被锁定，以致在调整形状大小时保持不变。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

