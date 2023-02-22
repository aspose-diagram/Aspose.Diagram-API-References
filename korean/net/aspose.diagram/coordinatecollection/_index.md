---
title: CoordinateCollection
second_title: .NET API 참조용 Aspose.Diagram
description: 좌표 수집.
type: docs
weight: 1040
url: /ko/net/aspose.diagram/coordinatecollection/
---
## CoordinateCollection class

좌표 수집.

```csharp
public class CoordinateCollection : Collection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArcToCol](../../aspose.diagram/coordinatecollection/arctocol/) { get; } | 각각 X, Y 및 A 요소로 표시되는 원호의 x 및 y 좌표와 활을 포함합니다. |
| [Count](../../aspose.diagram/collection/count/) { get; } | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [EllipseCol](../../aspose.diagram/coordinatecollection/ellipsecol/) { get; } | 타원의 중심점과 타원의 두 점의 x 및 y 좌표를 지정하는 요소를 포함합니다. |
| [EllipticalArcToCol](../../aspose.diagram/coordinatecollection/ellipticalarctocol/) { get; } | 타원형 호에 대한 정보를 지정하는 요소를 포함합니다. |
| [InfiniteLineCol](../../aspose.diagram/coordinatecollection/infinitelinecol/) { get; } | 무한선에 있는 두 점의 x 좌표와 y 좌표를 지정하는 요소를 포함합니다. X 및 Y 요소는 첫 번째 지점의 x 및 y 좌표를 지정하고 A 및 B 요소는 두 번째 지점의 x 및 y 좌표를 지정합니다. |
| [Item](../../aspose.diagram/coordinatecollection/item/) { get; } | 지정된 인덱스에서 요소를 가져옵니다. |
| [LineToCol](../../aspose.diagram/coordinatecollection/linetocol/) { get; } | 직선 세그먼트의 끝 꼭지점에 대한 x 및 y 좌표를 포함합니다. 이러한 좌표는 각각 X 및 Y 요소에 포함됩니다. |
| [MoveToCol](../../aspose.diagram/coordinatecollection/movetocol/) { get; } | 모양의 첫 번째 꼭지점의 x 및 y 좌표를 포함하거나 경로에서 중단된 후 첫 번째 꼭지점의 x 및 y 좌표를 포함합니다. |
| [NURBSToCol](../../aspose.diagram/coordinatecollection/nurbstocol/) { get; } | x 및 y 좌표, 마지막에서 두 번째 매듭의 위치, 마지막 추의 위치, 첫 번째 매듭의 위치, 첫 번째 추의 위치, 비균일 합리적 B-스플라인(NURBS)의 공식을 포함합니다. 이 정보는 각각 X, Y, A, B, C, D 및 E 요소에 지정됩니다. |
| [PolylineToCol](../../aspose.diagram/coordinatecollection/polylinetocol/) { get; } | 폴리라인 및 폴리라인 수식의 마지막 지점에 대한 x 및 y 좌표를 포함합니다. 좌표는 X 및 Y 요소에 지정되고 수식은 A 요소에 지정됩니다. |
| [RelCubBezToCol](../../aspose.diagram/coordinatecollection/relcubbeztocol/) { get; } | RelCubBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [RelEllipticalArcToCol](../../aspose.diagram/coordinatecollection/relellipticalarctocol/) { get; } | 타원형 호에 대한 정보를 지정하는 요소를 포함합니다.좌표는 상대 좌표로 지정됩니다. |
| [RelLineToCol](../../aspose.diagram/coordinatecollection/rellinetocol/) { get; } | 직선 세그먼트의 끝 꼭지점에 대한 x 및 y 좌표를 포함합니다. 이러한 좌표는 각각 X 및 Y 요소에 포함됩니다.좌표는 상대 좌표로 지정됩니다. |
| [RelMoveToCol](../../aspose.diagram/coordinatecollection/relmovetocol/) { get; } | 모양의 첫 번째 꼭지점의 x 및 y 좌표를 포함하거나 경로에서 중단 후 첫 번째 꼭지점의 x 및 y 좌표를 포함합니다.좌표는 상대 좌표로 지정됩니다. |
| [RelQuadBezToCol](../../aspose.diagram/coordinatecollection/relquadbeztocol/) { get; } | RelQuadBezTo의 점에 대한 x 및 y 좌표를 포함합니다. 좌표는 상대 좌표로 지정됩니다. |
| [SplineKnotCol](../../aspose.diagram/coordinatecollection/splineknotcol/) { get; } | 각각 X, Y 및 A 요소로 표시되는 스플라인 제어점 및 스플라인 매듭의 x 및 y 좌표를 포함합니다. |
| [SplineStartCol](../../aspose.diagram/coordinatecollection/splinestartcol/) { get; } | 스플라인의 두 번째 제어점, 두 번째 매듭, 첫 번째 매듭, 마지막 매듭 및 스플라인 각도에 대한 x 및 y 좌표를 포함합니다. 이 정보는 각각 X, Y, A, B, C 및 D 요소에 포함되어 있습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.diagram/coordinatecollection/add/#add)(ArcTo) | 컬렉션에 ArcTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_1)(Coordinate) | 컬렉션에 좌표 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_2)(Ellipse) | 컬렉션에 타원 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_3)(EllipticalArcTo) | 컬렉션에 EllipticalArcTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_4)(InfiniteLine) | 컬렉션에 InfiniteLine 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_5)(LineTo) | 컬렉션에 LineTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_6)(MoveTo) | 컬렉션에 MoveTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_7)(NURBSTo) | 컬렉션에 NURBSTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_8)(PolylineTo) | 컬렉션에 PolylineTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_9)(RelCubBezTo) | 컬렉션에 RelCubBezTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_10)(RelEllipticalArcTo) | 컬렉션에 RelEllipticalArcTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_11)(RelLineTo) | 컬렉션에 RelLineTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_12)(RelMoveTo) | 컬렉션에 RelMoveTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_13)(RelQuadBezTo) | 컬렉션에 RelQuadBezTo 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_14)(SplineKnot) | 컬렉션에 SplineKnot 개체를 추가합니다. |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_15)(SplineStart) | 컬렉션에 SplineStart 개체를 추가합니다. |
| [Clear](../../aspose.diagram/collection/clear/)() | 컬렉션에서 모든 요소를 제거합니다. |
| [GetEnumerator](../../aspose.diagram/collection/getenumerator/)() | 제네릭이 아닌 컬렉션에 대한 단순 반복을 지원합니다. |
| [IsExist](../../aspose.diagram/collection/isexist/)(int) | 컬렉션에 있는 항목입니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove)(ArcTo) | 컬렉션에서 ArcTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_1)(Coordinate) | 컬렉션에서 좌표 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_2)(Ellipse) | 컬렉션에서 타원 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_3)(EllipticalArcTo) | 컬렉션에서 EllipticalArcTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_4)(InfiniteLine) | 컬렉션에서 InfiniteLine 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_5)(LineTo) | 컬렉션에서 LineTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_6)(MoveTo) | 컬렉션에서 MoveTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_7)(NURBSTo) | 컬렉션에서 NURBSTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_8)(PolylineTo) | 컬렉션에서 PolylineTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_9)(RelCubBezTo) | 컬렉션에서 RelCubBezTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_10)(RelEllipticalArcTo) | 컬렉션에서 RelEllipticalArcTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_11)(RelLineTo) | 컬렉션에서 RelLineTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_12)(RelMoveTo) | 컬렉션에서 RelMoveTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_13)(RelQuadBezTo) | 컬렉션에서 RelQuadBezTo 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_14)(SplineKnot) | 컬렉션에서 SplineKnot 개체를 제거합니다. |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_15)(SplineStart) | 컬렉션에서 SplineStart 개체를 제거합니다. |

### 또한보십시오

* class [Collection](../collection/)
* 네임스페이스 [Aspose.Diagram](../../aspose.diagram/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
