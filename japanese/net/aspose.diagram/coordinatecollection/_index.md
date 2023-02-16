---
title: CoordinateCollection
second_title: Aspose.Diagram for .NET API リファレンス
description: 座標集
type: docs
weight: 1040
url: /ja/net/aspose.diagram/coordinatecollection/
---
## CoordinateCollection class

座標集。

```csharp
public class CoordinateCollection : Collection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArcToCol](../../aspose.diagram/coordinatecollection/arctocol/) { get; } | X、Y、および A 要素によってそれぞれ表される円弧の x および y 座標と弓形を含みます。 |
| [Count](../../aspose.diagram/collection/count/) { get; } | コレクションに実際に含まれる要素の数を取得します。 |
| [EllipseCol](../../aspose.diagram/coordinatecollection/ellipsecol/) { get; } | 楕円の中心点と楕円上の 2 点の x 座標と y 座標を指定する要素を含みます。 |
| [EllipticalArcToCol](../../aspose.diagram/coordinatecollection/ellipticalarctocol/) { get; } | 楕円弧に関する情報を指定する要素が含まれています。 |
| [InfiniteLineCol](../../aspose.diagram/coordinatecollection/infinitelinecol/) { get; } | 無限直線上の 2 点の x 座標と y 座標を指定する要素を含みます。 X 要素と Y 要素は最初の点の x 座標と y 座標を指定し、A 要素と B 要素は 2 番目の点の x 座標と y 座標を指定します。 |
| [Item](../../aspose.diagram/coordinatecollection/item/) { get; } | 指定されたインデックスの要素を取得します。 |
| [LineToCol](../../aspose.diagram/coordinatecollection/linetocol/) { get; } | 直線セグメントの終了頂点の x 座標と y 座標が含まれます。これらの座標は、それぞれ X 要素と Y 要素に含まれています。 |
| [MoveToCol](../../aspose.diagram/coordinatecollection/movetocol/) { get; } | 形状の最初の頂点の x 座標と y 座標、またはパスの中断後の最初の頂点の x 座標と y 座標が含まれます。 |
| [NURBSToCol](../../aspose.diagram/coordinatecollection/nurbstocol/) { get; } | x 座標と y 座標、最後から 2 番目のノットの位置、最後の重みの位置、最初のノットの位置、最初の重みの位置、および非一様有理 B スプライン (NURBS) の式が含まれます。この情報は、それぞれ X、Y、A、B、C、D、および E 要素で指定されます。 |
| [PolylineToCol](../../aspose.diagram/coordinatecollection/polylinetocol/) { get; } | ポリラインの最後の点の x 座標と y 座標、およびポリライン式が含まれます。 X要素とY要素に座標を指定し、A要素に式を指定します。 |
| [RelCubBezToCol](../../aspose.diagram/coordinatecollection/relcubbeztocol/) { get; } | RelCubBezTo のポイントの x 座標と y 座標が含まれます。座標は相対座標として指定されます。 |
| [RelEllipticalArcToCol](../../aspose.diagram/coordinatecollection/relellipticalarctocol/) { get; } | 楕円弧に関する情報を指定する要素が含まれます。座標は相対座標として指定されます。 |
| [RelLineToCol](../../aspose.diagram/coordinatecollection/rellinetocol/) { get; } | 直線セグメントの終了頂点の x 座標と y 座標が含まれます。これらの座標はそれぞれ X 要素と Y 要素に含まれます。座標は相対座標として指定されます。 |
| [RelMoveToCol](../../aspose.diagram/coordinatecollection/relmovetocol/) { get; } | 形状の最初の頂点の x 座標と y 座標、またはパスのブレーク後の最初の頂点の x 座標と y 座標が含まれます。座標は相対座標として指定されます。 |
| [RelQuadBezToCol](../../aspose.diagram/coordinatecollection/relquadbeztocol/) { get; } | RelQuadBezTo のポイントの x 座標と y 座標が含まれます。座標は相対座標として指定されます。 |
| [SplineKnotCol](../../aspose.diagram/coordinatecollection/splineknotcol/) { get; } | スプラインの制御点とスプラインのノットの x 座標と y 座標を含み、それぞれ X、Y、A 要素で表されます。 |
| [SplineStartCol](../../aspose.diagram/coordinatecollection/splinestartcol/) { get; } | スプラインの 2 番目の制御点、2 番目のノット、最初のノット、最後のノット、およびスプラインの次数の x 座標と y 座標が含まれます。この情報は、それぞれ X、Y、A、B、C、および D 要素に含まれています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.diagram/coordinatecollection/add/#add)(ArcTo) | ArcTo オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_1)(Coordinate) | Coordinate オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_2)(Ellipse) | Ellipse オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_3)(EllipticalArcTo) | EllipticalArcTo オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_4)(InfiniteLine) | InfiniteLine オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_5)(LineTo) | LineTo オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_6)(MoveTo) | コレクションに MoveTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_7)(NURBSTo) | コレクションに NURBSTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_8)(PolylineTo) | コレクションに PolylineTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_9)(RelCubBezTo) | コレクションに RelCubBezTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_10)(RelEllipticalArcTo) | RelEllipticalArcTo オブジェクトをコレクションに追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_11)(RelLineTo) | コレクションに RelLineTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_12)(RelMoveTo) | コレクションに RelMoveTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_13)(RelQuadBezTo) | コレクションに RelQuadBezTo オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_14)(SplineKnot) | コレクションに SplineKnot オブジェクトを追加します。 |
| [Add](../../aspose.diagram/coordinatecollection/add/#add_15)(SplineStart) | コレクションに SplineStart オブジェクトを追加します。 |
| [Clear](../../aspose.diagram/collection/clear/)() | コレクションからすべての要素を削除します。 |
| [GetEnumerator](../../aspose.diagram/collection/getenumerator/)() | 非ジェネリック コレクションに対する単純な反復をサポートします。 |
| [IsExist](../../aspose.diagram/collection/isexist/)(int) | コレクションに存在するアイテムです。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove)(ArcTo) | コレクションから ArcTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_1)(Coordinate) | Coordinate オブジェクトをコレクションから削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_2)(Ellipse) | Ellipse オブジェクトをコレクションから削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_3)(EllipticalArcTo) | EllipticalArcTo オブジェクトをコレクションから削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_4)(InfiniteLine) | InfiniteLine オブジェクトをコレクションから削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_5)(LineTo) | コレクションから LineTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_6)(MoveTo) | コレクションから MoveTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_7)(NURBSTo) | NURBSTo オブジェクトをコレクションから削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_8)(PolylineTo) | コレクションから PolylineTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_9)(RelCubBezTo) | コレクションから RelCubBezTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_10)(RelEllipticalArcTo) | コレクションから RelEllipticalArcTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_11)(RelLineTo) | コレクションから RelLineTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_12)(RelMoveTo) | コレクションから RelMoveTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_13)(RelQuadBezTo) | コレクションから RelQuadBezTo オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_14)(SplineKnot) | コレクションから SplineKnot オブジェクトを削除します。 |
| [Remove](../../aspose.diagram/coordinatecollection/remove/#remove_15)(SplineStart) | コレクションから SplineStart オブジェクトを削除します。 |

### 関連項目

* class [Collection](../collection/)
* 名前空間 [Aspose.Diagram](../../aspose.diagram/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
