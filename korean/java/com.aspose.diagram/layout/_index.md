---
title: 레이아웃
second_title: Aspose.Diagram for Java API 참조
description: 도형 배치 및 커넥터 라우팅 설정을 제어하는 요소를 포함합니다.
type: docs
weight: 215
url: /ko/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

도형 배치 및 커넥터 라우팅 설정을 제어하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | 커넥터가 재경로 지정되는 시점을 결정합니다. |
| [getConLineJumpCode()](#getConLineJumpCode--) | 두 연결기가 교차할 때 연결기가 점프하는지 여부를 결정합니다, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | 동적 커넥터의 수평 구간에서 발생하는 라인 점프의 방향을 결정합니다. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | 동적 커넥터의 수직 구간에서 발생하는 라인 점프의 방향을 결정합니다. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | 동적 커넥터의 라인 점프 스타일을 결정합니다. |
| [getConLineRouteExt()](#getConLineRouteExt--) | 커넥터의 외관을 결정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDisplayLevel()](#getDisplayLevel--) | 도형에 대한 표시 레벨 밴드( Z-순서 그룹화의 상대 범위)를 결정합니다. |
| [getRelationships()](#getRelationships--) | 컨테이너, 목록, 호출선 및 도형 간의 관계를 저장합니다. |
| [getShapeFixedCode()](#getShapeFixedCode--) | 배치 가능한 도형에 대한 배치 동작을 지정합니다. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | 사용자가 '도형 배치'(도형 메뉴)를 선택할 때 배치 가능한 도형을 기존 도형 위에 배치할 수 있는지 여부를 지정합니다. |
| [getShapePermeableX()](#getShapePermeableX--) | 연결기가 도형을 가로로 통과하도록 라우팅할 수 있는지 여부를 지정합니다. |
| [getShapePermeableY()](#getShapePermeableY--) | 연결기가 도형을 세로로 통과하도록 라우팅할 수 있는지 여부를 지정합니다. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | 사용자가 레이아웃 도형(도형 메뉴)을 선택할 때 배치 가능한 도형이 페이지에서 뒤집히거나 회전하는 방식을 지정합니다. |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | 자식 요소에 대한 배치 스타일을 결정합니다. |
| [getShapePlowCode()](#getShapePlowCode--) | 그리기 페이지에서 다른 배치 가능한 도형을 해당 도형 근처로 드래그할 때 배치 가능한 도형이 멀어지는지 여부를 지정합니다. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | 그리기 페이지에서 커넥터의 라우팅 스타일 및 방향을 지정합니다. |
| [getShapeSplit()](#getShapeSplit--) | 이 도형이 분할 가능한 도형을 분할할 수 있는지 여부를 결정합니다. |
| [getShapeSplittable()](#getShapeSplittable--) | 이 1차원 도형을 분할할 수 있는지 여부를 결정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/layout\#getDel--)을(를) 참조하십시오. |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | 이 속성에 대한 설명은 [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


커넥터가 재경로 지정되는 시점을 결정합니다.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


두 연결기가 교차할 때 연결기가 점프하는지 여부를 결정합니다,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


동적 커넥터의 수평 구간에서 발생하는 라인 점프의 방향을 결정합니다.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


동적 커넥터의 수직 구간에서 발생하는 라인 점프의 방향을 결정합니다.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


동적 커넥터의 라인 점프 스타일을 결정합니다.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


커넥터의 외관을 결정합니다.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


도형에 대한 표시 레벨 밴드( Z-순서 그룹화의 상대 범위)를 결정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


컨테이너, 목록, 호출선 및 도형 간의 관계를 저장합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


배치 가능한 도형에 대한 배치 동작을 지정합니다.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


사용자가 '도형 배치'(도형 메뉴)를 선택할 때 배치 가능한 도형을 기존 도형 위에 배치할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


연결기가 도형을 가로로 통과하도록 라우팅할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


연결기가 도형을 세로로 통과하도록 라우팅할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


사용자가 레이아웃 도형(도형 메뉴)을 선택할 때 배치 가능한 도형이 페이지에서 뒤집히거나 회전하는 방식을 지정합니다.

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


자식 요소에 대한 배치 스타일을 결정합니다.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


그리기 페이지에서 다른 배치 가능한 도형을 해당 도형 근처로 드래그할 때 배치 가능한 도형이 멀어지는지 여부를 지정합니다.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


그리기 페이지에서 커넥터의 라우팅 스타일 및 방향을 지정합니다.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


이 도형이 분할 가능한 도형을 분할할 수 있는지 여부를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


이 1차원 도형을 분할할 수 있는지 여부를 결정합니다.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/layout\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


이 속성에 대한 설명은 [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

