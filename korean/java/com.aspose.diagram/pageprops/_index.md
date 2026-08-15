---
title: PageProps
second_title: Aspose.Diagram for Java API 참조
description: 페이지 너비, 높이 및 스케일과 같은 페이지 속성을 제어하는 셀을 포함합니다.
type: docs
weight: 268
url: /ko/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

페이지 너비, 높이 및 축척과 같은 페이지 속성을 제어하는 셀을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDrawingResizeType()](#getDrawingResizeType--) | 그리기 페이지가 다이어그램에 맞게 자동으로 크기가 조정되는지를 결정합니다. |
| [getDrawingScale()](#getDrawingScale--) | 현재 도면 스케일에서 도면 단위의 값을 나타냅니다. |
| [getDrawingScaleType()](#getDrawingScaleType--) | 페이지에 사용할 그리기 축척 유형을 지정합니다. |
| [getDrawingSizeType()](#getDrawingSizeType--) | 페이지의 그리기 크기를 지정합니다. |
| [getInhibitSnap()](#getInhibitSnap--) | 전경 페이지의 도형이 페이지의 다른 객체 및 배경 페이지의 도형에 스냅되는지 여부를 지정합니다. |
| [getPageHeight()](#getPageHeight--) | 도면 단위로 페이지 높이를 지정합니다. |
| [getPageScale()](#getPageScale--) | 현재 도면 스케일에서 기본 페이지 단위의 값을 지정합니다. |
| [getPageWidth()](#getPageWidth--) | 도면 단위로 페이지 너비를 지정합니다. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | 기본 페이지 그림자 유형이 적용될 때 비스듬한 방향의 각도를 지정하는 숫자를 포함합니다. |
| [getShdwOffsetX()](#getShdwOffsetX--) | 도형의 그림자 드롭이 도형으로부터 수평으로 오프셋되는 거리를 페이지 단위로 지정합니다. |
| [getShdwOffsetY()](#getShdwOffsetY--) | 도형의 그림자 드롭이 도형으로부터 수직으로 오프셋되는 거리를 페이지 단위로 지정합니다. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | 도형 그림자를 확대하거나 축소할 비율을 지정합니다. |
| [getShdwType()](#getShdwType--) | 페이지에 대한 기본 그림자 유형을 나타냅니다. |
| [getUIVisibility()](#getUIVisibility--) | 페이지 이름이 사용자 인터페이스(UI)에 표시되는지 여부를 결정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/pageprops\#getDel--)을(를) 참조하십시오. |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


그리기 페이지가 다이어그램에 맞게 자동으로 크기가 조정되는지를 결정합니다.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


현재 도면 스케일에서 도면 단위의 값을 나타냅니다. 페이지의 도면 스케일은 PageScale 요소에 포함된 페이지 단위와 도면 단위의 비율입니다. 이 요소의 단위는 페이지의 기본 길이(DL) 단위를 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


페이지에 사용할 그리기 축척 유형을 지정합니다.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


페이지의 그리기 크기를 지정합니다.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


전경 페이지의 도형이 페이지의 다른 객체 및 배경 페이지의 도형에 스냅되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


도면 단위로 페이지 높이를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


현재 도면 스케일에서 기본 페이지 단위의 값을 지정합니다. 페이지의 도면 스케일은 PageScale 요소에 있는 페이지 단위와 DrawingScale 요소에 표시된 도면 단위의 비율입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


도면 단위로 페이지 너비를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


기본 페이지 그림자 유형이 적용될 때 비스듬한 방향의 각도를 지정하는 숫자를 포함합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


도형의 그림자 드롭이 도형으로부터 수평으로 오프셋되는 거리를 페이지 단위로 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


도형의 그림자 드롭이 도형으로부터 수직으로 오프셋되는 거리를 페이지 단위로 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


도형 그림자를 확대하거나 축소할 비율을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


페이지에 대한 기본 그림자 유형을 나타냅니다.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


페이지 이름이 사용자 인터페이스(UI)에 표시되는지 여부를 결정합니다. 값이 1이면 페이지가 보이지 않으며, 값이 0이면 페이지가 표시됩니다.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/pageprops\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

