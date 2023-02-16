---
title: Page
second_title: Aspose.Diagram for .NET API リファレンス
description: ドキュメント内のページを定義する要素が含まれています.
type: docs
weight: 2490
url: /ja/net/aspose.diagram/page/
---
## Page class

ドキュメント内のページを定義する要素が含まれています.

```csharp
public class Page : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Page](page/#constructor)() | コンストラクター. |
| [Page](page/#constructor_1)(int) | コンストラクター. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | 図面のレビュー担当者によって別のマークアップ オーバーレイでマークアップされた元の図面ページの ID. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | ページが背景ページかどうかを示すフラグ。 |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | ページの背景ページ。 |
| [Connects](../../aspose.diagram/page/connects/) { get; } | 図面内の 2 つの図形間の接続ごとに Connect 要素が含まれます。 |
| [ID](../../aspose.diagram/page/id/) { get; set; } | 親要素内の要素の一意の ID. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | 要素の名前。 |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | 要素の汎用名. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | ページ コレクション. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Page 要素または Master 要素のページ シートを定義する要素が含まれています。 |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | このページにプリセット テーマを適用します |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | プリセット テーマ バリアント クイックスタイルをこのページに適用 |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | このページにプリセットのテーマ バリアントを適用します |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | マークアップ オーバーレイに関連付けられたレビュー担当者の ID. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | 形状コレクション. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX と ViewCenterY は、新しいビュー (ウィンドウ) が最初に開いたときに想定されるページの中心点を指定します。 |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX と ViewCenterY は、新しいビュー (ウィンドウ) が最初に開いたときに想定されるページの中心点を指定します。 |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | ページの新しいビュー (ウィンドウ) が開かれたときに使用するデフォルトの倍率。たとえば、1 = 100%。 1.5 = 150% など。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Activex コントロールを作成します。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | シェイプの ID を持つシェイプにコメントを追加します。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | 形状にコメントを追加します。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | PinX と PinY を定義したコメントを追加します。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | マスターによって作成された形状を特定のページに追加します。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | 定義済みの PinX と PinY を使用して、マスターによって作成された形状をページに追加します。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | 定義された PinX、PinY、Width、および Height を使用して、マスターによって作成された形状をページに追加します。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | 定義された PinX と PinY を持つテキストを追加します。 |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | 定義された PinX と PinY を持つテキストを追加します。 |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | ページ全体にスタイルを適用します。 |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | 自動空間形状 |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | ID で定義されたシェイプを z オーダーの 1 つ前の位置に移動します。 |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | ID で定義された形状を z オーダーの前に移動します。 |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | ページの範囲に対してページの図形を中央に配置します。 図形を中央に配置しても、互いの位置は変わりません。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | コネクタを介して図形を接続します。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | コネクタを介して図形を接続します。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | コネクタを介して図形を接続します。 |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | コネクタ インデックスを介して図形を接続します。 |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | コネクタ インデックスを介して図形を接続します。 |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | アンマネージ リソースの解放、解放、または リセットに関連するアプリケーション定義のタスクを実行します。 |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | ベジエを描画するプロセス. ポイントの長さは 3 以上である必要があります. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | 楕円を描く過程. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | 一本の線を引く工程. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | 線を引く工程. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | 線を引く工程. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | ポリラインを描画するプロセス. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | ポリラインの描画処理. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | 長方形を描画するプロセス. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | スプラインを描く過程. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | グルー形状 |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | グルー形状. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | container の形を接着します |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | 接続名 を使用してコンテナー内の形状を接着します |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | container の接続 ID でシェイプを接着します |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | 形状をコネクタの BeginX に接着します |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | 形状をコネクタの EndX に接着します |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | 図形をレイアウトしたり、ページのコネクタを再ルーティングしたりします。 |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | ページをページ内の別の場所に移動します。 |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | ID で定義された形状を z オーダーで 1 つ後ろに移動します。 |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | ID で定義された形状を z オーダーの後ろに移動します。 |

### 関連項目

* 名前空間 [Aspose.Diagram](../../aspose.diagram/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
