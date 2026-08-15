---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API 참조
description: 좌표 컬렉션입니다.
type: docs
weight: 102
url: /ko/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

좌표 컬렉션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | 컬렉션에 ArcTo 객체를 추가합니다. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | 컬렉션에 Coordinate 객체를 추가합니다. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | 컬렉션에 Ellipse 객체를 추가합니다. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | 컬렉션에 EllipticalArcTo 객체를 추가합니다. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | 컬렉션에 InfiniteLine 객체를 추가합니다. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | 컬렉션에 LineTo 객체를 추가합니다. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | 컬렉션에 MoveTo 객체를 추가합니다. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | 컬렉션에 NURBSTo 객체를 추가합니다. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | 컬렉션에 PolylineTo 객체를 추가합니다. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | 컬렉션에 RelCubBezTo 객체를 추가합니다. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | 컬렉션에 RelEllipticalArcTo 객체를 추가합니다. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | 컬렉션에 RelLineTo 객체를 추가합니다. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | 컬렉션에 RelMoveTo 객체를 추가합니다. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | 컬렉션에 RelQuadBezTo 객체를 추가합니다. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | 컬렉션에 SplineKnot 객체를 추가합니다. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | 컬렉션에 SplineStart 객체를 추가합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 요소를 제거합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getArcToCol()](#getArcToCol--) | X, Y 및 A 요소에 각각 의해 표현되는 원호의 x 및 y 좌표와 활을 포함합니다. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [getEllipseCol()](#getEllipseCol--) | 타원의 중심점 및 타원 위의 두 점에 대한 x 및 y 좌표를 지정하는 요소를 포함합니다. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | 타원 호에 대한 정보를 지정하는 요소를 포함합니다. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | 무한선상의 두 점에 대한 x 및 y 좌표를 지정하는 요소를 포함합니다. |
| [getLineToCol()](#getLineToCol--) | 직선 세그먼트의 끝 정점의 x 및 y 좌표를 포함합니다. |
| [getMoveToCol()](#getMoveToCol--) | 도형의 첫 번째 정점의 x 및 y 좌표를 포함하거나, 경로 중단 후 첫 번째 정점의 x 및 y 좌표를 포함합니다. |
| [getNURBSToCol()](#getNURBSToCol--) | x 및 y 좌표, 두 번째에서 마지막 매듭의 위치, 마지막 가중치의 위치, 첫 번째 매듭의 위치, 첫 번째 가중치의 위치 및 비균일 유리 B-스플라인(NURBS)의 수식을 포함합니다. |
| [getPolylineToCol()](#getPolylineToCol--) | 폴리라인의 마지막 점과 폴리라인 수식의 x 및 y 좌표를 포함합니다. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | RelCubBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | 타원 호에 대한 정보를 지정하는 요소를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [getRelLineToCol()](#getRelLineToCol--) | 직선 세그먼트의 끝 정점의 x 및 y 좌표를 포함합니다. |
| [getRelMoveToCol()](#getRelMoveToCol--) | 도형의 첫 번째 정점의 x 및 y 좌표를 포함하거나, 경로에서 끊김 후 첫 번째 정점의 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | RelQuadBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [getSplineKnotCol()](#getSplineKnotCol--) | 스플라인의 제어점 및 스플라인의 매듭에 대한 x 및 y 좌표를 포함하며, 각각 X, Y 및 A 요소로 표시됩니다. |
| [getSplineStartCol()](#getSplineStartCol--) | 스플라인의 두 번째 제어점, 두 번째 매듭, 첫 번째 매듭, 마지막 매듭 및 스플라인 차수에 대한 x 및 y 좌표를 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | 컬렉션에 항목이 존재합니다. |
| [iterator()](#iterator--) | 비제네릭 컬렉션에 대한 간단한 반복을 지원합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | 컬렉션에서 ArcTo 객체를 제거합니다. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | 컬렉션에서 Coordinate 객체를 제거합니다. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | 컬렉션에서 Ellipse 객체를 제거합니다. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | 컬렉션에서 EllipticalArcTo 객체를 제거합니다. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | 컬렉션에서 InfiniteLine 객체를 제거합니다. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | 컬렉션에서 LineTo 객체를 제거합니다. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | 컬렉션에서 MoveTo 객체를 제거합니다. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | 컬렉션에서 NURBSTo 객체를 제거합니다. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | 컬렉션에서 PolylineTo 객체를 제거합니다. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | 컬렉션에서 RelCubBezTo 객체를 제거합니다. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | 컬렉션에서 RelEllipticalArcTo 객체를 제거합니다. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | 컬렉션에서 RelLineTo 객체를 제거합니다. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | 컬렉션에서 RelMoveTo 객체를 제거합니다. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | 컬렉션에서 RelQuadBezTo 객체를 제거합니다. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | 컬렉션에서 SplineKnot 객체를 제거합니다. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | 컬렉션에서 SplineStart 객체를 제거합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


컬렉션에 ArcTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


컬렉션에 Coordinate 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


컬렉션에 Ellipse 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


컬렉션에 EllipticalArcTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


컬렉션에 InfiniteLine 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


컬렉션에 LineTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


컬렉션에 MoveTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


컬렉션에 NURBSTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


컬렉션에 PolylineTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


컬렉션에 RelCubBezTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


컬렉션에 RelEllipticalArcTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


컬렉션에 RelLineTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


컬렉션에 RelMoveTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


컬렉션에 RelQuadBezTo 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


컬렉션에 SplineKnot 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


컬렉션에 SplineStart 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


컬렉션에서 모든 요소를 제거합니다.

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
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


X, Y 및 A 요소에 각각 의해 표현되는 원호의 x 및 y 좌표와 활을 포함합니다.

**Returns:**
[ArcToCollection](../../com.aspose.diagram/arctocollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


컬렉션에 실제로 포함된 요소 수를 가져옵니다.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


타원의 중심점 및 타원 위의 두 점에 대한 x 및 y 좌표를 지정하는 요소를 포함합니다.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


타원 호에 대한 정보를 지정하는 요소를 포함합니다.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


무한선상의 두 점에 대한 x 및 y 좌표를 지정하는 요소를 포함합니다. X와 Y 요소는 첫 번째 점의 x 및 y 좌표를 지정하고, A와 B 요소는 두 번째 점의 x 및 y 좌표를 지정합니다.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


직선 세그먼트의 끝 정점에 대한 x 및 y 좌표를 포함합니다. 이러한 좌표는 각각 X 및 Y 요소에 포함됩니다.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


도형의 첫 번째 정점의 x 및 y 좌표를 포함하거나, 경로 중단 후 첫 번째 정점의 x 및 y 좌표를 포함합니다.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


x 및 y 좌표, 두 번째 마지막 매듭 위치, 마지막 가중치 위치, 첫 번째 매듭 위치, 첫 번째 가중치 위치 및 비균일 유리 B-스플라인(NURBS) 공식을 포함합니다. 이 정보는 각각 X, Y, A, B, C, D, E 요소에 지정됩니다.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


폴리라인의 마지막 점의 x 및 y 좌표와 폴리라인 수식을 포함합니다. 좌표는 X 및 Y 요소에 지정되고, 수식은 A 요소에 지정됩니다.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


RelCubBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


타원 호에 대한 정보를 지정하는 요소를 포함합니다. 좌표는 상대 좌표로 지정됩니다.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


직선 세그먼트의 끝 정점에 대한 x 및 y 좌표를 포함합니다. 이러한 좌표는 각각 X 및 Y 요소에 포함됩니다. 좌표는 상대 좌표로 지정됩니다.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


도형의 첫 번째 정점의 x 및 y 좌표를 포함하거나, 경로에서 끊김 후 첫 번째 정점의 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


RelQuadBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


스플라인의 제어점 및 스플라인의 매듭에 대한 x 및 y 좌표를 포함하며, 각각 X, Y 및 A 요소로 표시됩니다.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


스플라인의 두 번째 제어점, 두 번째 매듭, 첫 번째 매듭, 마지막 매듭 및 스플라인 차수에 대한 x 및 y 좌표를 포함합니다. 이 정보는 각각 X, Y, A, B, C, D 요소에 포함됩니다.

**Returns:**
[SplineStartCollection](../../com.aspose.diagram/splinestartcollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


컬렉션에 항목이 존재합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 요소의 인덱스. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


비제네릭 컬렉션에 대한 간단한 반복을 지원합니다.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(ArcTo item) {#remove-com.aspose.diagram.ArcTo-}
```
public void remove(ArcTo item)
```


컬렉션에서 ArcTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


컬렉션에서 Coordinate 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


컬렉션에서 Ellipse 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


컬렉션에서 EllipticalArcTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


컬렉션에서 InfiniteLine 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


컬렉션에서 LineTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


컬렉션에서 MoveTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


컬렉션에서 NURBSTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


컬렉션에서 PolylineTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


컬렉션에서 RelCubBezTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


컬렉션에서 RelEllipticalArcTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


컬렉션에서 RelLineTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


컬렉션에서 RelMoveTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


컬렉션에서 RelQuadBezTo 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


컬렉션에서 SplineKnot 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


컬렉션에서 SplineStart 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

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

