---
title: CoordinateCollection
second_title: Riferimento API di Aspose.Diagram per Java
description: Raccolta di coordinate.
type: docs
weight: 102
url: /it/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Raccolta di coordinate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Aggiunge l'oggetto ArcTo alla collezione. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Aggiunge l'oggetto Coordinate alla collezione. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Aggiunge l'oggetto Ellipse alla collezione. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Aggiunge l'oggetto EllipticalArcTo alla collezione. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Aggiunge l'oggetto InfiniteLine alla collezione. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Aggiunge l'oggetto LineTo alla collezione. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Aggiunge l'oggetto MoveTo alla collezione. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Aggiunge l'oggetto NURBSTo alla collezione. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Aggiunge l'oggetto PolylineTo alla collezione. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Aggiunge l'oggetto RelCubBezTo alla collezione. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Aggiungi l'oggetto RelEllipticalArcTo nella collezione. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Aggiungi l'oggetto RelLineTo nella collezione. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Aggiungi l'oggetto RelMoveTo nella collezione. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Aggiungi l'oggetto RelQuadBezTo nella collezione. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Aggiungi l'oggetto SplineKnot nella collezione. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Aggiungi l'oggetto SplineStart nella collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Ottiene l'elemento all'indice specificato. |
| [getArcToCol()](#getArcToCol--) | Contiene le coordinate x e y e l'arco di un arco circolare rappresentati rispettivamente dagli elementi X, Y e A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [getEllipseCol()](#getEllipseCol--) | Contiene elementi che specificano le coordinate x e y del punto centrale dell'ellisse e due punti sull'ellisse. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Contiene elementi che specificano informazioni su un arco ellittico. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Contiene elementi che specificano le coordinate x e y di due punti su una linea infinita. |
| [getLineToCol()](#getLineToCol--) | Contiene le coordinate x e y del vertice finale di un segmento di linea retta. |
| [getMoveToCol()](#getMoveToCol--) | Contiene le coordinate x e y del primo vertice di una forma, oppure le coordinate x e y del primo vertice dopo un'interruzione in un percorso. |
| [getNURBSToCol()](#getNURBSToCol--) | Contiene le coordinate x e y, la posizione del penultimo nodo, la posizione dell'ultimo peso, la posizione del primo nodo, la posizione del primo peso e la formula per una B-spline razionale non uniforme (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Contiene le coordinate x e y dell'ultimo punto di una polilinea e la formula della polilinea. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Contiene le coordinate x e y per i punti di un RelCubBezTo. Le coordinate sono specificate come coordinate relative. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Contiene elementi che specificano informazioni su un arco ellittico. Le coordinate sono specificate come coordinate relative. |
| [getRelLineToCol()](#getRelLineToCol--) | Contiene le coordinate x e y del vertice finale di un segmento di linea retta. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Contiene le coordinate x e y del primo vertice di una forma, o contiene le coordinate x e y del primo vertice dopo un'interruzione in un percorso. Le coordinate sono specificate come coordinate relative. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Contiene le coordinate x e y per i punti di un RelQuadBezTo. Le coordinate sono specificate come coordinate relative. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Contiene le coordinate x e y per il punto di controllo di una spline e per un nodo della spline, rappresentati rispettivamente dagli elementi X, Y e A. |
| [getSplineStartCol()](#getSplineStartCol--) | Contiene le coordinate x e y per il secondo punto di controllo di una spline, il suo secondo nodo, il suo primo nodo, l'ultimo nodo e il grado della spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Esiste un elemento nella collezione. |
| [iterator()](#iterator--) | Supporta un'iterazione semplice su una collezione non generica. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Rimuovi l'oggetto ArcTo dalla collezione. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Rimuovi l'oggetto Coordinate dalla collezione. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Rimuovi l'oggetto Ellipse dalla collezione. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Rimuovi l'oggetto EllipticalArcTo dalla collezione. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Rimuovi l'oggetto InfiniteLine dalla collezione. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Rimuovi l'oggetto LineTo dalla collezione. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Rimuovi l'oggetto MoveTo dalla collezione. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Rimuovi l'oggetto NURBSTo dalla collezione. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Rimuovi l'oggetto PolylineTo dalla collezione. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Rimuovi l'oggetto RelCubBezTo dalla collezione. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Rimuovi l'oggetto RelEllipticalArcTo dalla collezione. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Rimuovi l'oggetto RelLineTo dalla collezione. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Rimuovi l'oggetto RelMoveTo dalla collezione. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Rimuovi l'oggetto RelQuadBezTo dalla collezione. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Rimuovi l'oggetto SplineKnot dalla collezione. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Rimuovi l'oggetto SplineStart dalla collezione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Aggiunge l'oggetto ArcTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Aggiunge l'oggetto Coordinate alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Aggiunge l'oggetto Ellipse alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Aggiunge l'oggetto EllipticalArcTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Aggiunge l'oggetto InfiniteLine alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Aggiunge l'oggetto LineTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Aggiunge l'oggetto MoveTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Aggiunge l'oggetto NURBSTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Aggiunge l'oggetto PolylineTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Aggiunge l'oggetto RelCubBezTo alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Aggiungi l'oggetto RelEllipticalArcTo nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Aggiungi l'oggetto RelLineTo nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Aggiungi l'oggetto RelMoveTo nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Aggiungi l'oggetto RelQuadBezTo nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Aggiungi l'oggetto SplineKnot nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Aggiungi l'oggetto SplineStart nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Rimuove tutti gli elementi dalla collezione.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Ottiene l'elemento all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Contiene le coordinate x e y e l'arco di un arco circolare rappresentati rispettivamente dagli elementi X, Y e A.

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


Ottiene il numero di elementi effettivamente contenuti nella collezione.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Contiene elementi che specificano le coordinate x e y del punto centrale dell'ellisse e due punti sull'ellisse.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Contiene elementi che specificano informazioni su un arco ellittico.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Contiene gli elementi che specificano le coordinate x e y di due punti su una linea infinita. Gli elementi X e Y specificano le coordinate x e y del primo punto, e gli elementi A e B specificano le coordinate x e y del secondo punto.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Contiene le coordinate x e y del vertice finale di un segmento di linea retta. Queste coordinate sono contenute rispettivamente negli elementi X e Y.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Contiene le coordinate x e y del primo vertice di una forma, oppure le coordinate x e y del primo vertice dopo un'interruzione in un percorso.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Contiene le coordinate x e y, la posizione del penultimo nodo, la posizione dell'ultimo peso, la posizione del primo nodo, la posizione del primo peso e la formula per una B-spline razionale non uniforme (NURBS). Queste informazioni sono specificate rispettivamente negli elementi X, Y, A, B, C, D ed E.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Contiene le coordinate x e y dell'ultimo punto di una polilinea e una formula di polilinea. Le coordinate sono specificate negli elementi X e Y, e la formula è specificata nell'elemento A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Contiene le coordinate x e y per i punti di un RelCubBezTo. Le coordinate sono specificate come coordinate relative.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Contiene elementi che specificano informazioni su un arco ellittico. Le coordinate sono specificate come coordinate relative.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Contiene le coordinate x e y del vertice finale di un segmento di linea retta. Queste coordinate sono contenute rispettivamente negli elementi X e Y.Coordinate specificate come coordinate relative.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Contiene le coordinate x e y del primo vertice di una forma, o contiene le coordinate x e y del primo vertice dopo un'interruzione in un percorso. Le coordinate sono specificate come coordinate relative.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Contiene le coordinate x e y per i punti di un RelQuadBezTo. Le coordinate sono specificate come coordinate relative.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Contiene le coordinate x e y per il punto di controllo di una spline e per un nodo della spline, rappresentati rispettivamente dagli elementi X, Y e A.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Contiene le coordinate x e y per il secondo punto di controllo di una spline, il suo secondo nodo, il suo primo nodo, l'ultimo nodo e il grado della spline. Queste informazioni sono contenute rispettivamente negli elementi X, Y, A, B, C e D.

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


Esiste un elemento nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | indice dell'elemento. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Supporta un'iterazione semplice su una collezione non generica.

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


Rimuovi l'oggetto ArcTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Rimuovi l'oggetto Coordinate dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Rimuovi l'oggetto Ellipse dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Rimuovi l'oggetto EllipticalArcTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Rimuovi l'oggetto InfiniteLine dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Rimuovi l'oggetto LineTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Rimuovi l'oggetto MoveTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Rimuovi l'oggetto NURBSTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Rimuovi l'oggetto PolylineTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Rimuovi l'oggetto RelCubBezTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Rimuovi l'oggetto RelEllipticalArcTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Rimuovi l'oggetto RelLineTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Rimuovi l'oggetto RelMoveTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Rimuovi l'oggetto RelQuadBezTo dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Rimuovi l'oggetto SplineKnot dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Rimuovi l'oggetto SplineStart dalla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

