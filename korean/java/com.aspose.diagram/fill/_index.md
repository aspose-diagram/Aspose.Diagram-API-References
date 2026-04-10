---
title: 채우기
second_title: Aspose.Diagram for Java API 참조
description: 도형 및 도형 그림자에 대한 현재 채우기 서식 값을 포함하며, 패턴 전경색 및 배경색을 포함합니다.
type: docs
weight: 153
url: /ko/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

패턴, 전경색 및 배경색을 포함하여 도형 및 도형의 그림자에 대한 현재 채우기 서식 값을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getFillBkgnd()](#getFillBkgnd--) | 도형 채우기 패턴 배경에 사용되는 색상을 지정합니다. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | 도형 채우기 패턴 배경(채우기) 색상의 투명도 수준을 지정합니다. 0(완전히 불투명)에서 1(완전히 투명)까지. |
| [getFillForegnd()](#getFillForegnd--) | 도형 채우기 패턴 전경(스트로크)에 사용되는 색상을 지정합니다. |
| [getFillForegndTrans()](#getFillForegndTrans--) | 도형 채우기 패턴 전경(채우기) 색상의 투명도 수준을 지정합니다. 0(완전히 불투명)에서 1(완전히 투명)까지. |
| [getFillPattern()](#getFillPattern--) | 도형의 채우기 패턴을 지정합니다. |
| [getGradientFill()](#getGradientFill--) | 도형에 대한 현재 그라디언트 채우기 서식 값을 포함합니다. |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | 도형 그림자의 흐림 크기를 지정합니다. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | 도형 그림자의 비스듬한 방향 각도를 지정합니다. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | 도형 그림자가 도형으로부터 수평으로 오프셋되는 거리를 페이지 단위로 결정합니다. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | 도형 그림자가 도형으로부터 수직으로 오프셋되는 거리를 페이지 단위로 결정합니다. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | 도형 그림자를 확대하거나 축소할 수 있는 비율을 지정합니다. |
| [getShapeShdwShow()](#getShapeShdwShow--) | 도형의 그림자 유형을 지정합니다. |
| [getShapeShdwType()](#getShapeShdwType--) | 도형의 그림자 유형을 지정합니다. |
| [getShdwBkgnd()](#getShdwBkgnd--) | 도형 그림자 채우기 패턴 배경(채우기)에 사용되는 색상을 지정합니다. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | 도형 그림자 채우기 패턴 배경(채우기)의 투명도 수준을 지정합니다. 0.0(완전히 불투명)에서 1.0(완전히 투명)까지. |
| [getShdwForegnd()](#getShdwForegnd--) | 도형 그림자 채우기 패턴 전경(스트로크)에 사용되는 색상을 지정합니다. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | 도형 그림자 채우기 패턴 전경(스트로크)의 투명도 수준을 지정합니다. 0.0(완전히 불투명)에서 1.0(완전히 투명)까지. |
| [getShdwPattern()](#getShdwPattern--) | 도형 그림자의 채우기 패턴을 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/fill\#getDel--)을 참조하십시오. |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)을 참조하십시오. |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)을 참조하십시오. |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)을 참조하십시오. |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)을 참조하십시오. |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)을 참조하십시오. |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)을 참조하십시오. |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)을 참조하십시오. |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)을(를) 참조하십시오. |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)을(를) 참조하십시오. |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)을(를) 참조하십시오. |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | 이 속성에 대한 설명은 [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)을(를) 참조하십시오. |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | 이 속성에 대한 설명은 [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)을(를) 참조하십시오. |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)을(를) 참조하십시오. |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)을(를) 참조하십시오. |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)을(를) 참조하십시오. |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)을(를) 참조하십시오. |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


도형 채우기 패턴 배경에 사용되는 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


도형 채우기 패턴 배경(채우기) 색상의 투명도 수준을 지정합니다. 0(완전히 불투명)에서 1(완전히 투명)까지.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


도형 채우기 패턴 전경(스트로크)에 사용되는 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


도형 채우기 패턴 전경(채우기) 색상의 투명도 수준을 지정합니다. 0(완전히 불투명)에서 1(완전히 투명)까지.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


도형의 채우기 패턴을 지정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


도형에 대한 현재 그라디언트 채우기 서식 값을 포함합니다.

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


도형의 그림자 흐림 크기를 지정합니다. 현재 흐림을 그릴 수는 없지만, 이제 vsdx에서 파싱할 수 있습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


도형 그림자의 비스듬한 방향 각도를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


도형 그림자가 도형으로부터 수평으로 오프셋되는 거리를 페이지 단위로 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


도형 그림자가 도형으로부터 수직으로 오프셋되는 거리를 페이지 단위로 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


도형 그림자를 확대하거나 축소할 수 있는 비율을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


도형의 그림자 유형을 지정합니다.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


도형의 그림자 유형을 지정합니다.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


도형 그림자 채우기 패턴 배경(채우기)에 사용되는 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


도형 그림자 채우기 패턴 배경(채우기)의 투명도 수준을 지정합니다. 0.0(완전히 불투명)에서 1.0(완전히 투명)까지.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


도형 그림자 채우기 패턴 전경(스트로크)에 사용되는 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


도형 그림자 채우기 패턴 전경(스트로크)의 투명도 수준을 지정합니다. 0.0(완전히 불투명)에서 1.0(완전히 투명)까지.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


도형 그림자의 채우기 패턴을 지정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/fill\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


이 속성에 대한 설명은 [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


이 속성에 대한 설명은 [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


이 속성에 대한 설명은 [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


이 속성에 대한 설명은 [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


이 속성에 대한 설명은 [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


이 속성에 대한 설명은 [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


이 속성에 대한 설명은 [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


이 속성에 대한 설명은 [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


이 속성에 대한 설명은 [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


이 속성에 대한 설명은 [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


이 속성에 대한 설명은 [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


이 속성에 대한 설명은 [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

