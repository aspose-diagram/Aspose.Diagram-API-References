---
title: PageSheet
second_title: Aspose.Diagram for Java API リファレンス
description: ページまたはマスター要素のページシートを定義する要素を含みます。
type: docs
weight: 270
url: /ja/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

ページまたはマスター要素のページシートを定義する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | ソースオブジェクトから pagesheet をコピーします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Act 要素のコレクションを含みます。 |
| [getAnnotations()](#getAnnotations--) | ドキュメントページに挿入されたコメントに関する情報を含む要素が含まれています。 |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 要素のコレクションを含みます。 |
| [getConnections()](#getConnections--) | Connection 要素のコレクションを含みます。 |
| [getFillStyle()](#getFillStyle--) | PageSheet が塗りつぶし書式を継承する StyleSheet 要素。 |
| [getForeign()](#getForeign--) | Microsoft Visio ドキュメントで使用される別のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。 |
| [getForeignData()](#getForeignData--) | Windows メタファイル、ビットマップ、または OLE データなどの画像データの MIME (Multipurpose Internet Mail Extensions) エンコード BLOB を含みます。 |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 要素のコレクションを含みます。 |
| [getLayers()](#getLayers--) | Layer 要素のコレクションを含みます。 |
| [getLineStyle()](#getLineStyle--) | PageSheet が線書式を継承する StyleSheet 要素。 |
| [getPageLayout()](#getPageLayout--) | ページ上のすべての図形やコネクタの間隔、ページ上のすべてのコネクタの間隔、コネクタのルーティングスタイルなど、図形とコネクタのページレイアウト設定を制御する Diagram を含みます。 |
| [getPageProps()](#getPageProps--) | ページ幅、ページ高さ、スケールなどのページ属性を制御する Diagram を含みます。 |
| [getPrintProps()](#getPrintProps--) | 描画ページがプリンタページ上でどのようにフォーマット（表示）されるかを制御する要素を含みます。 |
| [getProps()](#getProps--) | Prop 要素のコレクションを含みます。 |
| [getRulerGrid()](#getRulerGrid--) | ページの定規とグリッドの設定を指定する要素を含みます。 |
| [getScratchs()](#getScratchs--) | Scratch 要素のコレクションを含みます。 |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef 要素のコレクションを含みます。 |
| [getTextStyle()](#getTextStyle--) | PageSheet がテキスト書式を継承する StyleSheet 要素。 |
| [getUniqueID()](#getUniqueID--) | 要素の GUID（グローバル一意識別子）。 |
| [getUsers()](#getUsers--) | User 要素のコレクションを含みます。 |
| [getXForm()](#getXForm--) | シェイプに関する一般的な位置情報を指定する要素を含みます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) を参照してください。 |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) を参照してください。 |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


ソースオブジェクトから pagesheet をコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act 要素のコレクションを含みます。

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


ドキュメントページに挿入されたコメントに関する情報を含む要素が含まれています。

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


PageSheet が塗りつぶし書式を継承する StyleSheet 要素。

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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink 要素のコレクションを含みます。

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Layer 要素のコレクションを含みます。

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


PageSheet が線書式を継承する StyleSheet 要素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


ページ上のすべての図形やコネクタの間隔、ページ上のすべてのコネクタの間隔、コネクタのルーティングスタイルなど、図形とコネクタのページレイアウト設定を制御する Diagram を含みます。

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


ページ幅、ページ高さ、スケールなどのページ属性を制御する Diagram を含みます。

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


描画ページがプリンタページ上でどのようにフォーマット（表示）されるかを制御する要素を含みます。

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 要素のコレクションを含みます。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


ページの定規とグリッドの設定を指定する要素を含みます。

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 要素のコレクションを含みます。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef 要素のコレクションを含みます。

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


PageSheet がテキスト書式を継承する StyleSheet 要素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


要素の GUID（グローバル一意識別子）。

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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

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

