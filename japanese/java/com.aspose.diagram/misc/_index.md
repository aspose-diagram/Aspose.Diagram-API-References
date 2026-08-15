---
title: Misc
second_title: Aspose.Diagram for Java API リファレンス
description: 選択のハイライトや表示を制御する要素など、シェイプとグループのさまざまな要素を含みます。
type: docs
weight: 247
url: /ja/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

選択ハイライトや表示を制御する要素など、シェイプやグループのさまざまな要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Microsoft Visio が生成したトリガー式を含みます。この式は、別のシェイプへの接続を維持するために 1 次元シェイプの開始点を移動させるかどうかを判断します。 |
| [getCalendar()](#getCalendar--) | カスタム プロパティ、テキスト フィールド、要素の数式に使用されるカレンダーを決定します。 |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | シェイプのコメントテキストを文字列形式で含みます。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDropOnPageScale()](#getDropOnPageScale--) | シェイプが描画ページにドロップされたときに拡大縮小される割合を決定します。 |
| [getDynFeedback()](#getDynFeedback--) | コネクタをドラッグするときにユーザーに提供されるビジュアルフィードバックのタイプを指定します。 |
| [getEndTrigger()](#getEndTrigger--) | Microsoft Visio が生成したトリガー式を含みます。 |
| [getGlueType()](#getGlueType--) | シェイプに接続するときに、動的（シェイプ間）グルーが許可されているかどうかを指定します。 |
| [getHideText()](#getHideText--) | シェイプのテキストを非表示にします。 |
| [getLangID()](#getLangID--) | セルの数式、テキスト、カスタムプロパティ、またはコメントが入力された言語のロケール ID (LCID) を示します。 |
| [getLocalizeMerge()](#getLocalizeMerge--) | シェイプがドキュメント間でコピーされる際に、ローカライズ（LangID 要素がリセットされるかどうか）が行われるかどうかを決定します。 |
| [getNoAlignBox()](#getNoAlignBox--) | シェイプが選択されたときに選択矩形を表示するかどうかを指定します。 |
| [getNoCtlHandles()](#getNoCtlHandles--) | シェイプが選択されたときにコントロールハンドルを表示するかどうかを指定します。 |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | ユーザーが操作する際にシェイプが動的にサイズ変更または回転するかどうかを指定します。 |
| [getNoObjHandles()](#getNoObjHandles--) | シェイプが選択されたときに選択ハンドルを表示するかどうかを指定します。 |
| [getNonPrinting()](#getNonPrinting--) | 選択されたシェイプを印刷できるかどうかを指定します。 |
| [getObjType()](#getObjType--) | Microsoft Visio を使用して描画ページ上にシェイプを配置する際、オブジェクトが配置可能かルーティング可能かを指定します。 |
| [getShapeKeywords()](#getShapeKeywords--) | カスタム マスター シェイプに割り当てられた検索キーワードを含みます。 |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | コントロールハンドルが移動するたびにシェイプの選択矩形を再計算するかどうかを指定します。 |
| [getWalkPreference()](#getWalkPreference--) | 形状が曖昧な位置に移動したとき、動的接着を使用して、1 次元形状の端点が接着された形状上の水平または垂直の接続点に移動するかどうかを指定します。 |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | シェイプをグループ上にドロップしてグループに追加できるかどうかを指定します。 |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | シェイプ置換操作中に、マスターシェイプの指定セルの値が置換されるシェイプの値（ローカル値を含む）を上書きするかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/misc\#getDel--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Microsoft Visio が生成したトリガー式を含みます。この式は、別のシェイプへの接続を維持するために 1 次元シェイプの開始点を移動させるかどうかを判断します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


カスタム プロパティ、テキスト フィールド、要素の数式に使用されるカレンダーを決定します。

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


シェイプのコメントテキストを文字列形式で含みます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


シェイプが描画ページにドロップされたときに拡大縮小される割合を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


コネクタをドラッグするときにユーザーに提供されるビジュアルフィードバックのタイプを指定します。

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Microsoft Visio が生成したトリガー式を含みます。このトリガー式は、別のシェイプへの接続を維持するために 1 次元シェイプの終点を移動させるかどうかを判断します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


シェイプに接続するときに、動的（シェイプ間）グルーが許可されているかどうかを指定します。

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


シェイプのテキストを非表示にします。テキストブロック内のテキストを表示したり、プロパティを編集したり、スタイルを適用したりできますが、HideText 要素を 0 に指定するまで変更は反映されません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


セルの数式、テキスト、カスタムプロパティ、またはコメントが入力された言語のロケール ID (LCID) を示します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


シェイプがドキュメント間でコピーされる際に、ローカライズ（LangID 要素がリセットされるかどうか）が行われるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


シェイプが選択されたときに選択矩形を表示するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


シェイプが選択されたときにコントロールハンドルを表示するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


ユーザーが操作する際にシェイプが動的にサイズ変更または回転するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


シェイプが選択されたときに選択ハンドルを表示するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


選択されたシェイプを印刷できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Microsoft Visio を使用して描画ページ上にシェイプを配置する際、オブジェクトが配置可能かルーティング可能かを指定します。

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


カスタム マスター シェイプに割り当てられた検索キーワードを含みます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


コントロールハンドルが移動するたびにシェイプの選択矩形を再計算するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


形状が曖昧な位置に移動したとき、動的接着を使用して、1 次元形状の端点が接着された形状上の水平または垂直の接続点に移動するかどうかを指定します。

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


シェイプをグループ上にドロップしてグループに追加できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


シェイプ置換操作中に、マスターシェイプの指定セルの値が置換されるシェイプの値（ローカル値を含む）を上書きするかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/misc\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

