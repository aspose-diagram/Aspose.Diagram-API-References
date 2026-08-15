---
title: CoordinateCollection
second_title: Aspose.Diagram لـ Java API Reference
description: مجموعة الإحداثيات.
type: docs
weight: 102
url: /ar/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

مجموعة الإحداثيات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | أضف كائن ArcTo إلى المجموعة. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | أضف كائن Coordinate إلى المجموعة. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | أضف كائن Ellipse إلى المجموعة. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | أضف كائن EllipticalArcTo إلى المجموعة. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | أضف كائن InfiniteLine إلى المجموعة. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | أضف كائن LineTo إلى المجموعة. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | أضف كائن MoveTo إلى المجموعة. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | أضف كائن NURBSTo إلى المجموعة. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | أضف كائن PolylineTo إلى المجموعة. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | أضف كائن RelCubBezTo إلى المجموعة. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | أضف كائن RelEllipticalArcTo إلى المجموعة. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | أضف كائن RelLineTo إلى المجموعة. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | أضف كائن RelMoveTo إلى المجموعة. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | أضف كائن RelQuadBezTo إلى المجموعة. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | أضف كائن SplineKnot إلى المجموعة. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | أضف كائن SplineStart إلى المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getArcToCol()](#getArcToCol--) | يحتوي على إحداثيات x و y وقوس القوس الدائري الممثلة على التوالي بعناصر X و Y و A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [getEllipseCol()](#getEllipseCol--) | يحتوي على عناصر تحدد إحداثيات x و y لنقطة مركز القطعة البيضاوية ونقطتين على القطعة. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | يحتوي على عناصر تحدد معلومات حول قوس بيضاوي. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | يحتوي على عناصر تحدد إحداثيات x و y لنقطتين على خط لا نهائي. |
| [getLineToCol()](#getLineToCol--) | يحتوي على إحداثيات x و y للرأس النهائي لقطعة خط مستقيم. |
| [getMoveToCol()](#getMoveToCol--) | يحتوي على إحداثيات x و y للرأس الأول لشكل، أو على إحداثيات x و y للرأس الأول بعد انقطاع في المسار. |
| [getNURBSToCol()](#getNURBSToCol--) | يحتوي على إحداثيات x و y، موقع العقدة قبل الأخيرة، موقع الوزن الأخير، موقع العقدة الأولى، موقع الوزن الأول، والصيغة للمنحنى B-spline النسبي غير المتجانس (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | يحتوي على إحداثيات x و y للنقطة الأخيرة من خط متعدد و صيغة الخط المتعدد. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | يحتوي على إحداثيات x و y لنقاط RelCubBezTo. يتم تحديد الإحداثيات كإحداثيات نسبية. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | يحتوي على عناصر تحدد معلومات حول قوس إهليلجي. يتم تحديد الإحداثيات كإحداثيات نسبية. |
| [getRelLineToCol()](#getRelLineToCol--) | يحتوي على إحداثيات x و y للرأس النهائي لقطعة خط مستقيم. |
| [getRelMoveToCol()](#getRelMoveToCol--) | تحتوي على إحداثيات x و y للرأس الأول للشكل، أو تحتوي على إحداثيات x و y للرأس الأول بعد انقطاع في المسار. يتم تحديد الإحداثيات كإحداثيات نسبية. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | يحتوي على إحداثيات x و y لنقاط RelQuadBezTo. يتم تحديد الإحداثيات كإحداثيات نسبية. |
| [getSplineKnotCol()](#getSplineKnotCol--) | يحتوي على إحداثيات x و y لنقطة التحكم في المنحنى ولقطة المنحنى، ممثلة بعناصر X و Y و A على التوالي. |
| [getSplineStartCol()](#getSplineStartCol--) | يحتوي على إحداثيات x و y للنقطة التحكمية الثانية للمنحنى، القطة الثانية، القطة الأولى، القطة الأخيرة، ودرجة المنحنى. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | هل يوجد عنصر في المجموعة. |
| [iterator()](#iterator--) | يدعم تكرارًا بسيطًا على مجموعة غير عامة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | أزل كائن ArcTo من المجموعة. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | أزل كائن Coordinate من المجموعة. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | أزل كائن Ellipse من المجموعة. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | أزل كائن EllipticalArcTo من المجموعة. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | أزل كائن InfiniteLine من المجموعة. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | أزل كائن LineTo من المجموعة. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | أزل كائن MoveTo من المجموعة. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | أزل كائن NURBSTo من المجموعة. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | أزل كائن PolylineTo من المجموعة. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | أزل كائن RelCubBezTo من المجموعة. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | أزل كائن RelEllipticalArcTo من المجموعة. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | أزل كائن RelLineTo من المجموعة. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | أزل كائن RelMoveTo من المجموعة. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | أزل كائن RelQuadBezTo من المجموعة. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | أزل كائن SplineKnot من المجموعة. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | أزل كائن SplineStart من المجموعة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


أضف كائن ArcTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


أضف كائن Coordinate إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


أضف كائن Ellipse إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


أضف كائن EllipticalArcTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


أضف كائن InfiniteLine إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


أضف كائن LineTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


أضف كائن MoveTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


أضف كائن NURBSTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


أضف كائن PolylineTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


أضف كائن RelCubBezTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


أضف كائن RelEllipticalArcTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


أضف كائن RelLineTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


أضف كائن RelMoveTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


أضف كائن RelQuadBezTo إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


أضف كائن SplineKnot إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


أضف كائن SplineStart إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


يزيل جميع العناصر من المجموعة.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


يحصل على العنصر في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


يحتوي على إحداثيات x و y وقوس القوس الدائري الممثلة على التوالي بعناصر X و Y و A.

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


يحصل على عدد العناصر الموجودة فعليًا في المجموعة.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


يحتوي على عناصر تحدد إحداثيات x و y لنقطة مركز القطعة البيضاوية ونقطتين على القطعة.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


يحتوي على عناصر تحدد معلومات حول قوس بيضاوي.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


يحتوي على عناصر تحدد إحداثيات x و y لنقطتين على خط لا نهائي. تحدد عناصر X و Y إحداثيات x و y للنقطة الأولى، وتحدد عناصر A و B إحداثيات x و y للنقطة الثانية.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


يحتوي على إحداثيات x و y للرأس النهائي لقطعة خط مستقيم. تُحفظ هذه الإحداثيات في العنصرين X و Y على التوالي.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


يحتوي على إحداثيات x و y للرأس الأول لشكل، أو على إحداثيات x و y للرأس الأول بعد انقطاع في المسار.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


يحتوي على إحداثيات x و y، موقع العقدة قبل الأخيرة، موقع الوزن الأخير، موقع العقدة الأولى، موقع الوزن الأول، والصيغة لـ nonuniform rational B-spline (NURBS). يتم تحديد هذه المعلومات في العناصر X و Y و A و B و C و D و E على التوالي.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


يحتوي على إحداثيات x و y للنقطة الأخيرة من خط متعدد وصيغة الخط المتعدد. يتم تحديد الإحداثيات في عناصر X و Y، ويتم تحديد الصيغة في العنصر A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


يحتوي على إحداثيات x و y لنقاط RelCubBezTo. يتم تحديد الإحداثيات كإحداثيات نسبية.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


يحتوي على عناصر تحدد معلومات حول قوس إهليلجي. يتم تحديد الإحداثيات كإحداثيات نسبية.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


يحتوي على إحداثيات x و y للرأس النهائي لقطعة خط مستقيم. تُحفظ هذه الإحداثيات في العنصرين X و Y على التوالي. الإحداثيات محددة كإحداثيات نسبية.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


تحتوي على إحداثيات x و y للرأس الأول للشكل، أو تحتوي على إحداثيات x و y للرأس الأول بعد انقطاع في المسار. يتم تحديد الإحداثيات كإحداثيات نسبية.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


يحتوي على إحداثيات x و y لنقاط RelQuadBezTo. يتم تحديد الإحداثيات كإحداثيات نسبية.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


يحتوي على إحداثيات x و y لنقطة التحكم في المنحنى ولقطة المنحنى، ممثلة بعناصر X و Y و A على التوالي.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


يحتوي على إحداثيات x و y للنقطة التحكمية الثانية للمنحنى، عقدته الثانية، عقدته الأولى، العقدة الأخيرة، ودرجة المنحنى. هذه المعلومات موجودة في العناصر X و Y و A و B و C و D على التوالي.

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


هل يوجد عنصر في المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس العنصر. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


يدعم تكرارًا بسيطًا على مجموعة غير عامة.

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


أزل كائن ArcTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


أزل كائن Coordinate من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


أزل كائن Ellipse من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


أزل كائن EllipticalArcTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


أزل كائن InfiniteLine من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


أزل كائن LineTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


أزل كائن MoveTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


أزل كائن NURBSTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


أزل كائن PolylineTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


أزل كائن RelCubBezTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


أزل كائن RelEllipticalArcTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


أزل كائن RelLineTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


أزل كائن RelMoveTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


أزل كائن RelQuadBezTo من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


أزل كائن SplineKnot من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


أزل كائن SplineStart من المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

