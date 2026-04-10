---
title: ページ
second_title: Aspose.Diagram for Java API リファレンス
description: ドキュメント内のページを定義する要素を含みます。
type: docs
weight: 260
url: /ja/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

ドキュメント内のページを定義する要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Page()](#Page--) | コンストラクタ。 |
| [Page(int ID)](#Page-int-) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Activex Control を作成します。 |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | シェイプにコメントを追加します。 |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | 定義された PinX と PinY を使用してコメントを追加します。 |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | シェイプの ID を使用してシェイプにコメントを追加します。 |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | マスターで作成されたシェイプを特定のページに追加します。 |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | 定義された PinX、PinY、幅、そして高さを使用して、ページ上にマスターで作成されたシェイプを追加します。 |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | 定義された PinX と PinY を使用して、ページ上にマスターで作成されたシェイプを追加します。 |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | 定義された PinX と PinY を使用してテキストを追加します。 |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | 定義された PinX と PinY を使用してテキストを追加します。 |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | 全ページにスタイルを適用します。 |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | シェイプの自動間隔調整 |
| [bringForward(long shapeId)](#bringForward-long-) | ID で定義されたシェイプを Z オーダーで 1 つ前に移動します。 |
| [bringToFront(long shapeId)](#bringToFront-long-) | ID で定義されたシェイプを Z オーダーの最前面に移動します。 |
| [centerDrawing()](#centerDrawing--) | ページの範囲に対してページ上のシェイプを中央揃えにします。 |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | コネクタを使用してシェイプを接続します。 |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | コネクタを使用してシェイプを接続します。 |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | コネクタを使用してシェイプを接続します。 |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | コネクタインデックスを使用してシェイプを接続します。 |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | コネクタインデックスを使用してシェイプを接続します。 |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | 楕円を描画するプロセス。 |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | 単一の線を描画するプロセス。 |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | 線を描画するプロセス。 |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | ポリラインを描画するプロセス。 |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | 矩形を描画するプロセス。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | 図面のレビュアーが別々のマークアップオーバーレイでマークアップした元の図面ページの ID。 |
| [getBackPage()](#getBackPage--) | ページの背景ページ。 |
| [getBackground()](#getBackground--) | ページが背景ページかどうかを示すフラグ。 |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 図面内の 2 つの形状間の各接続について Connect 要素を含みます。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getPageSheet()](#getPageSheet--) | ページまたはマスター要素のページシートを定義する要素を含みます。 |
| [getPages()](#getPages--) | ページコレクション。 |
| [getReviewerID()](#getReviewerID--) | マークアップオーバーレイに関連付けられたレビュアーの ID。 |
| [getShapes()](#getShapes--) | シェイプ コレクション。 |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX と ViewCenterY は、新しいビュー（ウィンドウ）が最初に開かれたときにページ上で想定する中心点を指定します。 |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX と ViewCenterY は、新しいビュー（ウィンドウ）が最初に開かれたときにページ上で想定する中心点を指定します。 |
| [getViewScale()](#getViewScale--) | ページの新しいビュー（ウィンドウ）が開かれる際に使用するデフォルトの拡大率。 |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | シェイプをコネクタの BeginX に接続 |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | シェイプをコネクタの EndX に接続 |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | シェイプを接続。 |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | シェイプを接続 |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | コンテナ内のシェイプを接続 |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | 接続名を使用してコンテナ内のシェイプを接続 |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | コンテナ内で接続 ID によってシェイプを接続 |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | ページのシェイプを配置し、またはコネクタの経路を再設定します。 |
| [moveTo(int index)](#moveTo-int-) | ページをページ集合内の別の場所に移動します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | ID で定義されたシェイプを Z オーダーで 1 つ後ろに移動します。 |
| [sendToBack(long shapeId)](#sendToBack-long-) | ID で定義されたシェイプを Z オーダーの最背面に移動します。 |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | このプロパティの説明については、[getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) を参照してください。 |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | このプロパティの説明については、[getBackPage()](../../com.aspose.diagram/page\#getBackPage--) を参照してください。 |
| [setBackground(int value)](#setBackground-int-) | このプロパティの説明については、[getBackground()](../../com.aspose.diagram/page\#getBackground--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/page\#getID--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/page\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/page\#getNameU--) を参照してください。 |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | このプロパティの説明については、[getPages()](../../com.aspose.diagram/page\#getPages--) を参照してください。 |
| [setPresetTheme(int value)](#setPresetTheme-int-) | このページにプリセットテーマを適用する |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | このページにプリセットテーマバリアントのクイックスタイルを適用する |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | このページにプリセットテーマバリアントを適用する |
| [setReviewerID(int value)](#setReviewerID-int-) | このプロパティの説明については、[getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) を参照してください |
| [setViewCenterX(double value)](#setViewCenterX-double-) | このプロパティの説明については、[getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) を参照してください |
| [setViewCenterY(double value)](#setViewCenterY-double-) | このプロパティの説明については、[getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) を参照してください |
| [setViewScale(double value)](#setViewScale-double-) | このプロパティの説明については、[getViewScale()](../../com.aspose.diagram/page\#getViewScale--) を参照してください |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


コンストラクタ。

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


コンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Activex Control を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | int | コントロールのタイプです。 |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅をインチ単位で指定します。 |
| height | double | シェイプの高さをインチ単位で指定します。 |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


シェイプにコメントを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | コメントを追加しているシェイプを指定します。 |
| comment | java.lang.String | コメント文字列です。 |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


定義された PinX と PinY を使用してコメントを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するコメントのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するコメントのピン（回転中心）のY座標を指定します。 |
| comment | java.lang.String | コメント文字列です。 |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


シェイプの ID を使用してシェイプにコメントを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | コメント文字列です。 |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


マスターで作成されたシェイプを特定のページに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 新しいシェイプオブジェクト[Shape](../../com.aspose.diagram/shape)。 |
| masterName | java.lang.String | マスターの名前です。 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| ストリーム | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


定義された PinX、PinY、幅、そして高さを使用して、ページ上にマスターで作成されたシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅をインチ単位で指定します。 |
| height | double | シェイプの高さをインチ単位で指定します。 |
| masterName | java.lang.String | マスターの名前です。 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


定義された PinX と PinY を使用して、ページ上にマスターで作成されたシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| masterName | java.lang.String | マスターの名前です。 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


定義された PinX と PinY を使用してテキストを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するテキストのピン（回転の中心）のx座標を指定します。 |
| pinY | double | ページに対するテキストのピン（回転の中心）のy座標を指定します。 |
| width | double |  |
| height | double |  |
| テキスト | java.lang.String | テキスト文字列。 |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


定義された PinX と PinY を使用してテキストを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するテキストのピン（回転の中心）のx座標を指定します。 |
| pinY | double | ページに対するテキストのピン（回転の中心）のy座標を指定します。 |
| width | double | テキストの幅を指定します。 |
| height | double | テキストの高さを指定します。 |
| テキスト | java.lang.String | テキスト文字列。 |
| fontName | java.lang.String | テキストのフォント名。 |
| fontColor | java.lang.String | テキストのフォント色。 |
| size | double | テキストのフォントサイズ。 |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


全ページにスタイルを適用します。デフォルト値は -1 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textStyle | int | テキストスタイルID。 |
| lineStyle | int | ラインスタイルID。 |
| fillStyle | int | 塗りつぶしスタイルID。 |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


シェイプの自動間隔調整

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | シェイプが自動的に間隔を持つように指定します。 |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


ID で定義されたシェイプを Z オーダーで 1 つ前に移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeId | long | shape.long の ID。 |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


ID で定義されたシェイプを Z オーダーの最前面に移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeId | long | shape.long の ID。 |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


ページの範囲に対してページのシェイプを中央揃えします。シェイプを中央揃えしても、シェイプ同士の相対位置は変わりません。

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


コネクタを使用してシェイプを接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | コネクタが開始するシェイプは [Shape](../../com.aspose.diagram/shape) です。 |
| placeFrom | int | コネクタが接続される最初のシェイプ上の位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | コネクタが終了するシェイプ [Shape](../../com.aspose.diagram/shape)。 |
| placeTo | int | コネクタが接続される2番目のシェイプ上の位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| connector | [Shape](../../com.aspose.diagram/shape) | タイプが Dynamic connector のシェイプ [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


コネクタを使用してシェイプを接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | コネクタが開始するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| placeFrom | int | コネクタが接続される最初のシェイプ上の位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| shapeToId | long | コネクタが終了するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| placeTo | int | コネクタが接続される2番目のシェイプ上の位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| connectorId | long | タイプが Dynamic connector のシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


コネクタを使用してシェイプを接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | コネクタが開始するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| fromConnectionName | java.lang.String | コネクタが接続される最初のシェイプ上の接続名。 |
| shapeToId | long | コネクタが終了するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| toConnectionName | java.lang.String | コネクタが接続される2番目のシェイプ上の接続名。 |
| connectorId | long | タイプが Dynamic connector のシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


コネクタインデックスを使用してシェイプを接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | コネクタが開始するシェイプは [Shape](../../com.aspose.diagram/shape) です。 |
| fromIndex | int | 最初のシェイプ上の接続のインデックス |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | コネクタが終了するシェイプ [Shape](../../com.aspose.diagram/shape)。 |
| toIndex | int | 2番目のシェイプ上の接続のインデックス |
| connector | [Shape](../../com.aspose.diagram/shape) | タイプが Dynamic connector のシェイプ [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


コネクタインデックスを使用してシェイプを接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | コネクタが開始するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| fromIndex | int | 最初のシェイプ上の接続のインデックス |
| shapeToId | long | コネクタが終了するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| toIndex | int | 2番目のシェイプ上の接続のインデックス |
| connectorId | long | タイプが Dynamic connector のシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


楕円を描画するプロセス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅を指定します |
| height | double | シェイプの高さを指定します |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


単一の線を描画するプロセス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| beginX | double | ページに対するシェイプの位置の開始 x 座標を指定します。 |
| beginY | double | ページに対するシェイプの位置の開始 y 座標を指定します。 |
| endX | double | ページに対するシェイプの位置の終了 x 座標を指定します。 |
| endY | double | ページに対する形状の位置の終端 y 座標を指定します。 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


線を描画するプロセス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅を指定します |
| height | double | シェイプの高さを指定します |
| xyArray | double[] | 新しい形状の点を定義する、交互に並んだ x と y の値の配列 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


ポリラインを描画するプロセス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅を指定します |
| height | double | シェイプの高さを指定します |
| xyArray | double[] | 新しい形状の点を定義する、交互に並んだ x と y の値の配列 |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


矩形を描画するプロセス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅を指定します |
| height | double | シェイプの高さを指定します |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


図面のレビュアーが別々のマークアップオーバーレイでマークアップした元の図面ページの ID。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


ページの背景ページ。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


ページが背景ページかどうかを示すフラグ。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


図面内の 2 つの形状間の各接続について Connect 要素を含みます。

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


要素の親要素内における一意の ID。

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


要素の名前。

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


要素のユニバーサル名。

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


ページまたはマスター要素のページシートを定義する要素を含みます。

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


ページコレクション。

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


マークアップオーバーレイに関連付けられたレビュアーの ID。

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


シェイプ コレクション。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX と ViewCenterY は、新しいビュー（ウィンドウ）が最初に開かれたときにページ上で想定する中心点を指定します。

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX と ViewCenterY は、新しいビュー（ウィンドウ）が最初に開かれたときにページ上で想定する中心点を指定します。

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


ページの新しいビュー（ウィンドウ）を開く際に使用するデフォルトの拡大率です。例: 1 = 100%、1.5 = 150% など。

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


シェイプをコネクタの BeginX に接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | コネクタが開始するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| connectionName | java.lang.String | コネクタが接続される形状上の接続名です。 |
| connectorId | long | タイプが Dynamic connector のシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


シェイプをコネクタの EndX に接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeToId | long | コネクタが終了するシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |
| connectionName | java.lang.String | コネクタが接続される2番目のシェイプ上の接続名。 |
| connectorId | long | タイプが Dynamic connector のシェイプの ID [Shape](../../com.aspose.diagram/shape)。 |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


シェイプを接続。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | [Shape](../../com.aspose.diagram/shape) から接着される形状です。 |
| placeTo | int | 最初の形状上で Aspose.Diagram.Manipulation.ConnectionPointPlace を接着する位置です。 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | [Shape](../../com.aspose.diagram/shape) に接着する形状です。 |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


シェイプを接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape) から接着される形状の ID です。 |
| placeTo | int | 最初の形状上で Aspose.Diagram.Manipulation.ConnectionPointPlace を接着する位置です。 |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape) に接着する形状の ID です。 |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


コンテナ内のシェイプを接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape) から接着される形状の ID です。 |
| shapeToBeginConnectionIndex | int | 最初の接続インデックス上で接着する位置です。 |
| shapeToEndConnectionIndex | int | 終了接続インデックス上で接着する位置です。 |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape) に接着する形状の ID です。 |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


接続名を使用してコンテナ内のシェイプを接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape) から接着される形状の ID です。 |
| shapeToBeginConnectionName | java.lang.String | 最初の接続名上で接着する位置です。 |
| shapeToEndConnectionName | java.lang.String | 終了接続名上で接着する位置です。 |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape) に接着する形状の ID です。 |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


コンテナ内で接続 ID によってシェイプを接続

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape) から接着される形状の ID です。 |
| shapeToBeginConnectionID | int | 最初の接続 ID 上で接着する位置です。 |
| shapeToEndConnectionID | int | 終了接続 ID 上で接着する位置です。 |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape) に接着する形状の ID です。 |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


ページのシェイプを配置し、またはコネクタの経路を再設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions) を使用してレイアウトのオプションを構成します。 |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


ページをページ集合内の別の場所に移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | 宛先ページインデックス。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


ID で定義されたシェイプを Z オーダーで 1 つ後ろに移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeId | long | shape.long の ID。 |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


ID で定義されたシェイプを Z オーダーの最背面に移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeId | long | shape.long の ID。 |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


このプロパティの説明については、[getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


このプロパティの説明については、[getBackPage()](../../com.aspose.diagram/page\#getBackPage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


このプロパティの説明については、[getBackground()](../../com.aspose.diagram/page\#getBackground--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/page\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/page\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/page\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


このプロパティの説明については、[getPages()](../../com.aspose.diagram/page\#getPages--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


このページにプリセットテーマを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


このページにプリセットテーマバリアントのクイックスタイルを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


このページにプリセットテーマバリアントを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


このプロパティの説明については、[getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


このプロパティの説明については、[getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


このプロパティの説明については、[getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


このプロパティの説明については、[getViewScale()](../../com.aspose.diagram/page\#getViewScale--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

