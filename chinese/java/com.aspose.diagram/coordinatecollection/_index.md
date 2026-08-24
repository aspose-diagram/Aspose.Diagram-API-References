---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API 参考
description: 坐标集合。
type: docs
weight: 102
url: /zh/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

坐标集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | 在集合中添加 ArcTo 对象。 |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | 在集合中添加 Coordinate 对象。 |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | 在集合中添加 Ellipse 对象。 |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | 在集合中添加 EllipticalArcTo 对象。 |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | 在集合中添加 InfiniteLine 对象。 |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | 在集合中添加 LineTo 对象。 |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | 在集合中添加 MoveTo 对象。 |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | 在集合中添加 NURBSTo 对象。 |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | 在集合中添加 PolylineTo 对象。 |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | 在集合中添加 RelCubBezTo 对象。 |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | 在集合中添加 RelEllipticalArcTo 对象。 |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | 在集合中添加 RelLineTo 对象。 |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | 在集合中添加 RelMoveTo 对象。 |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | 在集合中添加 RelQuadBezTo 对象。 |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | 在集合中添加 SplineKnot 对象。 |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | 在集合中添加 SplineStart 对象。 |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getArcToCol()](#getArcToCol--) | 包含由 X、Y 和 A 元素分别表示的圆弧的 x、y 坐标和弧度。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getEllipseCol()](#getEllipseCol--) | 包含指定椭圆中心点以及椭圆上两点的 x、y 坐标的元素。 |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | 包含指定椭圆弧信息的元素。 |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | 包含指定无限直线上两点的 x 和 y 坐标的元素。 |
| [getLineToCol()](#getLineToCol--) | 包含直线段结束顶点的 x 和 y 坐标。 |
| [getMoveToCol()](#getMoveToCol--) | 包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标。 |
| [getNURBSToCol()](#getNURBSToCol--) | 包含 x 和 y 坐标、倒数第二个节点的位置、最后一个权重的位置、第一个节点的位置、第一权重的位置，以及非均匀有理 B 样条 (NURBS) 的公式。 |
| [getPolylineToCol()](#getPolylineToCol--) | 包含折线最后一点的 x 和 y 坐标以及折线公式。 |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | 包含 RelCubBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。 |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | 包含指定椭圆弧信息的元素。坐标以相对坐标指定。 |
| [getRelLineToCol()](#getRelLineToCol--) | 包含直线段结束顶点的 x 和 y 坐标。 |
| [getRelMoveToCol()](#getRelMoveToCol--) | 包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标。坐标以相对坐标指定。 |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | 包含 RelQuadBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。 |
| [getSplineKnotCol()](#getSplineKnotCol--) | 包含样条曲线控制点和结点的 x、y 坐标，分别由 X、Y 和 A 元素表示。 |
| [getSplineStartCol()](#getSplineStartCol--) | 包含样条曲线第二控制点、第二结点、第一结点、最后结点以及样条的阶数的 x、y 坐标。 |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | 支持对非泛型集合进行简单迭代。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | 从集合中移除 ArcTo 对象。 |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | 从集合中移除 Coordinate 对象。 |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | 从集合中移除 Ellipse 对象。 |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | 从集合中移除 EllipticalArcTo 对象。 |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | 从集合中移除 InfiniteLine 对象。 |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | 从集合中移除 LineTo 对象。 |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | 从集合中移除 MoveTo 对象。 |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | 从集合中移除 NURBSTo 对象。 |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | 从集合中移除 PolylineTo 对象。 |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | 从集合中移除 RelCubBezTo 对象。 |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | 从集合中移除 RelEllipticalArcTo 对象。 |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | 从集合中移除 RelLineTo 对象。 |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | 从集合中移除 RelMoveTo 对象。 |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | 从集合中移除 RelQuadBezTo 对象。 |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | 从集合中移除 SplineKnot 对象。 |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | 从集合中移除 SplineStart 对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


在集合中添加 ArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


在集合中添加 Coordinate 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


在集合中添加 Ellipse 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


在集合中添加 EllipticalArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


在集合中添加 InfiniteLine 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


在集合中添加 LineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


在集合中添加 MoveTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


在集合中添加 NURBSTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


在集合中添加 PolylineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


在集合中添加 RelCubBezTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


在集合中添加 RelEllipticalArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


在集合中添加 RelLineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


在集合中添加 RelMoveTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


在集合中添加 RelQuadBezTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


在集合中添加 SplineKnot 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


在集合中添加 SplineStart 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Gets the element at the specified index.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


包含由 X、Y 和 A 元素分别表示的圆弧的 x、y 坐标和弧度。

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


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


包含指定椭圆中心点以及椭圆上两点的 x、y 坐标的元素。

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


包含指定椭圆弧信息的元素。

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


包含指定无限直线上两点的 x 和 y 坐标的元素。X 和 Y 元素指定第一点的 x 和 y 坐标，A 和 B 元素指定第二点的 x 和 y 坐标。

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


包含直线段终点顶点的 x 和 y 坐标。这些坐标分别位于 X 和 Y 元素中。

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标。

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


包含 x 和 y 坐标、第二个结点的位置、最后权重的位置、第一结点的位置、第一权重的位置，以及非均匀有理 B 样条 (NURBS) 的公式。这些信息分别在 X、Y、A、B、C、D 和 E 元素中指定。

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


包含折线最后一点的 x 和 y 坐标以及折线公式。坐标在 X 和 Y 元素中指定，公式在 A 元素中指定。

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


包含 RelCubBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


包含指定椭圆弧信息的元素。坐标以相对坐标指定。

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


包含直线段终点顶点的 x 和 y 坐标。这些坐标分别位于 X 和 Y 元素中。坐标指定为相对坐标。

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


包含形状第一个顶点的 x 和 y 坐标，或包含路径中断后第一个顶点的 x 和 y 坐标。坐标以相对坐标指定。

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


包含 RelQuadBezTo 点的 x 和 y 坐标。坐标指定为相对坐标。

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


包含样条曲线控制点和结点的 x、y 坐标，分别由 X、Y 和 A 元素表示。

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


包含样条曲线第二控制点、第二节点、第一节点、最后节点的 x 和 y 坐标以及样条的阶数。这些信息分别存放在 X、Y、A、B、C 和 D 元素中。

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


Is exist item in the collection.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 元素的索引。 |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


支持对非泛型集合进行简单迭代。

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


从集合中移除 ArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


从集合中移除 Coordinate 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


从集合中移除 Ellipse 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


从集合中移除 EllipticalArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


从集合中移除 InfiniteLine 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


从集合中移除 LineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


从集合中移除 MoveTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


从集合中移除 NURBSTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


从集合中移除 PolylineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


从集合中移除 RelCubBezTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


从集合中移除 RelEllipticalArcTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


从集合中移除 RelLineTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


从集合中移除 RelMoveTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


从集合中移除 RelQuadBezTo 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


从集合中移除 SplineKnot 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


从集合中移除 SplineStart 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
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

