---
title: CoordinateCollection
second_title: Справочник API Aspose.Diagram for Java
description: Коллекция координат.
type: docs
weight: 102
url: /ru/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Коллекция координат.
## Методы

| Метод | Описание |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Добавить объект ArcTo в коллекцию. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Добавить объект Coordinate в коллекцию. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Добавить объект Ellipse в коллекцию. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Добавить объект EllipticalArcTo в коллекцию. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Добавить объект InfiniteLine в коллекцию. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Добавить объект LineTo в коллекцию. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Добавить объект MoveTo в коллекцию. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Добавить объект NURBSTo в коллекцию. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Добавить объект PolylineTo в коллекцию. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Добавить объект RelCubBezTo в коллекцию. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Добавьте объект RelEllipticalArcTo в коллекцию. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Добавьте объект RelLineTo в коллекцию. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Добавьте объект RelMoveTo в коллекцию. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Добавьте объект RelQuadBezTo в коллекцию. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Добавьте объект SplineKnot в коллекцию. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Добавьте объект SplineStart в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Получает элемент по указанному индексу. |
| [getArcToCol()](#getArcToCol--) | Содержит координаты x и y и прогиб дуги круга, представленные соответственно элементами X, Y и A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [getEllipseCol()](#getEllipseCol--) | Содержит элементы, указывающие координаты x и y центра эллипса и двух точек на эллипсе. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Содержит элементы, задающие информацию об эллиптической дуге. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Содержит элементы, указывающие x- и y-координаты двух точек на бесконечной прямой. |
| [getLineToCol()](#getLineToCol--) | Содержит координаты x и y конечной вершины прямого отрезка линии. |
| [getMoveToCol()](#getMoveToCol--) | Содержит координаты x и y первой вершины фигуры, либо координаты x и y первой вершины после разрыва в пути. |
| [getNURBSToCol()](#getNURBSToCol--) | Содержит координаты x и y, позицию предпоследнего узла, позицию последнего веса, позицию первого узла, позицию первого веса и формулу для неравномерного рационального B-сплайна (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Содержит координаты x и y последней точки полилинии и формулу полилинии. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Содержит координаты x и y для точек RelCubBezTo.Координаты указаны как относительные. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Содержит элементы, которые указывают информацию об эллиптической дуге. Координаты задаются как относительные координаты. |
| [getRelLineToCol()](#getRelLineToCol--) | Содержит координаты x и y конечной вершины прямого отрезка линии. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Содержит координаты x и y первой вершины фигуры, либо содержит координаты x и y первой вершины после разрыва в пути. Координаты задаются как относительные координаты. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Содержит координаты x и y для точек RelQuadBezTo.Координаты указаны как относительные. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Содержит координаты x и y контрольной точки сплайна и узла сплайна, представленные элементами X, Y и A соответственно. |
| [getSplineStartCol()](#getSplineStartCol--) | Содержит координаты x и y второй контрольной точки сплайна, его второго узла, первого узла, последнего узла и степень сплайна. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Элемент существует в коллекции. |
| [iterator()](#iterator--) | Поддерживает простую итерацию по необобщённой коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Удалите объект ArcTo из коллекции. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Удалите объект Coordinate из коллекции. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Удалите объект Ellipse из коллекции. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Удалите объект EllipticalArcTo из коллекции. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Удалите объект InfiniteLine из коллекции. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Удалите объект LineTo из коллекции. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Удалите объект MoveTo из коллекции. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Удалите объект NURBSTo из коллекции. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Удалите объект PolylineTo из коллекции. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Удалите объект RelCubBezTo из коллекции. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Удалите объект RelEllipticalArcTo из коллекции. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Удалите объект RelLineTo из коллекции. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Удалите объект RelMoveTo из коллекции. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Удалите объект RelQuadBezTo из коллекции. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Удалите объект SplineKnot из коллекции. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Удалите объект SplineStart из коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Добавить объект ArcTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Добавить объект Coordinate в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Добавить объект Ellipse в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Добавить объект EllipticalArcTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Добавить объект InfiniteLine в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Добавить объект LineTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Добавить объект MoveTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Добавить объект NURBSTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Добавить объект PolylineTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Добавить объект RelCubBezTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Добавьте объект RelEllipticalArcTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Добавьте объект RelLineTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Добавьте объект RelMoveTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Добавьте объект RelQuadBezTo в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Добавьте объект SplineKnot в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Добавьте объект SplineStart в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Получает элемент по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Содержит координаты x и y и прогиб дуги круга, представленные соответственно элементами X, Y и A.

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


Получает количество элементов, фактически содержащихся в коллекции.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Содержит элементы, указывающие координаты x и y центра эллипса и двух точек на эллипсе.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Содержит элементы, задающие информацию об эллиптической дуге.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Содержит элементы, указывающие координаты x и y двух точек на бесконечной линии. Элементы X и Y задают координаты x и y первой точки, а элементы A и B задают координаты x и y второй точки.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Содержит координаты x и y конечной вершины прямолинейного отрезка. Эти координаты находятся в элементах X и Y соответственно.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Содержит координаты x и y первой вершины фигуры, либо координаты x и y первой вершины после разрыва в пути.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Содержит x- и y-координаты, позицию предпоследнего узла, позицию последнего веса, позицию первого узла, позицию первого веса и формулу для неравномерного рационального B-сплайна (NURBS). Эта информация указана соответственно в элементах X, Y, A, B, C, D и E.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Содержит x- и y-координаты последней точки полилинии и формулу полилинии. Координаты задаются в элементах X и Y, а формула задаётся в элементе A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Содержит координаты x и y для точек RelCubBezTo.Координаты указаны как относительные.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Содержит элементы, которые указывают информацию об эллиптической дуге. Координаты задаются как относительные координаты.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Содержит координаты x и y конечной вершины прямолинейного отрезка. Эти координаты находятся в элементах X и Y соответственно. Координаты задаются как относительные координаты.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Содержит координаты x и y первой вершины фигуры, либо содержит координаты x и y первой вершины после разрыва в пути. Координаты задаются как относительные координаты.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Содержит координаты x и y для точек RelQuadBezTo.Координаты указаны как относительные.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Содержит координаты x и y контрольной точки сплайна и узла сплайна, представленные элементами X, Y и A соответственно.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Содержит координаты x и y для второй контрольной точки сплайна, его второго узла, первого узла, последнего узла и степени сплайна. Эта информация содержится в элементах X, Y, A, B, C и D соответственно.

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


Элемент существует в коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | индекс элемента. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Поддерживает простую итерацию по необобщённой коллекции.

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


Удалите объект ArcTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Удалите объект Coordinate из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Удалите объект Ellipse из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Удалите объект EllipticalArcTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Удалите объект InfiniteLine из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Удалите объект LineTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Удалите объект MoveTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Удалите объект NURBSTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Удалите объект PolylineTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Удалите объект RelCubBezTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Удалите объект RelEllipticalArcTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Удалите объект RelLineTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Удалите объект RelMoveTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Удалите объект RelQuadBezTo из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Удалите объект SplineKnot из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Удалите объект SplineStart из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

