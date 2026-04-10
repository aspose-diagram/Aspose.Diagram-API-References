---
title: 保護
second_title: Aspose.Diagram for Java API リファレンス
description: ロックはシェイプへの偶発的な変更を防止するのに役立ちますが、他の状況で Microsoft Visio が値をリセットすることは防げません。
type: docs
weight: 312
url: /ja/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

ロック機能はシェイプへの偶発的な変更を防止するのに役立ちますが、他の状況で Microsoft Visio が値をリセットすることは防げません。また、ShapeSheet ウィンドウで行われた変更からも保護されません。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getLockAspect()](#getLockAspect--) | 図形のアスペクト比がロックされているかどうかを指定します。 |
| [getLockBegin()](#getLockBegin--) | 1 次元図形の開始点が特定の位置にロックされているかどうかを指定します。 |
| [getLockCalcWH()](#getLockCalcWH--) | 図形の選択矩形がロックされているかどうかを指定します。これにより、頂点が編集されたり、Geom 要素内の要素タイプが変更されたりしても再計算されません。 |
| [getLockCrop()](#getLockCrop--) | Microsoft Visio の Crop ツールで切り取られないように、外部オブジェクトがロックされているかどうかを指定します。 |
| [getLockCustProp()](#getLockCustProp--) | ユーザーが「カスタム プロパティの定義」ダイアログ ボックスを使用して、ユーザー インターフェイス (UI) でカスタム プロパティを追加、削除、または変更できるかどうかを決定します。 |
| [getLockDelete()](#getLockDelete--) | 図形が削除されないようにロックされているかどうかを指定します。 |
| [getLockEnd()](#getLockEnd--) | 1 次元図形の終了点が特定の位置にロックされているかどうかを指定します。 |
| [getLockFormat()](#getLockFormat--) | 図形の書式設定がロックされていて変更できないかどうかを指定します。 |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | サブシェイプが、Visio ユーザー インターフェイスで親グループ シェイプに適用される書式設定の変更をブロックできるようにし、そうでなければ個々のグループ シェイプにカスケードされるのを防ぎます。 |
| [getLockGroup()](#getLockGroup--) | グループがロックされていて、グループ解除できないかどうかを指定します。 |
| [getLockHeight()](#getLockHeight--) | 図形の高さがロックされているかどうかを指定します。 |
| [getLockMoveX()](#getLockMoveX--) | 図形の水平位置がロックされていて、水平に移動できないかどうかを指定します。 |
| [getLockMoveY()](#getLockMoveY--) | 図形の垂直位置がロックされていて、垂直に移動できないかどうかを指定します。 |
| [getLockRotate()](#getLockRotate--) | Microsoft Visio の回転ツールや「左に回転」または「右に回転」コマンドで図形が回転されないようにロックされているかどうかを指定します。 |
| [getLockSelect()](#getLockSelect--) | 図形の選択矩形がロックされているかどうかを指定します。これにより、頂点が編集されたり、Geom 要素内の要素タイプが変更されたりしても再計算されません。 |
| [getLockTextEdit()](#getLockTextEdit--) | 図形のテキストがロックされていて、編集できないかどうかを指定します。 |
| [getLockThemeColors()](#getLockThemeColors--) | ユーザーが図形にテーマカラーを適用することを防止します。 |
| [getLockThemeEffects()](#getLockThemeEffects--) | ユーザーがシェイプにテーマ効果を適用するのを防止します。 |
| [getLockVtxEdit()](#getLockVtxEdit--) | シェイプの頂点がロックされているかどうかを指定し、ツールバーのいかなるツールでも編集できないようにします。 |
| [getLockWidth()](#getLockWidth--) | シェイプの幅がロックされているかどうかを指定し、サイズ変更時に幅が変わらないようにします。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/protection\#getDel--) を参照してください。 |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


シェイプのアスペクト比がロックされているかどうかを指定します。ロックされている場合、シェイプは比例的にサイズ変更でき、単一の次元でサイズ変更することはできません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


1 次元図形の開始点が特定の位置にロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


図形の選択矩形がロックされているかどうかを指定します。これにより、頂点が編集されたり、Geom 要素内の要素タイプが変更されたりしても再計算されません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Microsoft Visio の Crop ツールで切り取られないように、外部オブジェクトがロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


ユーザーが「カスタム プロパティの定義」ダイアログ ボックスを使用して、ユーザー インターフェイス (UI) でカスタム プロパティを追加、削除、または変更できるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


図形が削除されないようにロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


1 次元図形の終了点が特定の位置にロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


シェイプの書式設定がロックされているかどうかを指定し、変更できないようにします。具体的には、この要素はテキスト、線、塗りの書式設定の変更や、シェイプが継承する Style 要素の変更から保護します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


サブシェイプが、Visio ユーザー インターフェイスで親グループ シェイプに適用される書式設定の変更をブロックできるようにし、そうでなければ個々のグループ シェイプにカスケードされるのを防ぎます。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


グループがロックされていて、グループ解除できないかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


シェイプの高さがロックされているかどうかを指定します。ロックされている場合、サイズ変更時に高さは変わりません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


図形の水平位置がロックされていて、水平に移動できないかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


図形の垂直位置がロックされていて、垂直に移動できないかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Microsoft Visio の回転ツールや「左に回転」または「右に回転」コマンドで図形が回転されないようにロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


図形の選択矩形がロックされているかどうかを指定します。これにより、頂点が編集されたり、Geom 要素内の要素タイプが変更されたりしても再計算されません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


シェイプのテキストがロックされているかどうかを指定し、編集できないようにします。ただし、テキストはスタイルを適用したり、テキスト ダイアログ ボックスのフォント タブの Style オプションを使用して書式設定することは可能です。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


ユーザーが図形にテーマカラーを適用することを防止します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


ユーザーがシェイプにテーマ効果を適用するのを防止します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


シェイプの頂点がロックされているかどうかを指定し、ツールバーのいかなるツールでも編集できないようにします。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


シェイプの幅がロックされているかどうかを指定し、サイズ変更時に幅が変わらないようにします。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/protection\#getDel--) を参照してください。

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

