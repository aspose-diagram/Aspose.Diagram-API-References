---
title: CoordinateCollection
second_title: Referencia de API de Aspose.Diagram para Java
description: Colección de coordenadas.
type: docs
weight: 102
url: /es/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Colección de coordenadas.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Agrega el objeto ArcTo a la colección. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Agrega el objeto Coordinate a la colección. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Agrega el objeto Ellipse a la colección. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Agrega el objeto EllipticalArcTo a la colección. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Agrega el objeto InfiniteLine a la colección. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Agrega el objeto LineTo a la colección. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Agrega el objeto MoveTo a la colección. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Agrega el objeto NURBSTo a la colección. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Agrega el objeto PolylineTo a la colección. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Agrega el objeto RelCubBezTo a la colección. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Agregar el objeto RelEllipticalArcTo a la colección. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Agregar el objeto RelLineTo a la colección. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Agregar el objeto RelMoveTo a la colección. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Agregar el objeto RelQuadBezTo a la colección. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Agregar el objeto SplineKnot a la colección. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Agregar el objeto SplineStart a la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Obtiene el elemento en el índice especificado. |
| [getArcToCol()](#getArcToCol--) | Contiene las coordenadas x e y y la curvatura de un arco circular representados respectivamente por los elementos X, Y y A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [getEllipseCol()](#getEllipseCol--) | Contiene elementos que especifican las coordenadas x e y del punto central de la elipse y dos puntos en la elipse. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Contiene elementos que especifican información sobre un arco elíptico. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Contiene elementos que especifican las coordenadas x e y de dos puntos en una línea infinita. |
| [getLineToCol()](#getLineToCol--) | Contiene las coordenadas x e y del vértice final de un segmento de línea recta. |
| [getMoveToCol()](#getMoveToCol--) | Contiene las coordenadas x e y del primer vértice de una forma, o contiene las coordenadas x e y del primer vértice después de una interrupción en una ruta. |
| [getNURBSToCol()](#getNURBSToCol--) | Contiene las coordenadas x e y, la posición del penúltimo nudo, la posición del último peso, la posición del primer nudo, la posición del primer peso y la fórmula de una B-spline racional no uniforme (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Contiene las coordenadas x e y del último punto de una polilínea y la fórmula de la polilínea. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Contiene coordenadas x e y para los puntos de un RelCubBezTo. Las coordenadas se especifican como coordenadas relativas. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Contiene elementos que especifican información sobre un arco elíptico. Las coordenadas se especifican como coordenadas relativas. |
| [getRelLineToCol()](#getRelLineToCol--) | Contiene las coordenadas x e y del vértice final de un segmento de línea recta. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Contiene las coordenadas x e y del primer vértice de una forma, o contiene las coordenadas x e y del primer vértice después de una interrupción en una ruta. Las coordenadas se especifican como coordenadas relativas. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Contiene coordenadas x e y para los puntos de un RelQuadBezTo. Las coordenadas se especifican como coordenadas relativas. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Contiene coordenadas x e y para el punto de control de una spline y el nudo de una spline, representados por los elementos X, Y y A, respectivamente. |
| [getSplineStartCol()](#getSplineStartCol--) | Contiene coordenadas x e y para el segundo punto de control de una spline, su segundo nudo, su primer nudo, el último nudo y el grado de la spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existe un elemento en la colección. |
| [iterator()](#iterator--) | Admite una iteración simple sobre una colección no genérica. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Eliminar el objeto ArcTo de la colección. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Eliminar el objeto Coordinate de la colección. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Eliminar el objeto Ellipse de la colección. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Eliminar el objeto EllipticalArcTo de la colección. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Eliminar el objeto InfiniteLine de la colección. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Eliminar el objeto LineTo de la colección. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Eliminar el objeto MoveTo de la colección. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Eliminar el objeto NURBSTo de la colección. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Eliminar el objeto PolylineTo de la colección. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Eliminar el objeto RelCubBezTo de la colección. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Eliminar el objeto RelEllipticalArcTo de la colección. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Eliminar el objeto RelLineTo de la colección. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Eliminar el objeto RelMoveTo de la colección. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Eliminar el objeto RelQuadBezTo de la colección. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Eliminar el objeto SplineKnot de la colección. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Eliminar el objeto SplineStart de la colección. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Agrega el objeto ArcTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Agrega el objeto Coordinate a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Agrega el objeto Ellipse a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Agrega el objeto EllipticalArcTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Agrega el objeto InfiniteLine a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Agrega el objeto LineTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Agrega el objeto MoveTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Agrega el objeto NURBSTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Agrega el objeto PolylineTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Agrega el objeto RelCubBezTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Agregar el objeto RelEllipticalArcTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Agregar el objeto RelLineTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Agregar el objeto RelMoveTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Agregar el objeto RelQuadBezTo a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Agregar el objeto SplineKnot a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Agregar el objeto SplineStart a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Elimina todos los elementos de la colección.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Obtiene el elemento en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Contiene las coordenadas x e y y la curvatura de un arco circular representados respectivamente por los elementos X, Y y A.

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


Obtiene el número de elementos realmente contenidos en la colección.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Contiene elementos que especifican las coordenadas x e y del punto central de la elipse y dos puntos en la elipse.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Contiene elementos que especifican información sobre un arco elíptico.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Contiene elementos que especifican las coordenadas x e y de dos puntos en una línea infinita. Los elementos X y Y especifican las coordenadas x e y del primer punto, y los elementos A y B especifican las coordenadas x e y del segundo punto.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Contiene las coordenadas x e y del vértice final de un segmento de línea recta. Estas coordenadas se encuentran en los elementos X y Y, respectivamente.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Contiene las coordenadas x e y del primer vértice de una forma, o contiene las coordenadas x e y del primer vértice después de una interrupción en una ruta.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Contiene las coordenadas x e y, la posición del penúltimo nudo, la posición del último peso, la posición del primer nudo, la posición del primer peso y la fórmula de una B-spline racional no uniforme (NURBS). Esta información se especifica en los elementos X, Y, A, B, C, D y E, respectivamente.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Contiene las coordenadas x e y del último punto de una polilínea y la fórmula de la polilínea. Las coordenadas se especifican en los elementos X y Y, y la fórmula se especifica en el elemento A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Contiene coordenadas x e y para los puntos de un RelCubBezTo. Las coordenadas se especifican como coordenadas relativas.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Contiene elementos que especifican información sobre un arco elíptico. Las coordenadas se especifican como coordenadas relativas.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Contiene las coordenadas x e y del vértice final de un segmento de línea recta. Estas coordenadas se encuentran en los elementos X y Y, respectivamente. Las coordenadas se especifican como coordenadas relativas.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Contiene las coordenadas x e y del primer vértice de una forma, o contiene las coordenadas x e y del primer vértice después de una interrupción en una ruta. Las coordenadas se especifican como coordenadas relativas.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Contiene coordenadas x e y para los puntos de un RelQuadBezTo. Las coordenadas se especifican como coordenadas relativas.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Contiene coordenadas x e y para el punto de control de una spline y el nudo de una spline, representados por los elementos X, Y y A, respectivamente.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Contiene las coordenadas x e y para el segundo punto de control de una spline, su segundo nudo, su primer nudo, el último nudo y el grado de la spline. Esta información se encuentra en los elementos X, Y, A, B, C y D, respectivamente.

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


Existe un elemento en la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | índice del elemento. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Admite una iteración simple sobre una colección no genérica.

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


Eliminar el objeto ArcTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Eliminar el objeto Coordinate de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Eliminar el objeto Ellipse de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Eliminar el objeto EllipticalArcTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Eliminar el objeto InfiniteLine de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Eliminar el objeto LineTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Eliminar el objeto MoveTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Eliminar el objeto NURBSTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Eliminar el objeto PolylineTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Eliminar el objeto RelCubBezTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Eliminar el objeto RelEllipticalArcTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Eliminar el objeto RelLineTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Eliminar el objeto RelMoveTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Eliminar el objeto RelQuadBezTo de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Eliminar el objeto SplineKnot de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Eliminar el objeto SplineStart de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

