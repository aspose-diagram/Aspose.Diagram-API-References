---
title: Shape
second_title: Aspose.Diagram for Java API リファレンス
description: マスターページまたはグループシェイプ要素内のシェイプを定義する要素を含みます。
type: docs
weight: 355
url: /ja/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

マスター、ページ、またはグループ シェイプ要素内でシェイプを定義する要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Shape()](#Shape--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [bringForward()](#bringForward--) | シェイプを Z オーダーで 1 つ前に移動します。 |
| [bringToFront()](#bringToFront--) | シェイプを Z オーダーの最前面に移動します。 |
| [centerDrawing()](#centerDrawing--) | ページの範囲に対してシェイプを中央揃えにします。 |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | シェイプに接続されているシェイプの識別子 (ID) を含む配列を返します。 |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | シェイプに依存しているシェイプの識別子を含む配列を返します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | ActiveX コントロールを取得します。 |
| [getActs()](#getActs--) | Act 要素のコレクションを含みます。 |
| [getAlign()](#getAlign--) | シェイプが貼り付けられているガイドまたはガイドポイントに対するシェイプの配置を示します。 |
| [getChars()](#getChars--) | Char 要素のコレクションを含みます。 |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 要素のコレクションを含みます。 |
| [getConnections()](#getConnections--) | Connection 要素のコレクションを含みます。 |
| [getConnectorRule()](#getConnectorRule--) | シェイプに接続されているシェイプ ID と connecton を含む connectorRule を返します。 |
| [getConnectorsType()](#getConnectorsType--) | コネクタのタイプを取得します。 |
| [getControlData()](#getControlData--) | コントロールのデータを取得します。 |
| [getControls()](#getControls--) | Control 要素のコレクションを含みます。 |
| [getData1()](#getData1--) | シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。 |
| [getData2()](#getData2--) | シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。 |
| [getData3()](#getData3--) | シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。 |
| [getDel()](#getDel--) | 要素がローカルで削除されているかどうかを示すフラグです。 |
| [getDiagram()](#getDiagram--) | Visio オブジェクト階層のルート要素です。 |
| [getDisplayText()](#getDisplayText--) | インターフェイスに表示されるテキストを取得します。 |
| [getEvent()](#getEvent--) | シェイプ イベントを制御する数式を指定する要素を含みます。 |
| [getFields()](#getFields--) | Field 要素のコレクションを含みます。 |
| [getFill()](#getFill--) | シェイプとシェイプのドロップシャドウの現在の塗りつぶし書式設定値を含み、パターン、前景色、背景色が含まれます。 |
| [getFillStyle()](#getFillStyle--) | このシェイプが塗りつぶし書式を継承する StyleSheet。 |
| [getForeign()](#getForeign--) | Microsoft Visio ドキュメントで使用される別のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。 |
| [getForeignData()](#getForeignData--) | Windows メタファイル、ビットマップ、または OLE データなどの画像データの MIME (Multipurpose Internet Mail Extensions) エンコード BLOB を含みます。 |
| [getGeoms()](#getGeoms--) | Geom 要素のコレクションを含みます。 |
| [getGroup()](#getGroup--) | グループにシェイプを追加する方法、グループのメンバーを移動する方法、グループを選択する方法を制御する要素を含みます。 |
| [getHelp()](#getHelp--) | Shape 要素のヘルプファイルトピックと著作権情報を指定する要素を含みます。 |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 要素のコレクションを含みます。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getImage()](#getImage--) | ビットマップのガンマ、明るさ、コントラスト、ぼかし、シャープ、ノイズ除去、透明度の値を含みます。 |
| [getInheritChars()](#getInheritChars--) | マスターシェイプから継承されたシェイプの文字値を含みます。 |
| [getInheritFill()](#getInheritFill--) | 親スタイルとマスターシェイプから継承されたシェイプの塗りつぶし書式値を含みます。 |
| [getInheritGeoms()](#getInheritGeoms--) | マスタ形状から継承された形状の Geoms 値を含みます。 |
| [getInheritLine()](#getInheritLine--) | 親スタイルとマスタ形状から継承された形状の line formatting 値を含みます。 |
| [getInheritParas()](#getInheritParas--) | 親スタイルとマスタ形状から継承された形状の paras を含みます。 |
| [getInheritProps()](#getInheritProps--) | マスタ形状から継承された形状の props を含みます。 |
| [getInheritTextBlock()](#getInheritTextBlock--) | 親スタイルとマスタ形状から継承された形状の textblock 値を含みます。 |
| [getInheritUsers()](#getInheritUsers--) | マスタ形状から継承された形状の users を含みます。 |
| [getLayerMem()](#getLayerMem--) | LayerMember 要素を含み、シェイプが割り当てられる各レイヤーを指定します。 |
| [getLayout()](#getLayout--) | シェイプの配置とコネクタのルーティング設定を制御する要素を含みます。 |
| [getLine()](#getLine--) | パターン、太さ、色など、シェイプの線属性を制御する要素を含みます。 |
| [getLineStyle()](#getLineStyle--) | この形状が line formatting を継承する StyleSheet |
| [getMaster()](#getMaster--) | 形状がデータを継承する Master |
| [getMasterShape()](#getMasterShape--) | この属性は、グループ shape のメンバーであり、かつそのグループが master のインスタンスである shape にのみ存在する場合があります。 |
| [getMisc()](#getMisc--) | Shape 要素のヘルプファイルトピックと著作権情報を指定する要素を含みます。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getOneD()](#getOneD--) | 形状が一次元 (1-D) オブジェクトとして動作するかどうかを決定します。 |
| [getPage()](#getPage--) | Visio オブジェクト階層のルート要素です。 |
| [getParas()](#getParas--) | Para 要素のコレクションを含みます。 |
| [getParentShape()](#getParentShape--) | shape の親。 |
| [getProps()](#getProps--) | Prop 要素のコレクションを含みます。 |
| [getProtection()](#getProtection--) | ロックはシェイプへの偶発的な変更を防止するのに役立ちますが、他の状況で Microsoft Visio が値をリセットすることは防げません。 |
| [getPureText()](#getPureText--) | テキスト文字列を取得 |
| [getRootShape()](#getRootShape--) | この shape が master インスタンスの一部である場合、インスタンスのトップレベル shape を返します。 |
| [getScratchs()](#getScratchs--) | Scratch 要素のコレクションを含みます。 |
| [getShapes()](#getShapes--) | Shape 要素のコレクションを含みます。 |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef 要素のコレクションを含みます。 |
| [getTabsCollection()](#getTabsCollection--) | Tab 要素のコレクションを含みます。 |
| [getText()](#getText--) | シェイプのテキストを含みます。 |
| [getTextBlock()](#getTextBlock--) | シェイプのテキスト ブロック内のテキストの配置、余白、デフォルトのタブ位置を指定する要素を含みます。 |
| [getTextStyle()](#getTextStyle--) | この shape が text formatting を継承する StyleSheet。 |
| [getTextXForm()](#getTextXForm--) | シェイプのテキスト ブロックに関する位置情報を指定する要素を含みます。 |
| [getThreeDFormat()](#getThreeDFormat--) | ThreeDFormat を取得します。 |
| [getTwoD()](#getTwoD--) | shape が二次元 (2-D) オブジェクトとして動作するかどうかを決定します。 |
| [getType()](#getType--) | shape のタイプ。 |
| [getUniqueID()](#getUniqueID--) | shape に割り当てられた GUID (グローバルに一意な識別子)。 |
| [getUsers()](#getUsers--) | User 要素のコレクションを含みます。 |
| [getXForm()](#getXForm--) | シェイプに関する一般的な位置情報を指定する要素を含みます。 |
| [getXForm1D()](#getXForm1D--) | 1 次元シェイプの開始点と終了点の x 座標と y 座標を含みます。 |
| [getZOrderIndex()](#getZOrderIndex--) | ガイド shape を除く、z 順序における shape のインデックスを返します。 |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | shape に貼り付けられた shape の識別子を含む配列を返します。 |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | この 2 つの shape が接続されているかどうかを示します。 |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | この shape が別の shape を含んでいるかどうかを示します。 |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | この 2 つの shape が接着されているかどうかを示します。 |
| [isInGroup()](#isInGroup--) | この shape が group shape に含まれているかどうかを示します。 |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | このシェイプが別のシェイプと交差しているかどうかを示します。 |
| [isTextEmpty()](#isTextEmpty--) | シェイプにテキストがあり、テキストが空かどうかを示します。 |
| [move(double dX, double dY)](#move-double-double-) | シェイプを現在位置から dX および dY インチだけ移動させます。 |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | シェイプをページ上の新しい絶対位置に移動させます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | シェイプのテキストやその他を変更した際に、xform、接続、geom を含むシェイプの位置を更新します。 |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | シェイプのテキスト文字列を置き換えます。 |
| [sendBackward()](#sendBackward--) | シェイプを Z オーダーで 1 つ後ろに移動させます。 |
| [sendToBack()](#sendToBack--) | シェイプを Z オーダーの最背面に移動させます。 |
| [setAngle(double angle)](#setAngle-double-) | シェイプの新しい角度を設定します。 |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | このプロパティの説明については、[getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) を参照してください。 |
| [setConnectorsType(int type)](#setConnectorsType-int-) | コネクタのタイプを設定します。 |
| [setData1(String value)](#setData1-java.lang.String-) | このプロパティの説明については、[getData1()](../../com.aspose.diagram/shape\#getData1--) を参照してください。 |
| [setData2(String value)](#setData2-java.lang.String-) | このプロパティの説明については、[getData2()](../../com.aspose.diagram/shape\#getData2--) を参照してください。 |
| [setData3(String value)](#setData3-java.lang.String-) | このプロパティの説明については、[getData3()](../../com.aspose.diagram/shape\#getData3--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/shape\#getDel--) を参照してください。 |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | このプロパティの説明については、[getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) を参照してください。 |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | このプロパティの説明については、[getEvent()](../../com.aspose.diagram/shape\#getEvent--) を参照してください。 |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) を参照してください。 |
| [setHeight(double height)](#setHeight-double-) | シェイプの新しい高さを設定します。 |
| [setID(long value)](#setID-long-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/shape\#getID--) を参照してください。 |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) を参照してください。 |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | このプロパティの説明については、[getMaster()](../../com.aspose.diagram/shape\#getMaster--) を参照してください。 |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | このプロパティの説明については、[getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/shape\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/shape\#getNameU--) を参照してください。 |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | このプロパティの説明については、[getPage()](../../com.aspose.diagram/shape\\#getPage--) を参照してください。 |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | このプロパティの説明については、[getParentShape()](../../com.aspose.diagram/shape\\#getParentShape--) を参照してください。 |
| [setPresetTheme(int value)](#setPresetTheme-int-) | このシェイプにプリセットテーマを適用する |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | このシェイプにプリセットテーマバリアントのクイックスタイルを適用する |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | このシェイプにプリセットテーマバリアントのクイックスタイルを適用する。シェイプスタイルのドロップダウンリストにあるテーマスタイルオプションのように |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | このシェイプにプリセットテーマバリアントを適用する |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | このプロパティの説明については、[getProps()](../../com.aspose.diagram/shape\\#getProps--) を参照してください。 |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | このプロパティの説明については、[getText()](../../com.aspose.diagram/shape\\#getText--) を参照してください。 |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getTextStyle()](../../com.aspose.diagram/shape\\#getTextStyle--) を参照してください。 |
| [setTwoD(boolean value)](#setTwoD-boolean-) | このプロパティの説明については、[getTwoD()](../../com.aspose.diagram/shape\\#getTwoD--) を参照してください。 |
| [setType(int value)](#setType-int-) | このプロパティの説明については、[getType()](../../com.aspose.diagram/shape\\#getType--) を参照してください。 |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/shape\\#getUniqueID--) を参照してください。 |
| [setWidth(double width)](#setWidth-double-) | シェイプの新しい幅を設定します。 |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | このプロパティの説明については、[getXForm()](../../com.aspose.diagram/shape\\#getXForm--) を参照してください。 |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | このプロパティの説明については、[getXForm1D()](../../com.aspose.diagram/shape\\#getXForm1D--) を参照してください。 |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | シェイプのHTMLを作成し、指定された形式でストリームに保存します。 |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | シェイプのHTMLを作成し、指定された形式でストリームに保存します。 |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | HTMLを作成し、ファイルに保存します。 |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | シェイプの画像を作成し、指定された形式でストリームに保存します。 |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | シェイプの画像を作成し、指定された形式でストリームに保存します。 |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | シェイプの画像を作成し、ファイルに保存します。 |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | シェイプのPDFを作成し、ストリームに保存します。 |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | シェイプのPDFを作成し、ストリームに保存します。 |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | シェイプをPDFファイルに保存します。 |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | シェイプをSVGファイルに保存します。 |
| [ungroup()](#ungroup--) | シェイプのグループ解除 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


コンストラクタ。

### bringForward() {#bringForward--}
```
public void bringForward()
```


シェイプを Z オーダーで 1 つ前に移動します。

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


シェイプを Z オーダーの最前面に移動します。

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


ページの範囲に対してシェイプを中央揃えにします。

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


シェイプに接続されているシェイプの識別子 (ID) を含む配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ | int | コネクタの方向性で返されるシェイプIDの配列をフィルタリングします。可能な値についてはRemarksをご参照くださいAspose.Diagram.ConnectedShapesFlags。 |
| categoryFilter | java.lang.String | 指定された categoryString に一致するシェイプの ID に限定して、返されるシェイプ ID の配列をフィルタリングします。 |

**Returns:**
long[] - ID の配列 long。
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


シェイプに依存しているシェイプの識別子を含む配列を返します。

**Returns:**
long[] - ID の配列 long。
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


ActiveX コントロールを取得します。

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act 要素のコレクションを含みます。

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


形状が接着されているガイドまたはガイドポイントに対する形状の配置を示します。Align 要素は、ガイドまたはガイドポイントに接着された形状に対してのみ表示されます。

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Char 要素のコレクションを含みます。

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


ConnectionABCD 要素のコレクションを含みます。

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Connection 要素のコレクションを含みます。

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


シェイプに接続されているシェイプ ID と connecton を含む connectorRule を返します。

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


コネクタのタイプを取得します。

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


コントロールのデータを取得します。

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Control 要素のコレクションを含みます。

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


シェイプに関する追加情報を提供するために使用される任意の文字列値を含みます。

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


要素がローカルで削除されているかを示すフラグです。値が 1 の場合、要素はローカルで削除されたことを示します。

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Visio オブジェクト階層のルート要素です。

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


インターフェイスに表示されるテキストを取得します。

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


シェイプ イベントを制御する数式を指定する要素を含みます。

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Field 要素のコレクションを含みます。

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


シェイプとシェイプのドロップシャドウの現在の塗りつぶし書式設定値を含み、パターン、前景色、背景色が含まれます。

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


このシェイプが塗りつぶし書式を継承する StyleSheet。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Microsoft Visio ドキュメントで使用される他のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。また、オブジェクトの画像が境界内でオフセットされる距離を指定する要素も含みます。

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Windows メタファイル、ビットマップ、または OLE データなどの画像データの MIME (Multipurpose Internet Mail Extensions) エンコード BLOB を含みます。

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Geom 要素のコレクションを含みます。

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


グループにシェイプを追加する方法、グループのメンバーを移動する方法、グループを選択する方法を制御する要素を含みます。

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Shape 要素のヘルプファイルトピックと著作権情報を指定する要素を含みます。

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink 要素のコレクションを含みます。

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


要素の親要素内における一意の ID。

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


ビットマップのガンマ、明るさ、コントラスト、ぼかし、シャープ、ノイズ除去、透明度の値を含みます。

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


マスターシェイプから継承されたシェイプの文字値を含みます。

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


親スタイルとマスターシェイプから継承されたシェイプの塗りつぶし書式値を含みます。

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


マスタ形状から継承された形状の Geoms 値を含みます。

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


親スタイルとマスタ形状から継承された形状の line formatting 値を含みます。

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


親スタイルとマスタ形状から継承された形状の paras を含みます。

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


マスタ形状から継承された形状の props を含みます。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


親スタイルとマスタ形状から継承された形状の textblock 値を含みます。

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


マスタ形状から継承された形状の users を含みます。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


LayerMember 要素を含み、シェイプが割り当てられる各レイヤーを指定します。

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


シェイプの配置とコネクタのルーティング設定を制御する要素を含みます。

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


シェイプの線属性（パターン、太さ、色など）を制御する要素が含まれます。これらの要素は、線端が書式設定されているか（例: 矢じり）、線端書式のサイズ、線に適用される丸みの円の半径、そして線のキャップスタイル（丸形または四角形）を決定します。

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


この形状が line formatting を継承する StyleSheet

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


形状がデータを継承する Master

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


この属性は、グループ シェイプのメンバーであり、かつそのグループがマスターのインスタンスであるシェイプにのみ存在する可能性があります。属性には、マスター内の対応するサブシェイプを参照する ID が含まれます。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Shape 要素のヘルプファイルトピックと著作権情報を指定する要素を含みます。

**Returns:**
[Misc](../../com.aspose.diagram/misc)
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
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


シェイプが一次元 (1-D) オブジェクトとして動作するかどうかを決定します。読み取り専用です。

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Visio オブジェクト階層のルート要素です。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Para 要素のコレクションを含みます。

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


shape の親。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 要素のコレクションを含みます。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


ロック機能はシェイプへの偶発的な変更を防止するのに役立ちますが、他の状況で Microsoft Visio が値をリセットすることは防げません。また、ShapeSheet ウィンドウで行われた変更からも保護されません。

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


テキスト文字列を取得

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


このシェイプがマスター インスタンスの一部である場合、インスタンスの最上位シェイプを返します。読み取り専用です。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 要素のコレクションを含みます。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape 要素のコレクションを含みます。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef 要素のコレクションを含みます。

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Tab 要素のコレクションを含みます。

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


シェイプのテキストを含みます。

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


シェイプのテキスト ブロック内のテキストの配置、余白、デフォルトのタブ位置を指定する要素を含みます。

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


この shape が text formatting を継承する StyleSheet。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


シェイプのテキスト ブロックに関する位置情報を指定する要素を含みます。

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


ThreeDFormat を取得します。

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


shape が二次元 (2-D) オブジェクトとして動作するかどうかを決定します。

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


シェイプのタイプです。次のいずれかの値になる可能性があります: Group、Shape、Guide、または Foreign。

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


shape に割り当てられた GUID (グローバルに一意な識別子)。

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User 要素のコレクションを含みます。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


シェイプに関する一般的な位置情報を指定する要素を含みます。

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


1 次元シェイプの開始点と終了点の x および y 座標が含まれます。この要素は 1 次元シェイプにのみ表示されます。

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


ガイド shape を除く、z 順序における shape のインデックスを返します。

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


shape に貼り付けられた shape の識別子を含む配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ | int | 返されるシェイプの接続ポイントの次元性と方向性です。可能な値については Remarks を参照してください Aspose.Diagram.GluedShapesFlags。 |
| categoryFilter | java.lang.String | 指定された categoryString に一致するシェイプの ID に限定して、返されるシェイプ ID の配列をフィルタリングします。 |
| otherShape | [Shape](../../com.aspose.diagram/shape) | オプション: 返されるシェイプが追加で貼り付けられる必要がある別のシェイプで、[Shape](../../com.aspose.diagram/shape) または null にできます。 |

**Returns:**
long[] - ID の配列 long。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


この 2 つの shape が接続されているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | シェイプ |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


この shape が別の shape を含んでいるかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


この 2 つの shape が接着されているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | シェイプ |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


この shape が group shape に含まれているかどうかを示します。

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


このシェイプが別のシェイプと交差しているかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


シェイプにテキストがあり、テキストが空かどうかを示します。

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


シェイプを現在位置から dX および dY インチだけ移動させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dX | double | X オフセット double。 |
| dY | double | Y オフセット double。 |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


シェイプをページ上の新しい絶対位置に移動させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newPinX | double | 親の原点に対するシェイプのピン（回転中心）の新しい X 座標です。double。 |
| newPinY | double | 親の原点に対するシェイプのピン（回転中心）の新しい Y 座標です。double。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


シェイプのテキストやその他を変更した際に、xform、接続、ジオメトリを含むシェイプの位置を更新します。シェイプのテキストなどのデータを取得し、シェイプの位置を計算します。このメソッドはシェイプのデータを更新するためだけに使用されます。

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


シェイプのテキスト文字列を置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| テキスト | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


シェイプを Z オーダーで 1 つ後ろに移動させます。

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


シェイプを Z オーダーの最背面に移動させます。

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


シェイプの新しい角度を設定します。角度の単位はラジアンです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | double | 単位がラジアンで、度ではない新しい角度です。double。 |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


このプロパティの説明については、[getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


コネクタのタイプを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


このプロパティの説明については、[getData1()](../../com.aspose.diagram/shape\#getData1--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


このプロパティの説明については、[getData2()](../../com.aspose.diagram/shape\#getData2--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


このプロパティの説明については、[getData3()](../../com.aspose.diagram/shape\#getData3--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/shape\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


このプロパティの説明については、[getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


このプロパティの説明については、[getEvent()](../../com.aspose.diagram/shape\#getEvent--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


シェイプの新しい高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/shape\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


このプロパティの説明については、[getMaster()](../../com.aspose.diagram/shape\#getMaster--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


このプロパティの説明については、[getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/shape\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/shape\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


このプロパティの説明については、[getPage()](../../com.aspose.diagram/shape\\#getPage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


このプロパティの説明については、[getParentShape()](../../com.aspose.diagram/shape\\#getParentShape--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


このシェイプにプリセットテーマを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


このシェイプにプリセットテーマバリアントのクイックスタイルを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


このシェイプにプリセットテーマバリアントのクイックスタイルを適用する。シェイプスタイルのドロップダウンリストにあるテーマスタイルオプションのように

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


このシェイプにプリセットテーマバリアントを適用する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


このプロパティの説明については、[getProps()](../../com.aspose.diagram/shape\\#getProps--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


このプロパティの説明については、[getText()](../../com.aspose.diagram/shape\\#getText--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


このプロパティの説明については、[getTextStyle()](../../com.aspose.diagram/shape\\#getTextStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


このプロパティの説明については、[getTwoD()](../../com.aspose.diagram/shape\\#getTwoD--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


このプロパティの説明については、[getType()](../../com.aspose.diagram/shape\\#getType--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/shape\\#getUniqueID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


シェイプの新しい幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


このプロパティの説明については、[getXForm()](../../com.aspose.diagram/shape\\#getXForm--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


このプロパティの説明については、[getXForm1D()](../../com.aspose.diagram/shape\\#getXForm1D--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


シェイプのHTMLを作成し、指定された形式でストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


シェイプのHTMLを作成し、指定された形式でストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


HTMLを作成し、ファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


シェイプの画像を作成し、指定された形式でストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


シェイプの画像を作成し、指定された形式でストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


シェイプのPDFを作成し、ストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


シェイプのPDFを作成し、ストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


シェイプをPDFファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


シェイプをSVGファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


シェイプのグループ解除

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

