---
title: Hyperlink
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプまたは描画ページと別の描画ページ、別のファイル、またはウェブサイト間で複数のジャンプを作成するための要素を含みます。
type: docs
weight: 193
url: /ja/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

シェイプまたは描画ページと別の描画ページ、別のファイル、または Web サイト間で複数のジャンプを作成するための要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | ジャンプ先の URL アドレス、DOS ファイル名、または UNC パスを指定します。 |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | シェイプまたはページのデフォルトハイパーリンクを指定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDescription()](#getDescription--) | Description 要素はハイパーリンクを説明するテキスト文字列を含みます。 |
| [getExtraInfo()](#getExtraInfo--) | URL の解決に使用される情報（画像マップの座標など）を含みます。 |
| [getFrame()](#getFrame--) | Microsoft Visio がコンテナ アプリケーションでアクティブ ドキュメントとして開かれているときにターゲットとするフレーム名を含みます。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getInvisible()](#getInvisible--) | Invisible 要素は、シェイプまたはページのショートカット メニューにハイパーリンクが表示されるかどうかを示します。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getNewWindow()](#getNewWindow--) | ハイパーリンクでウェブページや別の Visio ドキュメントを開く際に、Microsoft Visio が新しい場所にウィンドウを開くかどうかを指定します。 |
| [getSortKey()](#getSortKey--) | Invisible 要素は、シェイプまたはページのショートカット メニューにハイパーリンクが表示されるかどうかを示します。 |
| [getSubAddress()](#getSubAddress--) | リンク先のドキュメント内の位置を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/hyperlink\#getDel--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/hyperlink\#getID--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/hyperlink\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
```


コンストラクタ。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


このインスタンスのディープコピーを作成します。

**Returns:**
java.lang.Object -
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


ジャンプ先の URL アドレス、DOS ファイル名、または UNC パスを指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


シェイプまたはページのデフォルトハイパーリンクを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Description 要素はハイパーリンクを説明するテキスト文字列を含みます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


URL の解決に使用される情報（画像マップの座標など）を含みます。例えば、x=41 y=7 は画像マップの座標を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Microsoft Visio がコンテナ アプリケーションでアクティブ ドキュメントとして開かれているときにターゲットとするフレーム名を含みます。デフォルトは空文字列です。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


要素の親要素内における一意の ID。

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 要素は、シェイプまたはページのショートカット メニューにハイパーリンクが表示されるかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


ハイパーリンクでウェブページや別の Visio ドキュメントを開く際に、Microsoft Visio が新しい場所にウィンドウを開くかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Invisible 要素は、シェイプまたはページのショートカット メニューにハイパーリンクが表示されるかどうかを示します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


リンク先のドキュメント内の位置を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/hyperlink\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/hyperlink\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/hyperlink\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

