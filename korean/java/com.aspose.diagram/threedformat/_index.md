---
title: ThreeDFormat
second_title: Aspose.Diagram for Java API 참조
description: 도형의 3차원 서식을 나타냅니다.
type: docs
weight: 406
url: /ko/java/com.aspose.diagram/threedformat/
---

**Inheritance:**
java.lang.Object
```
public class ThreeDFormat
```

도형의 3차원 서식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getBevelBottomHeight()](#getBevelBottomHeight--) | 3D 도형의 하단 베벨 높이를 지정합니다. |
| [getBevelBottomType()](#getBevelBottomType--) | 3D 도형의 하단 베벨에 대한 사전 설정 베벨 유형을 지정합니다. |
| [getBevelBottomWidth()](#getBevelBottomWidth--) | 3D 도형의 하단 베벨 너비를 지정합니다. |
| [getBevelContourColor()](#getBevelContourColor--) | 3D 도형의 외곽선 색상을 지정합니다. |
| [getBevelContourSize()](#getBevelContourSize--) | 3D 도형의 외곽선 두께를 지정합니다. |
| [getBevelDepthColor()](#getBevelDepthColor--) | 3D 도형의 돌출 색상을 지정합니다. |
| [getBevelDepthSize()](#getBevelDepthSize--) | 3D 도형의 돌출 깊이를 지정합니다. |
| [getBevelLightingAngle()](#getBevelLightingAngle--) | 3D 도형의 조명 방향을 지정합니다. |
| [getBevelLightingType()](#getBevelLightingType--) | 3D 도형의 조명 사전 설정 유형을 지정합니다. |
| [getBevelMaterialType()](#getBevelMaterialType--) | 3D 도형의 표면 외관 사전 설정을 지정합니다. |
| [getBevelTopHeight()](#getBevelTopHeight--) | 3D 도형의 상단 베벨 높이를 지정합니다. |
| [getBevelTopType()](#getBevelTopType--) | 3D 도형의 상단 베벨에 대한 사전 설정 베벨 유형을 지정합니다. |
| [getBevelTopWidth()](#getBevelTopWidth--) | 3D 도형의 상단 베벨 너비를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getDistanceFromGround()](#getDistanceFromGround--) | 3D 회전 속성이 있는 도형의 거리를 지정합니다. |
| [getKeepTextFlat()](#getKeepTextFlat--) | 3D 회전 속성이 도형의 텍스트에 적용되는지 여부를 지정합니다. |
| [getPerspective()](#getPerspective--) | 3D 회전 속성이 있는 도형의 시야 각도를 지정합니다. |
| [getRotationType()](#getRotationType--) | 도형의 효과 속성 투영 유형을 지정합니다. |
| [getRotationXAngle()](#getRotationXAngle--) | 도형을 y축을 중심으로 반시계 방향 회전 각도를 지정합니다. |
| [getRotationYAngle()](#getRotationYAngle--) | 도형을 x축을 중심으로 반시계 방향 회전 각도를 지정합니다. |
| [getRotationZAngle()](#getRotationZAngle--) | 도형을 z축을 중심으로 반시계 방향 회전 각도를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBevelBottomHeight(DoubleValue value)](#setBevelBottomHeight-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--)을(를) 참조하십시오. |
| [setBevelBottomType(BevelType value)](#setBevelBottomType-com.aspose.diagram.BevelType-) | 이 속성에 대한 설명은 [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--)을(를) 참조하십시오. |
| [setBevelBottomWidth(DoubleValue value)](#setBevelBottomWidth-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--)을(를) 참조하십시오. |
| [setBevelContourColor(ColorValue value)](#setBevelContourColor-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--)을(를) 참조하십시오. |
| [setBevelContourSize(DoubleValue value)](#setBevelContourSize-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--)을(를) 참조하십시오. |
| [setBevelDepthColor(ColorValue value)](#setBevelDepthColor-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--)을(를) 참조하십시오. |
| [setBevelDepthSize(DoubleValue value)](#setBevelDepthSize-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--)을(를) 참조하십시오. |
| [setBevelLightingAngle(DoubleValue value)](#setBevelLightingAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--)을(를) 참조하십시오. |
| [setBevelLightingType(BevelLightingType value)](#setBevelLightingType-com.aspose.diagram.BevelLightingType-) | 이 속성에 대한 설명은 [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--)을(를) 참조하십시오. |
| [setBevelMaterialType(BevelMaterialType value)](#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-) | 이 속성에 대한 설명은 [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--)을(를) 참조하십시오. |
| [setBevelTopHeight(DoubleValue value)](#setBevelTopHeight-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--)을(를) 참조하십시오. |
| [setBevelTopType(BevelType value)](#setBevelTopType-com.aspose.diagram.BevelType-) | 이 속성에 대한 설명은 [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--)을(를) 참조하십시오. |
| [setBevelTopWidth(DoubleValue value)](#setBevelTopWidth-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--)을(를) 참조하십시오. |
| [setDistanceFromGround(DoubleValue value)](#setDistanceFromGround-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--)을(를) 참조하십시오. |
| [setKeepTextFlat(BoolValue value)](#setKeepTextFlat-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--)을(를) 참조하십시오. |
| [setPerspective(DoubleValue value)](#setPerspective-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--)을(를) 참조하십시오. |
| [setRotationType(RotationType value)](#setRotationType-com.aspose.diagram.RotationType-) | 이 속성에 대한 설명은 [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--)을(를) 참조하십시오. |
| [setRotationXAngle(DoubleValue value)](#setRotationXAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--)을(를) 참조하십시오. |
| [setRotationYAngle(DoubleValue value)](#setRotationYAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--)을(를) 참조하십시오. |
| [setRotationZAngle(DoubleValue value)](#setRotationZAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean -
### getBevelBottomHeight() {#getBevelBottomHeight--}
```
public DoubleValue getBevelBottomHeight()
```


3D 도형의 하단 베벨 높이를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelBottomType() {#getBevelBottomType--}
```
public BevelType getBevelBottomType()
```


3D 도형의 하단 베벨에 대한 사전 설정 베벨 유형을 지정합니다.

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelBottomWidth() {#getBevelBottomWidth--}
```
public DoubleValue getBevelBottomWidth()
```


3D 도형의 하단 베벨 너비를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelContourColor() {#getBevelContourColor--}
```
public ColorValue getBevelContourColor()
```


3D 도형의 외곽선 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelContourSize() {#getBevelContourSize--}
```
public DoubleValue getBevelContourSize()
```


3D 도형의 외곽선 두께를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelDepthColor() {#getBevelDepthColor--}
```
public ColorValue getBevelDepthColor()
```


3D 도형의 돌출 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelDepthSize() {#getBevelDepthSize--}
```
public DoubleValue getBevelDepthSize()
```


3D 도형의 돌출 깊이를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingAngle() {#getBevelLightingAngle--}
```
public DoubleValue getBevelLightingAngle()
```


3D 도형의 조명 방향을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingType() {#getBevelLightingType--}
```
public BevelLightingType getBevelLightingType()
```


3D 도형의 조명 사전 설정 유형을 지정합니다.

**Returns:**
[BevelLightingType](../../com.aspose.diagram/bevellightingtype)
### getBevelMaterialType() {#getBevelMaterialType--}
```
public BevelMaterialType getBevelMaterialType()
```


3D 도형의 표면 외관 사전 설정을 지정합니다.

**Returns:**
[BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype)
### getBevelTopHeight() {#getBevelTopHeight--}
```
public DoubleValue getBevelTopHeight()
```


3D 도형의 상단 베벨 높이를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelTopType() {#getBevelTopType--}
```
public BevelType getBevelTopType()
```


3D 도형의 상단 베벨에 대한 사전 설정 베벨 유형을 지정합니다.

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelTopWidth() {#getBevelTopWidth--}
```
public DoubleValue getBevelTopWidth()
```


3D 도형의 상단 베벨 너비를 지정합니다.

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


3D 회전 속성이 있는 도형의 거리를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public BoolValue getKeepTextFlat()
```


3D 회전 속성이 도형의 텍스트에 적용되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerspective() {#getPerspective--}
```
public DoubleValue getPerspective()
```


3D 회전 속성이 있는 도형의 시야 각도를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationType() {#getRotationType--}
```
public RotationType getRotationType()
```


도형의 효과 속성 투영 유형을 지정합니다.

**Returns:**
[RotationType](../../com.aspose.diagram/rotationtype)
### getRotationXAngle() {#getRotationXAngle--}
```
public DoubleValue getRotationXAngle()
```


도형을 y축을 중심으로 반시계 방향 회전 각도를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationYAngle() {#getRotationYAngle--}
```
public DoubleValue getRotationYAngle()
```


도형을 x축을 중심으로 반시계 방향 회전 각도를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationZAngle() {#getRotationZAngle--}
```
public DoubleValue getRotationZAngle()
```


도형을 z축을 중심으로 반시계 방향 회전 각도를 지정합니다.

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


이 속성에 대한 설명은 [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelBottomType(BevelType value) {#setBevelBottomType-com.aspose.diagram.BevelType-}
```
public void setBevelBottomType(BevelType value)
```


이 속성에 대한 설명은 [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelBottomWidth(DoubleValue value) {#setBevelBottomWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelBottomWidth(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelContourColor(ColorValue value) {#setBevelContourColor-com.aspose.diagram.ColorValue-}
```
public void setBevelContourColor(ColorValue value)
```


이 속성에 대한 설명은 [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelContourSize(DoubleValue value) {#setBevelContourSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelContourSize(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelDepthColor(ColorValue value) {#setBevelDepthColor-com.aspose.diagram.ColorValue-}
```
public void setBevelDepthColor(ColorValue value)
```


이 속성에 대한 설명은 [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelDepthSize(DoubleValue value) {#setBevelDepthSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelDepthSize(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingAngle(DoubleValue value) {#setBevelLightingAngle-com.aspose.diagram.DoubleValue-}
```
public void setBevelLightingAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingType(BevelLightingType value) {#setBevelLightingType-com.aspose.diagram.BevelLightingType-}
```
public void setBevelLightingType(BevelLightingType value)
```


이 속성에 대한 설명은 [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BevelLightingType](../../com.aspose.diagram/bevellightingtype) |  |

### setBevelMaterialType(BevelMaterialType value) {#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-}
```
public void setBevelMaterialType(BevelMaterialType value)
```


이 속성에 대한 설명은 [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype) |  |

### setBevelTopHeight(DoubleValue value) {#setBevelTopHeight-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopHeight(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelTopType(BevelType value) {#setBevelTopType-com.aspose.diagram.BevelType-}
```
public void setBevelTopType(BevelType value)
```


이 속성에 대한 설명은 [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelTopWidth(DoubleValue value) {#setBevelTopWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopWidth(DoubleValue value)
```


이 속성에 대한 설명은 [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDistanceFromGround(DoubleValue value) {#setDistanceFromGround-com.aspose.diagram.DoubleValue-}
```
public void setDistanceFromGround(DoubleValue value)
```


이 속성에 대한 설명은 [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setKeepTextFlat(BoolValue value) {#setKeepTextFlat-com.aspose.diagram.BoolValue-}
```
public void setKeepTextFlat(BoolValue value)
```


이 속성에 대한 설명은 [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerspective(DoubleValue value) {#setPerspective-com.aspose.diagram.DoubleValue-}
```
public void setPerspective(DoubleValue value)
```


이 속성에 대한 설명은 [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationType(RotationType value) {#setRotationType-com.aspose.diagram.RotationType-}
```
public void setRotationType(RotationType value)
```


이 속성에 대한 설명은 [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RotationType](../../com.aspose.diagram/rotationtype) |  |

### setRotationXAngle(DoubleValue value) {#setRotationXAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationXAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationYAngle(DoubleValue value) {#setRotationYAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationYAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationZAngle(DoubleValue value) {#setRotationZAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationZAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

