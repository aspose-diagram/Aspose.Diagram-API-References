---
title: Master
second_title: Aspose.Diagram for Java API リファレンス
description: ドキュメントのマスターを定義する要素を含みます。
type: docs
weight: 240
url: /ja/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

ドキュメントの master を定義する要素を含みます。master とは、ステンシル上の形状で、図面作成時に繰り返し使用するものです。ステンシルから形状を図面ページへドラッグすると、その形状は master のインスタンスとなり、master のローカルコピーがドキュメントに含まれます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Master()](#Master--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | ステンシルウィンドウ内の master のテキストが左揃え、右揃え、または中央揃えかどうかを指定します。 |
| [getBaseID()](#getBaseID--) | ドキュメント間で master を識別する GUID（グローバル一意識別子）。 |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 図面内の 2 つの形状間の各接続について Connect 要素を含みます。 |
| [getHidden()](#getHidden--) | ユーザーインターフェイスで master が非表示かどうかを指定します。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getIcon()](#getIcon--) | ドキュメント内の Master または MasterShortcut 要素に対する MIME（Multipurpose Internet Mail Extensions）エンコードされたバイナリアイコン（.ico 形式）を指定します。 |
| [getIconSize()](#getIconSize--) | 要素のアイコンのサイズ。 |
| [getIconUpdate()](#getIconUpdate--) | アイコンが master 自体から自動的に生成されるかどうかを指定します。 |
| [getMatchByName()](#getMatchByName--) | MatchByName 属性は、master のインスタンスが図面ページにドロップされたときに、Microsoft Visio がドキュメントの master が既に存在するかどうかを判断する方法を決定します。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getPageSheet()](#getPageSheet--) | ページまたはマスター要素のページシートを定義する要素を含みます。 |
| [getPatternFlags()](#getPatternFlags--) | PatternFlags 属性は、マスターがカスタム パターンとして動作するかどうかを決定します。 |
| [getPrompt()](#getPrompt--) | ステータスバーとツールチップが要素に対してプロンプトを表示します。 |
| [getShapes()](#getShapes--) | Shape オブジェクトのコレクション。 |
| [getUniqueID()](#getUniqueID--) | ドキュメント内でマスターを識別する GUID。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | このプロパティの説明については、[getAlignName()](../../com.aspose.diagram/master\#getAlignName--) を参照してください。 |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | このプロパティの説明については、[getBaseID()](../../com.aspose.diagram/master\#getBaseID--) を参照してください。 |
| [setHidden(int value)](#setHidden-int-) | このプロパティの説明については、[getHidden()](../../com.aspose.diagram/master\#getHidden--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/master\#getID--) を参照してください。 |
| [setIcon(byte[] value)](#setIcon-byte---) | このプロパティの説明については、[getIcon()](../../com.aspose.diagram/master\#getIcon--) を参照してください。 |
| [setIconSize(int value)](#setIconSize-int-) | このプロパティの説明については、[getIconSize()](../../com.aspose.diagram/master\#getIconSize--) を参照してください。 |
| [setIconUpdate(int value)](#setIconUpdate-int-) | このプロパティの説明については、[getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) を参照してください。 |
| [setMatchByName(int value)](#setMatchByName-int-) | このプロパティの説明については、[getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/master\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/master\#getNameU--) を参照してください。 |
| [setPatternFlags(int value)](#setPatternFlags-int-) | このプロパティの説明については、[getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) を参照してください。 |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | このプロパティの説明については、[getPrompt()](../../com.aspose.diagram/master\#getPrompt--) を参照してください。 |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


コンストラクタ。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


このインスタンスのディープコピーを作成します。

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


ステンシルウィンドウ内の master のテキストが左揃え、右揃え、または中央揃えかどうかを指定します。

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


ドキュメント間で master を識別する GUID（グローバル一意識別子）。

**Returns:**
java.util.UUID
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
### getHidden() {#getHidden--}
```
public int getHidden()
```


ユーザーインターフェイスで master が非表示かどうかを指定します。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


要素の親要素内における一意の ID。

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


ドキュメント内の Master または MasterShortcut 要素に対する MIME（Multipurpose Internet Mail Extensions）エンコードされたバイナリアイコン（.ico 形式）を指定します。

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


要素のアイコンのサイズ。

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


アイコンが master 自体から自動的に生成されるかどうかを指定します。

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


MatchByName 属性は、Microsoft Visio が描画ページにマスターのインスタンスをドロップしたときに、ドキュメント マスターがすでに存在するかどうかを判断する方法を決定します。これにより、スタンドアロン ステンシル ファイルからインスタンスがドラッグされた場合でも、ドキュメント マスターへの変更がマスターの新しいインスタンスに適用されます。

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
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


PatternFlags 属性は、マスターがカスタム パターンとして動作するかどうかを決定します。

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


ステータスバーとツールチップが要素に対してプロンプトを表示します。

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape オブジェクトのコレクション。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


ドキュメント内でマスターを識別する GUID。

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


このプロパティの説明については、[getAlignName()](../../com.aspose.diagram/master\#getAlignName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


このプロパティの説明については、[getBaseID()](../../com.aspose.diagram/master\#getBaseID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


このプロパティの説明については、[getHidden()](../../com.aspose.diagram/master\#getHidden--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/master\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


このプロパティの説明については、[getIcon()](../../com.aspose.diagram/master\#getIcon--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


このプロパティの説明については、[getIconSize()](../../com.aspose.diagram/master\#getIconSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


このプロパティの説明については、[getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


このプロパティの説明については、[getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/master\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/master\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


このプロパティの説明については、[getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


このプロパティの説明については、[getPrompt()](../../com.aspose.diagram/master\#getPrompt--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) を参照してください。

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

