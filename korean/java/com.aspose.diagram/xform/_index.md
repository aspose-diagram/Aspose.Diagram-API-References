---
title: XForm
second_title: Aspose.Diagram for Java API 참조
description: 패턴 두께 및 색상과 같은 도형의 선 속성을 제어하는 요소를 포함합니다.
type: docs
weight: 449
url: /ko/java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

모양의 선 속성을 제어하는 요소들을 포함합니다. 예를 들어 패턴, 두께, 색상 등이 있습니다. 이러한 요소들은 선 끝이 형식화되는지 여부(예: 화살표 머리), 선 끝 형식의 크기, 선에 적용되는 둥근 원의 반경, 그리고 선 캡 스타일(둥근 또는 사각)을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 도형이 부모에 대해 현재 회전 각도를 나타냅니다. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getFlipX()](#getFlipX--) | 도형이 수평으로 뒤집혔는지 여부를 나타냅니다 |
| [getFlipY()](#getFlipY--) | 도형이 수직으로 뒤집혔는지 여부를 나타냅니다. |
| [getHeight()](#getHeight--) | 도형의 높이를 그리기 단위로 지정합니다. |
| [getLocPinX()](#getLocPinX--) | 도형의 원점에 대한 도형 핀(회전 중심)의 x좌표를 지정합니다. |
| [getLocPinY()](#getLocPinY--) | 도형의 원점에 대한 도형 핀(회전 중심)의 y좌표를 지정합니다. |
| [getPinPos()](#getPinPos--) | 도형의 핀 위치를 지정합니다 |
| [getPinX()](#getPinX--) | 부모의 원점에 대한 도형 핀(회전 중심)의 x좌표를 지정합니다. |
| [getPinY()](#getPinY--) | 부모의 원점에 대한 도형 핀(회전 중심)의 y좌표를 지정합니다. |
| [getResizeMode()](#getResizeMode--) | 그룹에 포함된 경우 도형에 대한 현재 크기 조정 동작 설정을 지정합니다. |
| [getWidth()](#getWidth--) | 연관된 도형의 너비를 그리기 단위로 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getAngle()](../../com.aspose.diagram/xform\#getAngle--)을 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/xform\#getDel--)을 참조하십시오. |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)을 참조하십시오. |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)을 참조하십시오. |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/xform\#getHeight--)을 참조하십시오. |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)을 참조하십시오. |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)을 참조하십시오. |
| [setPinPos(int value)](#setPinPos-int-) | 이 속성에 대한 설명은 [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)을 참조하십시오. |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getPinX()](../../com.aspose.diagram/xform\#getPinX--)을 참조하십시오. |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getPinY()](../../com.aspose.diagram/xform\#getPinY--)을 참조하십시오. |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | 이 속성에 대한 설명은 [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)을 참조하십시오. |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/xform\#getWidth--)을 참조하십시오. |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


도형이 부모에 대해 현재 회전 각도를 나타냅니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


도형이 수평으로 뒤집혔는지 여부를 나타냅니다

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


도형이 수직으로 뒤집혔는지 여부를 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


도형의 높이를 그리기 단위로 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


도형의 원점에 대한 도형 핀(회전 중심)의 x좌표를 지정합니다. LocPinX를 결정하는 기본 수식은: F='Width\* 0.5'입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


도형의 원점에 대한 도형 핀(회전 중심)의 y좌표를 지정합니다. LocPinY를 결정하는 기본 수식은: F='Height \* 0.5'입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


도형의 핀 위치를 지정합니다

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


부모의 원점에 대한 도형 핀(회전 중심)의 x좌표를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


부모의 원점에 대한 도형 핀(회전 중심)의 y좌표를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


그룹에 포함된 경우 도형에 대한 현재 크기 조정 동작 설정을 지정합니다.

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


연관된 도형의 너비를 그리기 단위로 포함합니다.

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


이 속성에 대한 설명은 [getAngle()](../../com.aspose.diagram/xform\#getAngle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/xform\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


이 속성에 대한 설명은 [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


이 속성에 대한 설명은 [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/xform\#getHeight--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


이 속성에 대한 설명은 [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


이 속성에 대한 설명은 [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


이 속성에 대한 설명은 [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


이 속성에 대한 설명은 [getPinX()](../../com.aspose.diagram/xform\#getPinX--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


이 속성에 대한 설명은 [getPinY()](../../com.aspose.diagram/xform\#getPinY--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


이 속성에 대한 설명은 [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/xform\#getWidth--)을 참조하십시오.

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

