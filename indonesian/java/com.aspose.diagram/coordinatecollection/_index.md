---
title: CoordinateCollection
second_title: Referensi API Aspose.Diagram untuk Java
description: Koleksi koordinat.
type: docs
weight: 102
url: /id/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Koleksi koordinat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Tambahkan objek ArcTo ke dalam koleksi. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Tambahkan objek Coordinate ke dalam koleksi. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Tambahkan objek Ellipse ke dalam koleksi. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Tambahkan objek EllipticalArcTo ke dalam koleksi. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Tambahkan objek InfiniteLine ke dalam koleksi. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Tambahkan objek LineTo ke dalam koleksi. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Tambahkan objek MoveTo ke dalam koleksi. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Tambahkan objek NURBSTo ke dalam koleksi. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Tambahkan objek PolylineTo ke dalam koleksi. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Tambahkan objek RelCubBezTo ke dalam koleksi. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Tambahkan objek RelEllipticalArcTo ke dalam koleksi. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Tambahkan objek RelLineTo ke dalam koleksi. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Tambahkan objek RelMoveTo ke dalam koleksi. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Tambahkan objek RelQuadBezTo ke dalam koleksi. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Tambahkan objek SplineKnot ke dalam koleksi. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Tambahkan objek SplineStart ke dalam koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getArcToCol()](#getArcToCol--) | Berisi koordinat x dan y serta busur dari busur melingkar yang diwakili masing-masing oleh elemen X, Y, dan A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [getEllipseCol()](#getEllipseCol--) | Berisi elemen yang menentukan koordinat x dan y dari titik pusat elips serta dua titik pada elips. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Berisi elemen yang menentukan informasi tentang busur elips. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Berisi elemen yang menentukan koordinat x dan y dari dua titik pada garis tak hingga. |
| [getLineToCol()](#getLineToCol--) | Berisi koordinat x dan y dari titik akhir segmen garis lurus. |
| [getMoveToCol()](#getMoveToCol--) | Berisi koordinat x dan y dari vertex pertama sebuah bentuk, atau berisi koordinat x dan y dari vertex pertama setelah jeda dalam jalur. |
| [getNURBSToCol()](#getNURBSToCol--) | Berisi koordinat x dan y, posisi simpul kedua dari terakhir, posisi beban terakhir, posisi simpul pertama, posisi beban pertama, dan rumus untuk B-spline rasional tidak seragam (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Berisi koordinat x dan y dari titik terakhir sebuah polyline dan formula polyline. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Berisi koordinat x dan y untuk titik-titik RelCubBezTo. Koordinat ditentukan sebagai koordinat relatif. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Berisi elemen yang menentukan informasi tentang busur elips. Koordinat ditentukan sebagai koordinat relatif. |
| [getRelLineToCol()](#getRelLineToCol--) | Berisi koordinat x dan y dari titik akhir segmen garis lurus. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Berisi koordinat x dan y dari vertex pertama sebuah bentuk, atau berisi koordinat x dan y dari vertex pertama setelah jeda dalam jalur. Koordinat ditentukan sebagai koordinat relatif. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Berisi koordinat x dan y untuk titik-titik RelQuadBezTo. Koordinat ditentukan sebagai koordinat relatif. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Berisi koordinat x dan y untuk titik kontrol spline dan simpul spline, yang diwakili oleh elemen X, Y, dan A masing-masing. |
| [getSplineStartCol()](#getSplineStartCol--) | Berisi koordinat x dan y untuk titik kontrol kedua spline, simpul kedua, simpul pertama, simpul terakhir, dan derajat spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Apakah ada item dalam koleksi. |
| [iterator()](#iterator--) | Mendukung iterasi sederhana atas koleksi non-generic. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Hapus objek ArcTo dari koleksi. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Hapus objek Coordinate dari koleksi. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Hapus objek Ellipse dari koleksi. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Hapus objek EllipticalArcTo dari koleksi. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Hapus objek InfiniteLine dari koleksi. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Hapus objek LineTo dari koleksi. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Hapus objek MoveTo dari koleksi. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Hapus objek NURBSTo dari koleksi. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Hapus objek PolylineTo dari koleksi. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Hapus objek RelCubBezTo dari koleksi. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Hapus objek RelEllipticalArcTo dari koleksi. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Hapus objek RelLineTo dari koleksi. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Hapus objek RelMoveTo dari koleksi. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Hapus objek RelQuadBezTo dari koleksi. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Hapus objek SplineKnot dari koleksi. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Hapus objek SplineStart dari koleksi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Tambahkan objek ArcTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Tambahkan objek Coordinate ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Tambahkan objek Ellipse ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Tambahkan objek EllipticalArcTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Tambahkan objek InfiniteLine ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Tambahkan objek LineTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Tambahkan objek MoveTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Tambahkan objek NURBSTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Tambahkan objek PolylineTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Tambahkan objek RelCubBezTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Tambahkan objek RelEllipticalArcTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Tambahkan objek RelLineTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Tambahkan objek RelMoveTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Tambahkan objek RelQuadBezTo ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Tambahkan objek SplineKnot ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Tambahkan objek SplineStart ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Menghapus semua elemen dari koleksi.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Berisi koordinat x dan y serta busur dari busur melingkar yang diwakili masing-masing oleh elemen X, Y, dan A.

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


Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Berisi elemen yang menentukan koordinat x dan y dari titik pusat elips serta dua titik pada elips.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Berisi elemen yang menentukan informasi tentang busur elips.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Berisi elemen yang menentukan koordinat x dan y dari dua titik pada garis tak terbatas. Elemen X dan Y menentukan koordinat x dan y dari titik pertama, dan elemen A dan B menentukan koordinat x dan y dari titik kedua.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Berisi koordinat x dan y dari simpul akhir segmen garis lurus. Koordinat ini terdapat dalam elemen X dan Y, masing-masing.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Berisi koordinat x dan y dari vertex pertama sebuah bentuk, atau berisi koordinat x dan y dari vertex pertama setelah jeda dalam jalur.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Berisi koordinat x dan y, posisi simpul kedua terakhir, posisi bobot terakhir, posisi simpul pertama, posisi bobot pertama, dan formula untuk nonuniform rational B-spline (NURBS). Informasi ini ditentukan dalam elemen X, Y, A, B, C, D, dan E, masing‑masing.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Berisi koordinat x dan y dari titik terakhir sebuah polyline serta formula polyline. Koordinat ditentukan dalam elemen X dan Y, dan formula ditentukan dalam elemen A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Berisi koordinat x dan y untuk titik-titik RelCubBezTo. Koordinat ditentukan sebagai koordinat relatif.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Berisi elemen yang menentukan informasi tentang busur elips. Koordinat ditentukan sebagai koordinat relatif.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Berisi koordinat x dan y dari simpul akhir segmen garis lurus. Koordinat ini terdapat dalam elemen X dan Y, masing-masing.Koordinat ditentukan sebagai koordinat relatif.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Berisi koordinat x dan y dari vertex pertama sebuah bentuk, atau berisi koordinat x dan y dari vertex pertama setelah jeda dalam jalur. Koordinat ditentukan sebagai koordinat relatif.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Berisi koordinat x dan y untuk titik-titik RelQuadBezTo. Koordinat ditentukan sebagai koordinat relatif.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Berisi koordinat x dan y untuk titik kontrol spline dan simpul spline, yang diwakili oleh elemen X, Y, dan A masing-masing.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Berisi koordinat x dan y untuk titik kontrol kedua spline, simpul keduanya, simpul pertamanya, simpul terakhir, dan derajat spline. Informasi ini terdapat dalam elemen X, Y, A, B, C, dan D, masing-masing.

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


Apakah ada item dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | indeks elemen. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Mendukung iterasi sederhana atas koleksi non-generic.

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


Hapus objek ArcTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Hapus objek Coordinate dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Hapus objek Ellipse dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Hapus objek EllipticalArcTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Hapus objek InfiniteLine dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Hapus objek LineTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Hapus objek MoveTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Hapus objek NURBSTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Hapus objek PolylineTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Hapus objek RelCubBezTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Hapus objek RelEllipticalArcTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Hapus objek RelLineTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Hapus objek RelMoveTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Hapus objek RelQuadBezTo dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Hapus objek SplineKnot dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Hapus objek SplineStart dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

