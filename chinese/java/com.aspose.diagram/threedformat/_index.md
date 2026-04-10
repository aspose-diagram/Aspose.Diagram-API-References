---
title: ThreeDFormat
second_title: Aspose.Diagram for Java API 参考
description: 表示形状的三维格式化。
type: docs
weight: 406
url: /zh/java/com.aspose.diagram/threedformat/
---

**Inheritance:**
java.lang.Object
```
public class ThreeDFormat
```

表示形状的三维格式化。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getBevelBottomHeight()](#getBevelBottomHeight--) | 指定 3D 形状底部斜角的高度。 |
| [getBevelBottomType()](#getBevelBottomType--) | 指定 3D 形状底部斜角的预设斜角类型 |
| [getBevelBottomWidth()](#getBevelBottomWidth--) | 指定 3D 形状底部斜角的宽度。 |
| [getBevelContourColor()](#getBevelContourColor--) | 指定 3D 形状轮廓的颜色 |
| [getBevelContourSize()](#getBevelContourSize--) | 指定 3D 形状轮廓的粗细 |
| [getBevelDepthColor()](#getBevelDepthColor--) | 指定 3D 形状的拉伸颜色 |
| [getBevelDepthSize()](#getBevelDepthSize--) | 指定 3D 形状的拉伸深度 |
| [getBevelLightingAngle()](#getBevelLightingAngle--) | 指定 3D 形状的光照方向。 |
| [getBevelLightingType()](#getBevelLightingType--) | 指定 3D 形状的预设光照类型 |
| [getBevelMaterialType()](#getBevelMaterialType--) | 指定 3D 形状的预设表面外观 |
| [getBevelTopHeight()](#getBevelTopHeight--) | 指定 3D 形状顶部斜角的高度 |
| [getBevelTopType()](#getBevelTopType--) | 指定 3D 形状顶部斜角的预设斜角类型 |
| [getBevelTopWidth()](#getBevelTopWidth--) | 指定 3D 形状顶部斜角的宽度。 |
| [getClass()](#getClass--) |  |
| [getDistanceFromGround()](#getDistanceFromGround--) | 指定 具有 3D 旋转属性的形状的距离 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 指定 3D 旋转属性是否适用于形状的文本 |
| [getPerspective()](#getPerspective--) | 指定 具有 3D 旋转属性的形状的视角 |
| [getRotationType()](#getRotationType--) | 指定 形状效果属性的投影类型。 |
| [getRotationXAngle()](#getRotationXAngle--) | 指定 形状围绕 y 轴的逆时针旋转角度。 |
| [getRotationYAngle()](#getRotationYAngle--) | 指定 形状围绕 x 轴的逆时针旋转角度 |
| [getRotationZAngle()](#getRotationZAngle--) | 指定 形状围绕 z 轴的逆时针旋转角度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBevelBottomHeight(DoubleValue value)](#setBevelBottomHeight-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--) |
| [setBevelBottomType(BevelType value)](#setBevelBottomType-com.aspose.diagram.BevelType-) | 有关此属性的描述，请参阅 [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--) |
| [setBevelBottomWidth(DoubleValue value)](#setBevelBottomWidth-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--) |
| [setBevelContourColor(ColorValue value)](#setBevelContourColor-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--) |
| [setBevelContourSize(DoubleValue value)](#setBevelContourSize-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--) |
| [setBevelDepthColor(ColorValue value)](#setBevelDepthColor-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--) |
| [setBevelDepthSize(DoubleValue value)](#setBevelDepthSize-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--) |
| [setBevelLightingAngle(DoubleValue value)](#setBevelLightingAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--) |
| [setBevelLightingType(BevelLightingType value)](#setBevelLightingType-com.aspose.diagram.BevelLightingType-) | 有关此属性的描述，请参阅 [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--) |
| [setBevelMaterialType(BevelMaterialType value)](#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-) | 有关此属性的描述，请参阅 [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--) |
| [setBevelTopHeight(DoubleValue value)](#setBevelTopHeight-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--) |
| [setBevelTopType(BevelType value)](#setBevelTopType-com.aspose.diagram.BevelType-) | 有关此属性的描述，请参阅 [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--) |
| [setBevelTopWidth(DoubleValue value)](#setBevelTopWidth-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--) |
| [setDistanceFromGround(DoubleValue value)](#setDistanceFromGround-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--) |
| [setKeepTextFlat(BoolValue value)](#setKeepTextFlat-com.aspose.diagram.BoolValue-) | 有关此属性的描述，请参阅 [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--) |
| [setPerspective(DoubleValue value)](#setPerspective-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--) |
| [setRotationType(RotationType value)](#setRotationType-com.aspose.diagram.RotationType-) | 有关此属性的描述，请参阅 [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--) |
| [setRotationXAngle(DoubleValue value)](#setRotationXAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--) |
| [setRotationYAngle(DoubleValue value)](#setRotationYAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--) |
| [setRotationZAngle(DoubleValue value)](#setRotationZAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean -
### getBevelBottomHeight() {#getBevelBottomHeight--}
```
public DoubleValue getBevelBottomHeight()
```


指定 3D 形状底部斜角的高度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelBottomType() {#getBevelBottomType--}
```
public BevelType getBevelBottomType()
```


指定 3D 形状底部斜角的预设斜角类型

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelBottomWidth() {#getBevelBottomWidth--}
```
public DoubleValue getBevelBottomWidth()
```


指定 3D 形状底部斜角的宽度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelContourColor() {#getBevelContourColor--}
```
public ColorValue getBevelContourColor()
```


指定 3D 形状轮廓的颜色

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelContourSize() {#getBevelContourSize--}
```
public DoubleValue getBevelContourSize()
```


指定 3D 形状轮廓的粗细

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelDepthColor() {#getBevelDepthColor--}
```
public ColorValue getBevelDepthColor()
```


指定 3D 形状的拉伸颜色

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelDepthSize() {#getBevelDepthSize--}
```
public DoubleValue getBevelDepthSize()
```


指定 3D 形状的拉伸深度

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingAngle() {#getBevelLightingAngle--}
```
public DoubleValue getBevelLightingAngle()
```


指定 3D 形状的光照方向。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingType() {#getBevelLightingType--}
```
public BevelLightingType getBevelLightingType()
```


指定 3D 形状的预设光照类型

**Returns:**
[BevelLightingType](../../com.aspose.diagram/bevellightingtype)
### getBevelMaterialType() {#getBevelMaterialType--}
```
public BevelMaterialType getBevelMaterialType()
```


指定 3D 形状的预设表面外观

**Returns:**
[BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype)
### getBevelTopHeight() {#getBevelTopHeight--}
```
public DoubleValue getBevelTopHeight()
```


指定 3D 形状顶部斜角的高度

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelTopType() {#getBevelTopType--}
```
public BevelType getBevelTopType()
```


指定 3D 形状顶部斜角的预设斜角类型

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelTopWidth() {#getBevelTopWidth--}
```
public DoubleValue getBevelTopWidth()
```


指定 3D 形状顶部斜角的宽度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDistanceFromGround() {#getDistanceFromGround--}
```
public DoubleValue getDistanceFromGround()
```


指定 具有 3D 旋转属性的形状的距离

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public BoolValue getKeepTextFlat()
```


指定 3D 旋转属性是否适用于形状的文本

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerspective() {#getPerspective--}
```
public DoubleValue getPerspective()
```


指定 具有 3D 旋转属性的形状的视角

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationType() {#getRotationType--}
```
public RotationType getRotationType()
```


指定 形状效果属性的投影类型。

**Returns:**
[RotationType](../../com.aspose.diagram/rotationtype)
### getRotationXAngle() {#getRotationXAngle--}
```
public DoubleValue getRotationXAngle()
```


指定 形状围绕 y 轴的逆时针旋转角度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationYAngle() {#getRotationYAngle--}
```
public DoubleValue getRotationYAngle()
```


指定 形状围绕 x 轴的逆时针旋转角度

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationZAngle() {#getRotationZAngle--}
```
public DoubleValue getRotationZAngle()
```


指定 形状围绕 z 轴的逆时针旋转角度。

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




### setBevelBottomHeight(DoubleValue value) {#setBevelBottomHeight-com.aspose.diagram.DoubleValue-}
```
public void setBevelBottomHeight(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelBottomType(BevelType value) {#setBevelBottomType-com.aspose.diagram.BevelType-}
```
public void setBevelBottomType(BevelType value)
```


有关此属性的描述，请参阅 [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelBottomWidth(DoubleValue value) {#setBevelBottomWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelBottomWidth(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelContourColor(ColorValue value) {#setBevelContourColor-com.aspose.diagram.ColorValue-}
```
public void setBevelContourColor(ColorValue value)
```


有关此属性的描述，请参阅 [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelContourSize(DoubleValue value) {#setBevelContourSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelContourSize(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelDepthColor(ColorValue value) {#setBevelDepthColor-com.aspose.diagram.ColorValue-}
```
public void setBevelDepthColor(ColorValue value)
```


有关此属性的描述，请参阅 [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelDepthSize(DoubleValue value) {#setBevelDepthSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelDepthSize(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingAngle(DoubleValue value) {#setBevelLightingAngle-com.aspose.diagram.DoubleValue-}
```
public void setBevelLightingAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingType(BevelLightingType value) {#setBevelLightingType-com.aspose.diagram.BevelLightingType-}
```
public void setBevelLightingType(BevelLightingType value)
```


有关此属性的描述，请参阅 [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BevelLightingType](../../com.aspose.diagram/bevellightingtype) |  |

### setBevelMaterialType(BevelMaterialType value) {#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-}
```
public void setBevelMaterialType(BevelMaterialType value)
```


有关此属性的描述，请参阅 [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype) |  |

### setBevelTopHeight(DoubleValue value) {#setBevelTopHeight-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopHeight(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelTopType(BevelType value) {#setBevelTopType-com.aspose.diagram.BevelType-}
```
public void setBevelTopType(BevelType value)
```


有关此属性的描述，请参阅 [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelTopWidth(DoubleValue value) {#setBevelTopWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopWidth(DoubleValue value)
```


有关此属性的描述，请参阅 [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDistanceFromGround(DoubleValue value) {#setDistanceFromGround-com.aspose.diagram.DoubleValue-}
```
public void setDistanceFromGround(DoubleValue value)
```


有关此属性的描述，请参阅 [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setKeepTextFlat(BoolValue value) {#setKeepTextFlat-com.aspose.diagram.BoolValue-}
```
public void setKeepTextFlat(BoolValue value)
```


有关此属性的描述，请参阅 [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerspective(DoubleValue value) {#setPerspective-com.aspose.diagram.DoubleValue-}
```
public void setPerspective(DoubleValue value)
```


有关此属性的描述，请参阅 [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationType(RotationType value) {#setRotationType-com.aspose.diagram.RotationType-}
```
public void setRotationType(RotationType value)
```


有关此属性的描述，请参阅 [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RotationType](../../com.aspose.diagram/rotationtype) |  |

### setRotationXAngle(DoubleValue value) {#setRotationXAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationXAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationYAngle(DoubleValue value) {#setRotationYAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationYAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationZAngle(DoubleValue value) {#setRotationZAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationZAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

