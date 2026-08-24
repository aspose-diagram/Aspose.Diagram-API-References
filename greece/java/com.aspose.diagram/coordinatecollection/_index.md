---
title: CoordinateCollection
second_title: Αναφορά API του Aspose.Diagram για Java
description: Συλλογή συντεταγμένων.
type: docs
weight: 102
url: /el/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Συλλογή συντεταγμένων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Προσθέστε το αντικείμενο ArcTo στη συλλογή. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Προσθέστε το αντικείμενο Coordinate στη συλλογή. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Προσθέστε το αντικείμενο Ellipse στη συλλογή. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Προσθέστε το αντικείμενο EllipticalArcTo στη συλλογή. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Προσθέστε το αντικείμενο InfiniteLine στη συλλογή. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Προσθέστε το αντικείμενο LineTo στη συλλογή. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Προσθέστε το αντικείμενο MoveTo στη συλλογή. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Προσθέστε το αντικείμενο NURBSTo στη συλλογή. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Προσθέστε το αντικείμενο PolylineTo στη συλλογή. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Προσθέστε το αντικείμενο RelCubBezTo στη συλλογή. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Προσθέστε το αντικείμενο RelEllipticalArcTo στη συλλογή. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Προσθέστε το αντικείμενο RelLineTo στη συλλογή. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Προσθέστε το αντικείμενο RelMoveTo στη συλλογή. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Προσθέστε το αντικείμενο RelQuadBezTo στη συλλογή. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Προσθέστε το αντικείμενο SplineKnot στη συλλογή. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Προσθέστε το αντικείμενο SplineStart στη συλλογή. |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getArcToCol()](#getArcToCol--) | Περιέχει τις συντεταγμένες x και y και την καμπυλότητα ενός κυκλικού τόξου που αντιπροσωπεύονται αντίστοιχα από τα στοιχεία X, Y και A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getEllipseCol()](#getEllipseCol--) | Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες x και y του κεντρικού σημείου της έλλειψης και δύο σημεία στην έλλειψη. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Περιέχει στοιχεία που καθορίζουν πληροφορίες σχετικά με μια ελλειπτική τόξο. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες x και y δύο σημείων σε μια άπειρη γραμμή. |
| [getLineToCol()](#getLineToCol--) | Περιέχει τις συντεταγμένες x και y του τελικού κορυφαίου σημείου ενός ευθύγραμμου τμήματος. |
| [getMoveToCol()](#getMoveToCol--) | Περιέχει τις συντεταγμένες x και y της πρώτης κορυφής ενός σχήματος, ή περιέχει τις συντεταγμένες x και y της πρώτης κορυφής μετά από ένα διάλειμμα σε μια διαδρομή. |
| [getNURBSToCol()](#getNURBSToCol--) | Περιέχει τις συντεταγμένες x και y, τη θέση του προτελευταίου κόμβου, τη θέση του τελευταίου βάρους, τη θέση του πρώτου κόμβου, τη θέση του πρώτου βάρους, και τον τύπο για μια μη ομοιόμορφη ρη rational B-spline (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Περιέχει τις συντεταγμένες x και y του τελευταίου σημείου μιας πολυγραμμής και τον τύπο της πολυγραμμής. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Περιέχει συντεταγμένες x και y για τα σημεία ενός RelCubBezTo. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Περιέχει στοιχεία που καθορίζουν πληροφορίες σχετικά με μια ελλειπτική τόξο. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες. |
| [getRelLineToCol()](#getRelLineToCol--) | Περιέχει τις συντεταγμένες x και y του τελικού κορυφαίου σημείου ενός ευθύγραμμου τμήματος. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Περιέχει τις x- και y-συντεταγμένες της πρώτης κορυφής ενός σχήματος, ή περιέχει τις x- και y-συντεταγμένες της πρώτης κορυφής μετά από μια διακοπή σε μια διαδρομή. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Περιέχει συντεταγμένες x και y για τα σημεία ενός RelQuadBezTo. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Περιέχει συντεταγμένες x και y για το σημείο ελέγχου μιας καμπύλης spline και για έναν κόμβο spline, που αντιπροσωπεύονται από τα στοιχεία X, Y και A, αντίστοιχα. |
| [getSplineStartCol()](#getSplineStartCol--) | Περιέχει συντεταγμένες x και y για το δεύτερο σημείο ελέγχου μιας spline, τον δεύτερο κόμβο της, τον πρώτο κόμβο, τον τελευταίο κόμβο και τον βαθμό της spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Αφαιρέστε το αντικείμενο ArcTo από τη συλλογή. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Αφαιρέστε το αντικείμενο Coordinate από τη συλλογή. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Αφαιρέστε το αντικείμενο Ellipse από τη συλλογή. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Αφαιρέστε το αντικείμενο EllipticalArcTo από τη συλλογή. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Αφαιρέστε το αντικείμενο InfiniteLine από τη συλλογή. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Αφαιρέστε το αντικείμενο LineTo από τη συλλογή. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Αφαιρέστε το αντικείμενο MoveTo από τη συλλογή. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Αφαιρέστε το αντικείμενο NURBSTo από τη συλλογή. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Αφαιρέστε το αντικείμενο PolylineTo από τη συλλογή. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Αφαιρέστε το αντικείμενο RelCubBezTo από τη συλλογή. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Αφαιρέστε το αντικείμενο RelEllipticalArcTo από τη συλλογή. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Αφαιρέστε το αντικείμενο RelLineTo από τη συλλογή. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Αφαιρέστε το αντικείμενο RelMoveTo από τη συλλογή. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Αφαιρέστε το αντικείμενο RelQuadBezTo από τη συλλογή. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Αφαιρέστε το αντικείμενο SplineKnot από τη συλλογή. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Αφαιρέστε το αντικείμενο SplineStart από τη συλλογή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Προσθέστε το αντικείμενο ArcTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Προσθέστε το αντικείμενο Coordinate στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Προσθέστε το αντικείμενο Ellipse στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Προσθέστε το αντικείμενο EllipticalArcTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Προσθέστε το αντικείμενο InfiniteLine στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Προσθέστε το αντικείμενο LineTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Προσθέστε το αντικείμενο MoveTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Προσθέστε το αντικείμενο NURBSTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Προσθέστε το αντικείμενο PolylineTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Προσθέστε το αντικείμενο RelCubBezTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Προσθέστε το αντικείμενο RelEllipticalArcTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Προσθέστε το αντικείμενο RelLineTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Προσθέστε το αντικείμενο RelMoveTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Προσθέστε το αντικείμενο RelQuadBezTo στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Προσθέστε το αντικείμενο SplineKnot στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Προσθέστε το αντικείμενο SplineStart στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Gets the element at the specified index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Περιέχει τις συντεταγμένες x και y και την καμπυλότητα ενός κυκλικού τόξου που αντιπροσωπεύονται αντίστοιχα από τα στοιχεία X, Y και A.

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


Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες x και y του κεντρικού σημείου της έλλειψης και δύο σημεία στην έλλειψη.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Περιέχει στοιχεία που καθορίζουν πληροφορίες σχετικά με μια ελλειπτική τόξο.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες x και y δύο σημείων σε μια άπειρη γραμμή. Τα στοιχεία X και Y καθορίζουν τις συντεταγμένες x και y του πρώτου σημείου, ενώ τα στοιχεία A και B καθορίζουν τις συντεταγμένες x και y του δεύτερου σημείου.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Περιέχει τις συντεταγμένες x και y του τελικού κορυφαίου σημείου ενός ευθύγραμμου τμήματος. Αυτές οι συντεταγμένες περιλαμβάνονται στα στοιχεία X και Y, αντίστοιχα.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Περιέχει τις συντεταγμένες x και y της πρώτης κορυφής ενός σχήματος, ή περιέχει τις συντεταγμένες x και y της πρώτης κορυφής μετά από ένα διάλειμμα σε μια διαδρομή.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Περιέχει τις συντεταγμένες x και y, τη θέση του προτελευταίου κόμπου, τη θέση του τελευταίου βάρους, τη θέση του πρώτου κόμπου, τη θέση του πρώτου βάρους και τον τύπο για μια nonuniform rational B-spline (NURBS). Αυτές οι πληροφορίες καθορίζονται στα στοιχεία X, Y, A, B, C, D και E, αντίστοιχα.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Περιέχει τις συντεταγμένες x και y του τελευταίου σημείου μιας πολυγραμμής και έναν τύπο πολυγραμμής. Οι συντεταγμένες καθορίζονται στα στοιχεία X και Y, και ο τύπος καθορίζεται στο στοιχείο A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Περιέχει συντεταγμένες x και y για τα σημεία ενός RelCubBezTo. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Περιέχει στοιχεία που καθορίζουν πληροφορίες σχετικά με μια ελλειπτική τόξο. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Περιέχει τις συντεταγμένες x και y του τελικού κορυφαίου σημείου ενός ευθύγραμμου τμήματος. Αυτές οι συντεταγμένες περιλαμβάνονται στα στοιχεία X και Y, αντίστοιχα.Οι συντεταγμένες ορίζονται ως σχετικές συντεταγμένες.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Περιέχει τις x- και y-συντεταγμένες της πρώτης κορυφής ενός σχήματος, ή περιέχει τις x- και y-συντεταγμένες της πρώτης κορυφής μετά από μια διακοπή σε μια διαδρομή. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Περιέχει συντεταγμένες x και y για τα σημεία ενός RelQuadBezTo. Οι συντεταγμένες καθορίζονται ως σχετικές συντεταγμένες.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Περιέχει συντεταγμένες x και y για το σημείο ελέγχου μιας καμπύλης spline και για έναν κόμβο spline, που αντιπροσωπεύονται από τα στοιχεία X, Y και A, αντίστοιχα.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Περιέχει τις συντεταγμένες x και y για το δεύτερο σημείο ελέγχου μιας spline, το δεύτερο κόμβο της, το πρώτο κόμβο της, τον τελευταίο κόμβο και τον βαθμό της spline. Αυτές οι πληροφορίες περιλαμβάνονται στα στοιχεία X, Y, A, B, C και D, αντίστοιχα.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | δείκτης του στοιχείου. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή.

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


Αφαιρέστε το αντικείμενο ArcTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Αφαιρέστε το αντικείμενο Coordinate από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Αφαιρέστε το αντικείμενο Ellipse από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Αφαιρέστε το αντικείμενο EllipticalArcTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Αφαιρέστε το αντικείμενο InfiniteLine από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Αφαιρέστε το αντικείμενο LineTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Αφαιρέστε το αντικείμενο MoveTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Αφαιρέστε το αντικείμενο NURBSTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Αφαιρέστε το αντικείμενο PolylineTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Αφαιρέστε το αντικείμενο RelCubBezTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Αφαιρέστε το αντικείμενο RelEllipticalArcTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Αφαιρέστε το αντικείμενο RelLineTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Αφαιρέστε το αντικείμενο RelMoveTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Αφαιρέστε το αντικείμενο RelQuadBezTo από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Αφαιρέστε το αντικείμενο SplineKnot από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Αφαιρέστε το αντικείμενο SplineStart από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

