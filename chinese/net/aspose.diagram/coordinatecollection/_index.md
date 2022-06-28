---
title: CoordinateCollection
second_title: Aspose.Diagram for .NET API 参考
description: 坐标集合
type: docs
weight: 1030
url: /zh/net/aspose.diagram/coordinatecollection/
---
## CoordinateCollection class

坐标集合。

```csharp
public class CoordinateCollection : Collection
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ArcToCol](../../aspose.diagram/coordinatecollection/arctocol) { get; } | 包含分别由 X、Y 和 A 元素表示的圆弧的 x 和 y 坐标和弓形。 |
| [Count](../../aspose.diagram/collection/count) { get; } | 获取集合中实际包含的元素数量。 |
| [EllipseCol](../../aspose.diagram/coordinatecollection/ellipsecol) { get; } | 包含指定椭圆中心点和椭圆上两个点的 x 和 y 坐标的元素。 |
| [EllipticalArcToCol](../../aspose.diagram/coordinatecollection/ellipticalarctocol) { get; } | 包含指定椭圆弧信息的元素。 |
| [InfiniteLineCol](../../aspose.diagram/coordinatecollection/infinitelinecol) { get; } | 包含指定无限线上两点的 x 和 y 坐标的元素。 X 和 Y 元素指定第一个点的 x 和 y 坐标，A 和 B 元素指定第二个点的 x 和 y 坐标。 |
| [Item](../../aspose.diagram/coordinatecollection/item) { get; } | 获取指定索引处的元素。 |
| [LineToCol](../../aspose.diagram/coordinatecollection/linetocol) { get; } | 包含直线段结束顶点的 x 和 y 坐标。这些坐标分别包含在 X 和 Y 元素中。 |
| [MoveToCol](../../aspose.diagram/coordinatecollection/movetocol) { get; } | 包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标. |
| [NURBSToCol](../../aspose.diagram/coordinatecollection/nurbstocol) { get; } | 包含 x 和 y 坐标，倒数第二个结的位置，最后一个重量的位置，第一个结的位置，第一个重量的位置，以及非均匀有理 B 样条 (NURBS) 的公式。此信息分别在 X、Y、A、B、C、D 和 E 元素中指定。 |
| [PolylineToCol](../../aspose.diagram/coordinatecollection/polylinetocol) { get; } | 包含折线最后一点的 x 和 y 坐标以及折线公式。坐标在 X 和 Y 元素中指定，公式在 A 元素中指定。 |
| [RelCubBezToCol](../../aspose.diagram/coordinatecollection/relcubbeztocol) { get; } | 包含 RelCubBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。 |
| [RelEllipticalArcToCol](../../aspose.diagram/coordinatecollection/relellipticalarctocol) { get; } | 包含指定椭圆弧信息的元素。坐标指定为相对坐标。 |
| [RelLineToCol](../../aspose.diagram/coordinatecollection/rellinetocol) { get; } | 包含直线段结束顶点的 x 和 y 坐标。这些坐标分别包含在 X 和 Y 元素中。坐标指定为相对坐标。 |
| [RelMoveToCol](../../aspose.diagram/coordinatecollection/relmovetocol) { get; } | 包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标.坐标被指定为相对坐标。 |
| [RelQuadBezToCol](../../aspose.diagram/coordinatecollection/relquadbeztocol) { get; } | 包含 RelQuadBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。 |
| [SplineKnotCol](../../aspose.diagram/coordinatecollection/splineknotcol) { get; } | 包含样条控制点和样条结的 x 和 y 坐标，分别由 X、Y 和 A 元素表示。 |
| [SplineStartCol](../../aspose.diagram/coordinatecollection/splinestartcol) { get; } | 包含样条曲线的第二个控制点、第二个节点、第一个节点、最后一个节点以及样条曲线的度数的 x 和 y 坐标。此信息分别包含在 X、Y、A、B、C 和 D 元素中。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.diagram/coordinatecollection/add#add)(ArcTo) | 在集合中添加 ArcTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_1)(Coordinate) | 在集合中添加坐标对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_2)(Ellipse) | 在集合中添加 Ellipse 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_3)(EllipticalArcTo) | 在集合中添加 EllipticalArcTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_4)(InfiniteLine) | 在集合中添加 InfiniteLine 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_5)(LineTo) | 在集合中添加 LineTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_6)(MoveTo) | 在集合中添加 MoveTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_7)(NURBSTo) | 在集合中添加 NURBSTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_8)(PolylineTo) | 在集合中添加 PolylineTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_9)(RelCubBezTo) | 在集合中添加 RelCubBezTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_10)(RelEllipticalArcTo) | 在集合中添加 RelEllipticalArcTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_11)(RelLineTo) | 在集合中添加 RelLineTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_12)(RelMoveTo) | 在集合中添加 RelMoveTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_13)(RelQuadBezTo) | 在集合中添加 RelQuadBezTo 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_14)(SplineKnot) | 在集合中添加 SplineKnot 对象。 |
| [Add](../../aspose.diagram/coordinatecollection/add#add_15)(SplineStart) | 在集合中添加 SplineStart 对象。 |
| [Clear](../../aspose.diagram/collection/clear)() | 从集合中删除所有元素。 |
| [GetEnumerator](../../aspose.diagram/collection/getenumerator)() | 支持对非泛型集合的简单迭代。 |
| [IsExist](../../aspose.diagram/collection/isexist)(int) | 是集合中存在的项目。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove)(ArcTo) | 从集合中移除 ArcTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_1)(Coordinate) | 从集合中移除坐标对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_2)(Ellipse) | 从集合中移除 Ellipse 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_3)(EllipticalArcTo) | 从集合中移除 EllipticalArcTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_4)(InfiniteLine) | 从集合中移除 InfiniteLine 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_5)(LineTo) | 从集合中移除 LineTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_6)(MoveTo) | 从集合中移除 MoveTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_7)(NURBSTo) | 从集合中移除 NURBSTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_8)(PolylineTo) | 从集合中移除 PolylineTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_9)(RelCubBezTo) | 从集合中移除 RelCubBezTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_10)(RelEllipticalArcTo) | 从集合中移除 RelEllipticalArcTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_11)(RelLineTo) | 从集合中移除 RelLineTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_12)(RelMoveTo) | 从集合中移除 RelMoveTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_13)(RelQuadBezTo) | 从集合中移除 RelQuadBezTo 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_14)(SplineKnot) | 从集合中移除 SplineKnot 对象。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove#remove_15)(SplineStart) | 从集合中移除 SplineStart 对象。 |

### 也可以看看

* class [Collection](../collection)
* 命名空间 [Aspose.Diagram](../../aspose.diagram)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
