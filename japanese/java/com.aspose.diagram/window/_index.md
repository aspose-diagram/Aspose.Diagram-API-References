---
title: Window
second_title: Aspose.Diagram for Java API リファレンス
description: Microsoft Visio インスタンス内の開いているウィンドウを表します。
type: docs
weight: 444
url: /ja/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Microsoft Visio インスタンス内の開いているウィンドウを表します。この要素には、DatadiagramML ファイルが Visio によって最初に開かれたときに、アプリケーション ワークスペース内でユーザー インターフェイス ウィンドウを正確に再作成するために必要な情報が含まれています。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Window()](#Window--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | コンテナの ID: ページ、シート、またはマスター。 |
| [getContainerType()](#getContainerType--) | 次のいずれかの値を取ります: Document、Page、または Master。 |
| [getDocument()](#getDocument--) | このウィンドウに表示されているドキュメントのファイル パス。 |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | ドキュメントまたはウィンドウに対して動的グリッド機能が有効かどうかを指定します。 |
| [getGlueSettings()](#getGlueSettings--) | ドキュメントで接着が有効な場合に、シェイプが接着するオブジェクトを指定します。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getMaster()](#getMaster--) | このウィンドウがマスターを表示している場合のマスター ID。 |
| [getPage()](#getPage--) | このウィンドウがページを表示している場合のページ ID。 |
| [getParentWindow()](#getParentWindow--) | このステンシル ウィンドウが含まれるウィンドウの ID。 |
| [getReadOnly()](#getReadOnly--) | このステンシルがドキュメント ステンシルでない場合の読み取り専用フラグ。 |
| [getSheet()](#getSheet--) | コンテナ内のシートの ID。 |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | ウィンドウに接続ポイントを表示するかどうかを指定します。 |
| [getShowGrid()](#getShowGrid--) | 図面ウィンドウにグリッドを表示するかどうかを指定します。 |
| [getShowGuides()](#getShowGuides--) | 図面ウィンドウにガイドを表示するかどうかを指定します。 |
| [getShowPageBreaks()](#getShowPageBreaks--) | ウィンドウに改ページ記号を表示するかどうかを指定します。 |
| [getShowRulers()](#getShowRulers--) | 図面ウィンドウに定規を表示するかどうかを指定します。 |
| [getSnapAngles()](#getSnapAngles--) | SnapAngle 要素のコレクションを含みます。 |
| [getSnapExtensions()](#getSnapExtensions--) | アクティブ ウィンドウに対して特定のスナップ拡張設定が有効か無効かを指定します。 |
| [getSnapSettings()](#getSnapSettings--) | ウィンドウでスナップが有効なときにシェイプがスナップするオブジェクトを指定します。 |
| [getStencilGroup()](#getStencilGroup--) | ウィンドウが所属する結合されたステンシル ウィンドウのグループを指定します。 |
| [getStencilGroupPos()](#getStencilGroupPos--) | ウィンドウ内のグループ内でステンシルの相対位置を指定する整数を含みます。 |
| [getTabSplitterPos()](#getTabSplitterPos--) | 図面ウィンドウのページ タブ コントロールの幅を指定します（図面ウィンドウ全体の幅に対する割合として）。 |
| [getViewCenterX()](#getViewCenterX--) | オプションの double。 |
| [getViewCenterY()](#getViewCenterY--) | オプションの double。 |
| [getViewScale()](#getViewScale--) | オプションの double。 |
| [getWindowHeight()](#getWindowHeight--) | ウィンドウ矩形の高さ。 |
| [getWindowLeft()](#getWindowLeft--) | ウィンドウ矩形の左座標。 |
| [getWindowState()](#getWindowState--) | この属性は以下の値の合計になる場合があります。 |
| [getWindowTop()](#getWindowTop--) | ウィンドウ矩形の上座標。 |
| [getWindowType()](#getWindowType--) | 列挙値で、次のいずれかになる可能性があります: Drawing、Sheet、Stencil、または Icon。WindowType='Stencil' の Window 要素は、親の図面ウィンドウ (WindowType='Drawing') の後、他の図面ウィンドウ要素の前に出現しなければなりません。 |
| [getWindowWidth()](#getWindowWidth--) | ウィンドウ矩形の幅。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | このプロパティの説明については、[getContainer()](../../com.aspose.diagram/window\\#getContainer--) を参照してください。 |
| [setContainerType(int value)](#setContainerType-int-) | このプロパティの説明については、[getContainerType()](../../com.aspose.diagram/window\\#getContainerType--) を参照してください。 |
| [setDocument(String value)](#setDocument-java.lang.String-) | このプロパティの説明については、[getDocument()](../../com.aspose.diagram/window\#getDocument--) を参照してください |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | このプロパティの説明については、[getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) を参照してください |
| [setGlueSettings(int value)](#setGlueSettings-int-) | このプロパティの説明については、[getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) を参照してください |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/window\#getID--) を参照してください |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | このプロパティの説明については、[getMaster()](../../com.aspose.diagram/window\#getMaster--) を参照してください |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | このプロパティの説明については、[getPage()](../../com.aspose.diagram/window\#getPage--) を参照してください |
| [setParentWindow(int value)](#setParentWindow-int-) | このプロパティの説明については、[getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) を参照してください |
| [setReadOnly(int value)](#setReadOnly-int-) | このプロパティの説明については、[getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) を参照してください |
| [setSheet(int value)](#setSheet-int-) | このプロパティの説明については、[getSheet()](../../com.aspose.diagram/window\#getSheet--) を参照してください |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | このプロパティの説明については、[getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) を参照してください |
| [setShowGrid(int value)](#setShowGrid-int-) | このプロパティの説明については、[getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) を参照してください |
| [setShowGuides(int value)](#setShowGuides-int-) | このプロパティの説明については、[getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) を参照してください |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | このプロパティの説明については、[getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) を参照してください |
| [setShowRulers(int value)](#setShowRulers-int-) | このプロパティの説明については、[getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) を参照してください |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | このプロパティの説明については、[getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) を参照してください |
| [setSnapSettings(int value)](#setSnapSettings-int-) | このプロパティの説明については、[getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) を参照してください |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | このプロパティの説明については、[getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) を参照してください |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | このプロパティの説明については、[getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) を参照してください |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | このプロパティの説明については、[getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) を参照してください |
| [setViewCenterX(double value)](#setViewCenterX-double-) | このプロパティの説明については、[getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) を参照してください |
| [setViewCenterY(double value)](#setViewCenterY-double-) | このプロパティの説明については、[getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) を参照してください |
| [setViewScale(double value)](#setViewScale-double-) | このプロパティの説明については、[getViewScale()](../../com.aspose.diagram/window\#getViewScale--) を参照してください |
| [setWindowHeight(long value)](#setWindowHeight-long-) | このプロパティの説明については、[getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) を参照してください |
| [setWindowLeft(int value)](#setWindowLeft-int-) | このプロパティの説明については、[getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) を参照してください |
| [setWindowState(int value)](#setWindowState-int-) | このプロパティの説明については、[getWindowState()](../../com.aspose.diagram/window\#getWindowState--) を参照してください |
| [setWindowTop(int value)](#setWindowTop-int-) | このプロパティの説明については、[getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)をご覧ください。 |
| [setWindowType(int value)](#setWindowType-int-) | このプロパティの説明については、[getWindowType()](../../com.aspose.diagram/window\#getWindowType--)をご覧ください。 |
| [setWindowWidth(long value)](#setWindowWidth-long-) | このプロパティの説明については、[getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)をご覧ください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


コンストラクタ。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


コンテナの ID: Page、Sheet、または Master。ContainerType が指定されている場合にのみ関連し、必要です。

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


このウィンドウに表示されるドキュメントのファイルパス。WindowType が Stencil と指定されているウィンドウに関連する属性です。

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


ドキュメントまたはウィンドウに対して動的グリッド機能が有効かどうかを指定します。

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


ドキュメントで接着が有効な場合に、シェイプが接着するオブジェクトを指定します。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


要素の親要素内における一意の ID。

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


このウィンドウがマスターを表示している場合のマスター ID。

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


このウィンドウがページを表示している場合のページ ID。WindowType が Drawing、かつ ContainerType が Page と指定されている場合にのみ関連します。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


このステンシルウィンドウが含まれるウィンドウの ID。WindowType が Stencil と指定されている場合にのみ関連します。

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


このステンシルがドキュメント ステンシルでない場合の読み取り専用フラグ。

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


コンテナ内のシートの ID。Container が Sheet と指定されている場合にのみ関連します。

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


ウィンドウに接続ポイントを表示するかどうかを指定します。

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


図面ウィンドウにグリッドを表示するかどうかを指定します。

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


図面ウィンドウにガイドを表示するかどうかを指定します。

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


ウィンドウに改ページ記号を表示するかどうかを指定します。

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


図面ウィンドウに定規を表示するかどうかを指定します。

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


SnapAngle 要素のコレクションを含みます。

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


アクティブウィンドウに対して、特定のスナップ拡張設定が有効か無効かを指定します。値は以下の表の値の合計になる場合があります。

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


ウィンドウでスナップが有効なときに、シェイプがスナップする対象オブジェクトを指定します。値は以下の表の値の合計になる場合があります。

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


ウィンドウが所属する結合されたステンシルウィンドウのグループを指定します。この属性は、Window 要素の WindowType 属性が Stencil に設定され、かつステンシルウィンドウが結合されたステンシルウィンドウのグループの一部である場合にのみ関連します。同じ結合グループに属するすべてのステンシルウィンドウは、同じ StencilGroup 要素値を持ちます。

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


ウィンドウ内のグループ内でステンシルの相対位置を指定する整数を含みます。

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


図面ウィンドウのページ タブ コントロールの幅を指定します（図面ウィンドウ全体の幅に対する割合として）。

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


オプションの double。

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


オプションの double。

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


オプションの double。

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


ウィンドウ矩形の高さ。

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


ウィンドウ矩形の左座標。

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


この属性は以下の値の合計になる場合があります。

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


ウィンドウ矩形の上座標。

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


列挙値で、次のいずれかになる可能性があります: Drawing、Sheet、Stencil、または Icon。WindowType='Stencil' の Window 要素は、親の図面ウィンドウ (WindowType='Drawing') の後、他の図面ウィンドウ要素の前に出現しなければなりません。

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


ウィンドウ矩形の幅。

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


このプロパティの説明については、[getContainer()](../../com.aspose.diagram/window\\#getContainer--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


このプロパティの説明については、[getContainerType()](../../com.aspose.diagram/window\\#getContainerType--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


このプロパティの説明については、[getDocument()](../../com.aspose.diagram/window\#getDocument--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


このプロパティの説明については、[getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


このプロパティの説明については、[getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/window\#getID--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


このプロパティの説明については、[getMaster()](../../com.aspose.diagram/window\#getMaster--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


このプロパティの説明については、[getPage()](../../com.aspose.diagram/window\#getPage--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


このプロパティの説明については、[getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


このプロパティの説明については、[getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


このプロパティの説明については、[getSheet()](../../com.aspose.diagram/window\#getSheet--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


このプロパティの説明については、[getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


このプロパティの説明については、[getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


このプロパティの説明については、[getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


このプロパティの説明については、[getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


このプロパティの説明については、[getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


このプロパティの説明については、[getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


このプロパティの説明については、[getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


このプロパティの説明については、[getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


このプロパティの説明については、[getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


このプロパティの説明については、[getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


このプロパティの説明については、[getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


このプロパティの説明については、[getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


このプロパティの説明については、[getViewScale()](../../com.aspose.diagram/window\#getViewScale--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


このプロパティの説明については、[getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


このプロパティの説明については、[getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


このプロパティの説明については、[getWindowState()](../../com.aspose.diagram/window\#getWindowState--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


このプロパティの説明については、[getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


このプロパティの説明については、[getWindowType()](../../com.aspose.diagram/window\#getWindowType--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


このプロパティの説明については、[getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

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

