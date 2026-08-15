---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API リファレンス
description: 座標コレクション。
type: docs
weight: 102
url: /ja/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object、[com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

座標コレクション。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | コレクションに ArcTo オブジェクトを追加します。 |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | コレクションに Coordinate オブジェクトを追加します。 |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | コレクションに Ellipse オブジェクトを追加します。 |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | コレクションに EllipticalArcTo オブジェクトを追加します。 |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | コレクションに InfiniteLine オブジェクトを追加します。 |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | コレクションに LineTo オブジェクトを追加します。 |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | コレクションに MoveTo オブジェクトを追加します。 |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | コレクションに NURBSTo オブジェクトを追加します。 |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | コレクションに PolylineTo オブジェクトを追加します。 |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | コレクションに RelCubBezTo オブジェクトを追加します。 |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | コレクションに RelEllipticalArcTo オブジェクトを追加します。 |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | コレクションに RelLineTo オブジェクトを追加します。 |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | コレクションに RelMoveTo オブジェクトを追加します。 |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | コレクションに RelQuadBezTo オブジェクトを追加します。 |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | コレクションに SplineKnot オブジェクトを追加します。 |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | コレクションに SplineStart オブジェクトを追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 指定されたインデックスの要素を取得します。 |
| [getArcToCol()](#getArcToCol--) | 円弧の X、Y、A 要素でそれぞれ表される x 座標、y 座標、そして弧度を含みます。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [getEllipseCol()](#getEllipseCol--) | 楕円の中心点および楕円上の 2 点の x 座標と y 座標を指定する要素を含みます。 |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | 楕円弧に関する情報を指定する要素を含みます。 |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | 無限直線上の2点の x および y 座標を指定する要素を含みます。 |
| [getLineToCol()](#getLineToCol--) | 直線セグメントの終点頂点の x および y 座標を含みます。 |
| [getMoveToCol()](#getMoveToCol--) | シェイプの最初の頂点の x および y 座標、またはパスの途中で切れた後の最初の頂点の x および y 座標を含みます。 |
| [getNURBSToCol()](#getNURBSToCol--) | x および y 座標、2 番目から最後のノットの位置、最後のウェイトの位置、最初のノットの位置、最初のウェイトの位置、そして非一様有理 B スプライン (NURBS) の式を含みます。 |
| [getPolylineToCol()](#getPolylineToCol--) | ポリラインの最後の点の x および y 座標とポリラインの式を含みます。 |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | RelCubBezTo の点の x 座標と y 座標を含みます。座標は相対座標として指定されます。 |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | 楕円弧に関する情報を指定する要素を含みます。座標は相対座標として指定されます。 |
| [getRelLineToCol()](#getRelLineToCol--) | 直線セグメントの終点頂点の x および y 座標を含みます。 |
| [getRelMoveToCol()](#getRelMoveToCol--) | 形状の最初の頂点の x および y 座標、またはパスの途中で切れ目が入った後の最初の頂点の x および y 座標を含みます。座標は相対座標として指定されます。 |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | RelQuadBezTo の点の x 座標と y 座標を含みます。座標は相対座標として指定されます。 |
| [getSplineKnotCol()](#getSplineKnotCol--) | スプラインの制御点およびスプラインのノットの x および y 座標を含み、これらはそれぞれ X、Y、A 要素で表されます。 |
| [getSplineStartCol()](#getSplineStartCol--) | スプラインの第2制御点、その第2ノット、第1ノット、最後のノット、およびスプラインの次数の x と y 座標を含みます。 |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | コレクションに項目が存在するかどうかを確認します。 |
| [iterator()](#iterator--) | ジェネリックではないコレクションに対するシンプルな反復をサポートします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | コレクションから ArcTo オブジェクトを削除します。 |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | コレクションから Coordinate オブジェクトを削除します。 |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | コレクションから Ellipse オブジェクトを削除します。 |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | コレクションから EllipticalArcTo オブジェクトを削除します。 |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | コレクションから InfiniteLine オブジェクトを削除します。 |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | コレクションから LineTo オブジェクトを削除します。 |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | コレクションから MoveTo オブジェクトを削除します。 |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | コレクションから NURBSTo オブジェクトを削除します。 |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | コレクションから PolylineTo オブジェクトを削除します。 |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | コレクションから RelCubBezTo オブジェクトを削除します。 |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | コレクションから RelEllipticalArcTo オブジェクトを削除します。 |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | コレクションから RelLineTo オブジェクトを削除します。 |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | コレクションから RelMoveTo オブジェクトを削除します。 |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | コレクションから RelQuadBezTo オブジェクトを削除します。 |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | コレクションから SplineKnot オブジェクトを削除します。 |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | コレクションから SplineStart オブジェクトを削除します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


コレクションに ArcTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


コレクションに Coordinate オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


コレクションに Ellipse オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


コレクションに EllipticalArcTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


コレクションに InfiniteLine オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


コレクションに LineTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


コレクションに MoveTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


コレクションに NURBSTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


コレクションに PolylineTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


コレクションに RelCubBezTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


コレクションに RelEllipticalArcTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


コレクションに RelLineTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


コレクションに RelMoveTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


コレクションに RelQuadBezTo オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


コレクションに SplineKnot オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


コレクションに SplineStart オブジェクトを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


コレクションからすべての要素を削除します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


指定されたインデックスの要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


円弧の X、Y、A 要素でそれぞれ表される x 座標、y 座標、そして弧度を含みます。

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


コレクションに実際に含まれる要素数を取得します。

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


楕円の中心点および楕円上の 2 点の x 座標と y 座標を指定する要素を含みます。

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


楕円弧に関する情報を指定する要素を含みます。

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


無限直線上の 2 点の x 座標と y 座標を指定する要素を含みます。X と Y 要素は最初の点の x 座標と y 座標を指定し、A と B 要素は2 番目の点の x 座標と y 座標を指定します。

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


直線セグメントの終点の x および y 座標を含みます。これらの座標はそれぞれ X 要素と Y 要素に格納されています。

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


シェイプの最初の頂点の x および y 座標、またはパスの途中で切れた後の最初の頂点の x および y 座標を含みます。

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


x および y 座標、最後から2番目のノット位置、最後の重み位置、最初のノット位置、最初の重み位置、そして非均一有理 B スプライン (NURBS) の数式を含みます。この情報はそれぞれ X、Y、A、B、C、D、E 要素で指定されます。

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


ポリラインの最後の点の x および y 座標とポリライン式を含みます。座標は X 要素と Y 要素で指定され、式は A 要素で指定されます。

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


RelCubBezTo の点の x 座標と y 座標を含みます。座標は相対座標として指定されます。

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


楕円弧に関する情報を指定する要素を含みます。座標は相対座標として指定されます。

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


直線セグメントの終点の x および y 座標を含みます。これらの座標はそれぞれ X 要素と Y 要素に格納されています。座標は相対座標として指定されます。

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


形状の最初の頂点の x および y 座標、またはパスの途中で切れ目が入った後の最初の頂点の x および y 座標を含みます。座標は相対座標として指定されます。

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


RelQuadBezTo の点の x 座標と y 座標を含みます。座標は相対座標として指定されます。

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


スプラインの制御点およびスプラインのノットの x および y 座標を含み、これらはそれぞれ X、Y、A 要素で表されます。

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


スプラインの第2制御点、その第2ノット、第1ノット、最後のノット、およびスプラインの次数の x および y 座標を含みます。この情報はそれぞれ X、Y、A、B、C、D 要素に格納されています。

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


コレクションに項目が存在するかどうかを確認します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | 要素のインデックス。 |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


ジェネリックではないコレクションに対するシンプルな反復をサポートします。

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


コレクションから ArcTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


コレクションから Coordinate オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


コレクションから Ellipse オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


コレクションから EllipticalArcTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


コレクションから InfiniteLine オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


コレクションから LineTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


コレクションから MoveTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


コレクションから NURBSTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


コレクションから PolylineTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


コレクションから RelCubBezTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


コレクションから RelEllipticalArcTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


コレクションから RelLineTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


コレクションから RelMoveTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


コレクションから RelQuadBezTo オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


コレクションから SplineKnot オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


コレクションから SplineStart オブジェクトを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

