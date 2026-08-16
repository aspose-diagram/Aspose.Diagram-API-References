---
title: CoordinateCollection
second_title: Aspose.Diagram voor Java API-referentie
description: Coördinatenverzameling.
type: docs
weight: 102
url: /nl/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Coördinatenverzameling.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Voeg het ArcTo‑object toe aan de collectie. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Voeg het Coordinate‑object toe aan de collectie. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Voeg het Ellipse‑object toe aan de collectie. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Voeg het EllipticalArcTo‑object toe aan de collectie. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Voeg het InfiniteLine‑object toe aan de collectie. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Voeg het LineTo‑object toe aan de collectie. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Voeg het MoveTo‑object toe aan de collectie. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Voeg het NURBSTo‑object toe aan de collectie. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Voeg het PolylineTo‑object toe aan de collectie. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Voeg het RelCubBezTo‑object toe aan de collectie. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Voeg het RelEllipticalArcTo-object toe aan de collectie. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Voeg het RelLineTo-object toe aan de collectie. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Voeg het RelMoveTo-object toe aan de collectie. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Voeg het RelQuadBezTo-object toe aan de collectie. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Voeg het SplineKnot-object toe aan de collectie. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Voeg het SplineStart-object toe aan de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Haalt het element op op de opgegeven index. |
| [getArcToCol()](#getArcToCol--) | Bevat de x- en y-coördinaten en de boog van een cirkelboog, respectievelijk weergegeven door de X-, Y- en A-elementen. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [getEllipseCol()](#getEllipseCol--) | Bevat elementen die de x- en y-coördinaten van het middelpunt van de ellips en twee punten op de ellips specificeren. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Bevat elementen die informatie over een elliptische boog specificeren. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Bevat elementen die de x- en y-coördinaten van twee punten op een oneindige lijn specificeren. |
| [getLineToCol()](#getLineToCol--) | Bevat de x- en y-coördinaten van het eindpunt van een rechte lijnsegment. |
| [getMoveToCol()](#getMoveToCol--) | Bevat de x- en y-coördinaten van de eerste hoekpunt van een vorm, of de x- en y-coördinaten van het eerste hoekpunt na een onderbreking in een pad. |
| [getNURBSToCol()](#getNURBSToCol--) | Bevat de x- en y-coördinaten, de positie van de op één na laatste knoop, de positie van het laatste gewicht, de positie van de eerste knoop, de positie van het eerste gewicht, en de formule voor een niet-uniforme rationale B-spline (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Bevat x- en y-coördinaten van het laatste punt van een polyline en een polyline-formule. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Bevat x- en y-coördinaten voor de punten van een RelCubBezTo. Coördinaten worden opgegeven als relatieve coördinaten. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Bevat elementen die informatie over een elliptische boog specificeren. Coördinaten worden opgegeven als relatieve coördinaten. |
| [getRelLineToCol()](#getRelLineToCol--) | Bevat de x- en y-coördinaten van het eindpunt van een rechte lijnsegment. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Bevat de x- en y-coördinaten van de eerste hoekpunt van een vorm, of bevat de x- en y-coördinaten van het eerste hoekpunt na een onderbreking in een pad.Coördinaten worden gespecificeerd als relatieve coördinaten. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Bevat x- en y-coördinaten voor de punten van een RelQuadBezTo. Coördinaten worden opgegeven als relatieve coördinaten. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Bevat x- en y-coördinaten voor een controlepunt van een spline en een knoop van een spline, respectievelijk weergegeven door de X-, Y- en A-elementen. |
| [getSplineStartCol()](#getSplineStartCol--) | Bevat x- en y-coördinaten voor het tweede controlepunt van een spline, de tweede knoop, de eerste knoop, de laatste knoop en de graad van de spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is er een item aanwezig in de collectie. |
| [iterator()](#iterator--) | Ondersteunt een eenvoudige iteratie over een niet-generieke collectie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Verwijder het ArcTo-object uit de collectie. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Verwijder het Coordinate-object uit de collectie. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Verwijder het Ellipse-object uit de collectie. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Verwijder het EllipticalArcTo-object uit de collectie. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Verwijder het InfiniteLine-object uit de collectie. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Verwijder het LineTo-object uit de collectie. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Verwijder het MoveTo-object uit de collectie. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Verwijder het NURBSTo-object uit de collectie. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Verwijder het PolylineTo-object uit de collectie. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Verwijder het RelCubBezTo-object uit de collectie. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Verwijder het RelEllipticalArcTo-object uit de collectie. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Verwijder het RelLineTo-object uit de collectie. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Verwijder het RelMoveTo-object uit de collectie. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Verwijder het RelQuadBezTo-object uit de collectie. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Verwijder het SplineKnot-object uit de collectie. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Verwijder het SplineStart-object uit de collectie. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Voeg het ArcTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Voeg het Coordinate‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Voeg het Ellipse‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Voeg het EllipticalArcTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Voeg het InfiniteLine‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Voeg het LineTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Voeg het MoveTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Voeg het NURBSTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Voeg het PolylineTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Voeg het RelCubBezTo‑object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Voeg het RelEllipticalArcTo-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Voeg het RelLineTo-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Voeg het RelMoveTo-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Voeg het RelQuadBezTo-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Voeg het SplineKnot-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Voeg het SplineStart-object toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Verwijdert alle elementen uit de collectie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Bevat de x- en y-coördinaten en de boog van een cirkelboog, respectievelijk weergegeven door de X-, Y- en A-elementen.

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


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Bevat elementen die de x- en y-coördinaten van het middelpunt van de ellips en twee punten op de ellips specificeren.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Bevat elementen die informatie over een elliptische boog specificeren.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Bevat elementen die de x- en y-coördinaten van twee punten op een oneindige lijn specificeren. De X- en Y-elementen geven de x- en y-coördinaten van het eerste punt aan, en de A- en B-elementen geven de x- en y-coördinaten van het tweede punt aan.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Bevat x- en y-coördinaten van de eindpunt van een rechte lijnsegment. Deze coördinaten staan respectievelijk in de X- en Y-elementen.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Bevat de x- en y-coördinaten van de eerste hoekpunt van een vorm, of de x- en y-coördinaten van het eerste hoekpunt na een onderbreking in een pad.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Bevat de x- en y-coördinaten, de positie van de op één na laatste knoop, de positie van het laatste gewicht, de positie van de eerste knoop, de positie van het eerste gewicht, en de formule voor een nonuniform rational B-spline (NURBS). Deze informatie wordt respectievelijk gespecificeerd in de X-, Y-, A-, B-, C-, D- en E-elementen.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Bevat x- en y-coördinaten van het laatste punt van een polyline en een polyline-formule. De coördinaten worden gespecificeerd in de X- en Y-elementen, en de formule wordt gespecificeerd in het A-element.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Bevat x- en y-coördinaten voor de punten van een RelCubBezTo. Coördinaten worden opgegeven als relatieve coördinaten.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Bevat elementen die informatie over een elliptische boog specificeren. Coördinaten worden opgegeven als relatieve coördinaten.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Bevat x- en y-coördinaten van de eindpunt van een rechte lijnsegment. Deze coördinaten staan respectievelijk in de X- en Y-elementen. Coördinaten worden opgegeven als relatieve coördinaten.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Bevat de x- en y-coördinaten van de eerste hoekpunt van een vorm, of bevat de x- en y-coördinaten van het eerste hoekpunt na een onderbreking in een pad.Coördinaten worden gespecificeerd als relatieve coördinaten.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Bevat x- en y-coördinaten voor de punten van een RelQuadBezTo. Coördinaten worden opgegeven als relatieve coördinaten.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Bevat x- en y-coördinaten voor een controlepunt van een spline en een knoop van een spline, respectievelijk weergegeven door de X-, Y- en A-elementen.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Bevat x- en y-coördinaten voor het tweede controlepunt van een spline, zijn tweede knoop, zijn eerste knoop, de laatste knoop en de graad van de spline. Deze informatie staat respectievelijk in de elementen X, Y, A, B, C en D.

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


Is er een item aanwezig in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | index van element. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Ondersteunt een eenvoudige iteratie over een niet-generieke collectie.

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


Verwijder het ArcTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Verwijder het Coordinate-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Verwijder het Ellipse-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Verwijder het EllipticalArcTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Verwijder het InfiniteLine-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Verwijder het LineTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Verwijder het MoveTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Verwijder het NURBSTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Verwijder het PolylineTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Verwijder het RelCubBezTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Verwijder het RelEllipticalArcTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Verwijder het RelLineTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Verwijder het RelMoveTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Verwijder het RelQuadBezTo-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Verwijder het SplineKnot-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Verwijder het SplineStart-object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

