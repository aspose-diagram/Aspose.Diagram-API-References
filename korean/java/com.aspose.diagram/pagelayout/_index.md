---
title: PageLayout
second_title: Aspose.Diagram for Java API 참조
description: 페이지의 도형 및 연결선에 대한 페이지 레이아웃 설정을 제어하는 셀을 포함합니다. 여기에는 페이지의 모든 도형 사이 간격, 모든 연결선 사이 간격 및 모든 연결선의 라우팅 스타일이 포함됩니다.
type: docs
weight: 263
url: /ko/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

페이지의 도형 및 커넥터에 대한 레이아웃 설정을 제어하는 셀을 포함합니다. 예를 들어 페이지 내 모든 도형 간 간격, 모든 커넥터 간 간격, 그리고 모든 커넥터의 라우팅 스타일 등이 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수직 간격을 결정합니다. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수직 간격을 결정합니다. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | 사용자가 '도형 레이아웃'(도형 메뉴)을 선택하여 도형을 배치할 때 도형이 페이지에 배치되는 방식을 지정합니다. |
| [getBlockSizeX()](#getBlockSizeX--) | Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지에서 각 도형이 들어가야 하는 영역인 수직 블록 크기를 결정합니다. |
| [getBlockSizeY()](#getBlockSizeY--) | Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수평 간격을 결정합니다. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | 제어 핸들을 사용하여 도형을 조작할 때 어떤 도형이 부모인지 결정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDynamicsOff()](#getDynamicsOff--) | 배치 가능한 도형이 이동하고 연결선이 그리기 페이지의 다른 도형 및 연결선 주위를 재경로 지정할지 여부를 지정합니다. |
| [getEnableGrid()](#getEnableGrid--) | 사용자가 Lay Out Shapes (Shape 메뉴)를 선택할 때 Microsoft Visio가 내부 페이지 그리드를 기반으로 도형을 배치할지 여부를 지정합니다. |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | 동적 커넥터가 서로 겹쳐 라우팅될 경우 어느 커넥터를 간격을 두도록 할지 지정합니다. |
| [getLineAdjustTo()](#getLineAdjustTo--) | 동적 커넥터가 서로 겹쳐 라우팅될 경우 어느 커넥터를 서로 정렬하도록 할지 지정합니다. |
| [getLineJumpCode()](#getLineJumpCode--) | 로컬 라인 점프 스타일이 없는 그리기 페이지의 모든 커넥터에 대한 라인 점프 스타일을 지정합니다. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | 페이지의 동적 연결선 수평 구간에서 라인 점프 크기를 지정합니다. 이 값은 LineToLineX 요소 값의 백분율이며, 해당 요소는 그리기 페이지의 모든 연결선 간 수평 간격을 지정합니다. |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | 페이지의 동적 연결선 수직 구간에서 라인 점프 크기를 지정합니다. 이 값은 LineToLineY 요소 값의 백분율이며, 해당 요소는 그리기 페이지의 모든 연결선 간 수직 간격을 지정합니다. |
| [getLineJumpStyle()](#getLineJumpStyle--) | 그림 페이지에서 로컬 점프 방향을 적용하지 않은 동적 커넥터의 수평 구간에 대한 라인 점프 방향을 지정합니다. |
| [getLineRouteExt()](#getLineRouteExt--) | 페이지의 모든 커넥터에 대한 기본 외관을 지정합니다. |
| [getLineToLineX()](#getLineToLineX--) | 그리기 페이지의 동적 연결선 간 최소 수평 간격을 지정합니다. |
| [getLineToLineY()](#getLineToLineY--) | 그리기 페이지의 동적 연결선 간 최소 수직 간격을 지정합니다. |
| [getLineToNodeX()](#getLineToNodeX--) | 그리기 페이지의 동적 연결선과 도형 간 최소 수직 간격을 지정합니다. |
| [getLineToNodeY()](#getLineToNodeY--) | Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지에서 각 도형이 들어가야 하는 영역인 수평 블록 크기를 결정합니다. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | 그림 페이지에서 로컬 점프 방향을 적용하지 않은 수직 동적 커넥터에 대한 라인 점프 방향을 지정합니다. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | 그리기 페이지의 동적 연결선과 도형 간 최소 수평 간격을 지정합니다. |
| [getPageShapeSplit()](#getPageShapeSplit--) | 페이지의 도형을 자동으로 분할할 수 있는지 여부를 나타냅니다. |
| [getPlaceDepth()](#getPlaceDepth--) | 사용자가 배치 가능한 도형을 다른 배치 가능한 도형 근처로 끌어다 놓을 때 배치 가능한 도형이 멀어지도록 이동할지 여부를 지정합니다. |
| [getPlaceFlip()](#getPlaceFlip--) | Microsoft Visio에서 '도형 레이아웃' 명령을 사용하여 도형을 배치할 때 배치 가능한 도형이 페이지에서 뒤집히거나 회전하는 방식을 지정합니다. |
| [getPlaceStyle()](#getPlaceStyle--) | 로컬 라우팅 스타일이 없는 그리기 페이지의 모든 동적 커넥터에 대한 라우팅 스타일 및 방향을 지정합니다. |
| [getPlowCode()](#getPlowCode--) | 점프를 추가하려는 동적 커넥터를 결정합니다. |
| [getResizePage()](#getResizePage--) | 사용자가 Lay Out Shapes (Shapes 메뉴)를 선택한 후 페이지를 확대하여 그리기를 포함시킬지 여부를 지정합니다. |
| [getRouteStyle()](#getRouteStyle--) | 자동으로 레이아웃되는 그림에 대해 레이아웃을 만들기 전에 그림을 분석하는 방법을 지정하고 레이아웃 유형을 결정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--)을(를) 참조하십시오. |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수직 간격을 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수직 간격을 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


사용자가 '도형 레이아웃'(도형 메뉴)을 선택하여 도형을 배치할 때 도형이 페이지에 배치되는 방식을 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지에서 각 도형이 들어가야 하는 영역인 수직 블록 크기를 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지의 도형 간 수평 간격을 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


제어 핸들을 사용하여 도형을 조작할 때 어떤 도형이 부모인지 결정합니다. 이 요소는 그리기 페이지의 모든 도형에 대한 동작을 설정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


배치 가능한 도형이 이동하고 연결선이 그리기 페이지의 다른 도형 및 연결선 주위를 재경로 지정할지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


사용자가 Lay Out Shapes (Shape 메뉴)를 선택할 때 Microsoft Visio가 내부 페이지 그리드를 기반으로 도형을 배치할지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


동적 커넥터가 서로 겹쳐 라우팅될 경우 어느 커넥터를 간격을 두도록 할지 지정합니다.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


동적 커넥터가 서로 겹쳐 라우팅될 경우 어느 커넥터를 서로 정렬하도록 할지 지정합니다.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


로컬 라인 점프 스타일이 없는 그리기 페이지의 모든 커넥터에 대한 라인 점프 스타일을 지정합니다.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


페이지의 동적 연결선 수평 구간에서 라인 점프 크기를 지정합니다. 이 값은 LineToLineX 요소 값의 백분율이며, 해당 요소는 그리기 페이지의 모든 연결선 간 수평 간격을 지정합니다. 이 요소의 값은 0에서 10 사이입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


페이지의 동적 연결선 수직 구간에서 라인 점프 크기를 지정합니다. 이 값은 LineToLineY 요소 값의 백분율이며, 해당 요소는 그리기 페이지의 모든 연결선 간 수직 간격을 지정합니다. 이 요소는 0에서 10 사이의 값을 가질 수 있습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


그림 페이지에서 로컬 점프 방향을 적용하지 않은 동적 커넥터의 수평 구간에 대한 라인 점프 방향을 지정합니다.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


페이지의 모든 커넥터에 대한 기본 외관을 지정합니다.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


그리기 페이지의 동적 연결선 간 최소 수평 간격을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


그리기 페이지의 동적 연결선 간 최소 수직 간격을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


그리기 페이지의 동적 연결선과 도형 간 최소 수직 간격을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Microsoft Visio를 사용하여 도형을 배치할 때 그리기 페이지에서 각 도형이 들어가야 하는 영역인 수평 블록 크기를 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


그림 페이지에서 로컬 점프 방향을 적용하지 않은 수직 동적 커넥터에 대한 라인 점프 방향을 지정합니다.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


그리기 페이지의 동적 연결선과 도형 간 최소 수평 간격을 지정합니다.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


페이지의 도형을 자동으로 분할할 수 있는지 여부를 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


사용자가 배치 가능한 도형을 다른 배치 가능한 도형 근처로 끌어다 놓을 때 배치 가능한 도형이 멀어지도록 이동할지 여부를 지정합니다.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Microsoft Visio에서 'Lay Out Shapes' 명령을 사용하여 도형을 배치할 때 배치 가능한 도형이 페이지에서 어떻게 뒤집히거나 회전하는지를 지정합니다. 다음 16진수 값을 허용합니다.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


로컬 라우팅 스타일이 없는 그리기 페이지의 모든 동적 커넥터에 대한 라우팅 스타일 및 방향을 지정합니다.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


점프를 추가하려는 동적 커넥터를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


사용자가 Lay Out Shapes (Shapes 메뉴)를 선택한 후 페이지를 확대하여 그리기를 포함시킬지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


자동으로 레이아웃되는 그림에 대해 레이아웃을 만들기 전에 그림을 분석하는 방법을 지정하고 레이아웃 유형을 결정합니다.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--)을(를) 참조하십시오.

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

