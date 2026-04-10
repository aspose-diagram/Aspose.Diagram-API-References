---
title: CoordinateCollection
second_title: Aspose.Diagram för Java API-referens
description: Koordinatsamling.
type: docs
weight: 102
url: /sv/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Koordinatsamling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Lägg till ArcTo-objektet i samlingen. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Lägg till Coordinate-objektet i samlingen. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Lägg till Ellipse-objektet i samlingen. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Lägg till EllipticalArcTo-objektet i samlingen. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Lägg till InfiniteLine-objektet i samlingen. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Lägg till LineTo-objektet i samlingen. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Lägg till MoveTo-objektet i samlingen. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Lägg till NURBSTo-objektet i samlingen. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Lägg till PolylineTo-objektet i samlingen. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Lägg till RelCubBezTo-objektet i samlingen. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Lägg till RelEllipticalArcTo-objektet i samlingen. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Lägg till RelLineTo-objektet i samlingen. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Lägg till RelMoveTo-objektet i samlingen. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Lägg till RelQuadBezTo-objektet i samlingen. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Lägg till SplineKnot-objektet i samlingen. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Lägg till SplineStart-objektet i samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Hämtar elementet på det angivna indexet. |
| [getArcToCol()](#getArcToCol--) | Innehåller x- och y-koordinaterna samt bågen för en cirkulär båge som representeras respektive av elementen X, Y och A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [getEllipseCol()](#getEllipseCol--) | Innehåller element som specificerar x- och y-koordinaterna för ellipsens mittpunkt samt två punkter på ellipsen. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Innehåller element som specificerar information om en elliptisk båge. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Innehåller element som specificerar x- och y-koordinaterna för två punkter på en oändlig linje. |
| [getLineToCol()](#getLineToCol--) | Innehåller x- och y-koordinater för den avslutande hörnpunkten i ett rakt linjesegment. |
| [getMoveToCol()](#getMoveToCol--) | Innehåller x- och y-koordinaterna för den första hörnpunkten i en form, eller x- och y-koordinaterna för den första hörnpunkten efter ett avbrott i en bana. |
| [getNURBSToCol()](#getNURBSToCol--) | Innehåller x- och y-koordinaterna, positionen för den näst sista knuten, positionen för den sista vikten, positionen för den första knuten, positionen för den första vikten samt formeln för en icke‑uniform rationell B-spline (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Innehåller x- och y-koordinater för den sista punkten i en polylinje samt en polylinjeformel. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Innehåller x- och y-koordinater för en RelCubBezTo:s punkter. Koordinaterna anges som relativa koordinater. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Innehåller element som specificerar information om en elliptisk båge. Koordinaterna anges som relativa koordinater. |
| [getRelLineToCol()](#getRelLineToCol--) | Innehåller x- och y-koordinater för den avslutande hörnpunkten i ett rakt linjesegment. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Innehåller x- och y-koordinaterna för den första vertexen i en form, eller innehåller x- och y-koordinaterna för den första vertexen efter ett avbrott i en bana. Koordinaterna anges som relativa koordinater. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Innehåller x- och y-koordinater för en RelQuadBezTo:s punkter. Koordinaterna anges som relativa koordinater. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Innehåller x- och y-koordinater för en splines kontrollpunkt och en splines knut, representerade av X-, Y- och A-elementen respektive. |
| [getSplineStartCol()](#getSplineStartCol--) | Innehåller x- och y-koordinater för en splines andra kontrollpunkt, dess andra knut, dess första knut, den sista knuten och splinens grad. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Finns ett objekt i samlingen. |
| [iterator()](#iterator--) | Stöder en enkel iteration över en icke-generisk samling. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Ta bort ArcTo-objektet från samlingen. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Ta bort Coordinate-objektet från samlingen. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Ta bort Ellipse-objektet från samlingen. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Ta bort EllipticalArcTo-objektet från samlingen. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Ta bort InfiniteLine-objektet från samlingen. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Ta bort LineTo-objektet från samlingen. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Ta bort MoveTo-objektet från samlingen. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Ta bort NURBSTo-objektet från samlingen. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Ta bort PolylineTo-objektet från samlingen. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Ta bort RelCubBezTo-objektet från samlingen. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Ta bort RelEllipticalArcTo-objektet från samlingen. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Ta bort RelLineTo-objektet från samlingen. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Ta bort RelMoveTo-objektet från samlingen. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Ta bort RelQuadBezTo-objektet från samlingen. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Ta bort SplineKnot-objektet från samlingen. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Ta bort SplineStart-objektet från samlingen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Lägg till ArcTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Lägg till Coordinate-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Lägg till Ellipse-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Lägg till EllipticalArcTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Lägg till InfiniteLine-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Lägg till LineTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Lägg till MoveTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Lägg till NURBSTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Lägg till PolylineTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Lägg till RelCubBezTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Lägg till RelEllipticalArcTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Lägg till RelLineTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Lägg till RelMoveTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Lägg till RelQuadBezTo-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Lägg till SplineKnot-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Lägg till SplineStart-objektet i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Tar bort alla element från samlingen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Hämtar elementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Innehåller x- och y-koordinaterna samt bågen för en cirkulär båge som representeras respektive av elementen X, Y och A.

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


Hämtar antalet element som faktiskt finns i samlingen.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Innehåller element som specificerar x- och y-koordinaterna för ellipsens mittpunkt samt två punkter på ellipsen.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Innehåller element som specificerar information om en elliptisk båge.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Innehåller element som specificerar x- och y-koordinaterna för två punkter på en oändlig linje. X- och Y-elementen specificerar x- och y-koordinaterna för den första punkten, och A- och B-elementen specificerar x- och y-koordinaterna för den andra punkten.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Innehåller x- och y-koordinater för den avslutande vertexen i ett rakt linjesegment. Dessa koordinater finns i X- respektive Y-elementen.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Innehåller x- och y-koordinaterna för den första hörnpunkten i en form, eller x- och y-koordinaterna för den första hörnpunkten efter ett avbrott i en bana.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Innehåller x- och y-koordinaterna, positionen för den näst sista knuten, positionen för den sista vikten, positionen för den första knuten, positionen för den första vikten samt formeln för en icke-uniform rationell B-spline (NURBS). Denna information anges i elementen X, Y, A, B, C, D och E, i den ordningen.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Innehåller x- och y-koordinater för den sista punkten i en polyline och en polyline-formel. Koordinaterna anges i X- och Y-elementen, och formeln anges i A-elementet.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Innehåller x- och y-koordinater för en RelCubBezTo:s punkter. Koordinaterna anges som relativa koordinater.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Innehåller element som specificerar information om en elliptisk båge. Koordinaterna anges som relativa koordinater.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Innehåller x- och y-koordinater för den avslutande vertexen i ett rakt linjesegment. Dessa koordinater finns i X- respektive Y-elementen. Koordinaterna anges som relativa koordinater.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Innehåller x- och y-koordinaterna för den första vertexen i en form, eller innehåller x- och y-koordinaterna för den första vertexen efter ett avbrott i en bana. Koordinaterna anges som relativa koordinater.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Innehåller x- och y-koordinater för en RelQuadBezTo:s punkter. Koordinaterna anges som relativa koordinater.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Innehåller x- och y-koordinater för en splines kontrollpunkt och en splines knut, representerade av X-, Y- och A-elementen respektive.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Innehåller x- och y-koordinater för en splines andra kontrollpunkt, dess andra knut, dess första knut, den sista knuten och graden av splinen. Denna information finns i elementen X, Y, A, B, C och D, respektive.

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


Finns ett objekt i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | index för elementet. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Stöder en enkel iteration över en icke-generisk samling.

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


Ta bort ArcTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Ta bort Coordinate-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Ta bort Ellipse-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Ta bort EllipticalArcTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Ta bort InfiniteLine-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Ta bort LineTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Ta bort MoveTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Ta bort NURBSTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Ta bort PolylineTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Ta bort RelCubBezTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Ta bort RelEllipticalArcTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Ta bort RelLineTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Ta bort RelMoveTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Ta bort RelQuadBezTo-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Ta bort SplineKnot-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Ta bort SplineStart-objektet från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

