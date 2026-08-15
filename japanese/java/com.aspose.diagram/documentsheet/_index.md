---
title: DocumentSheet
second_title: Aspose.Diagram for Java API リファレンス
description: ドキュメントの ShapeSheet 構造を指定します。
type: docs
weight: 127
url: /ja/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

ドキュメントの ShapeSheet 構造を指定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | ドキュメントページに挿入されたコメントに関する情報を含む要素が含まれています。 |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 要素のコレクションを含みます。 |
| [getConnections()](#getConnections--) | Connection 要素のコレクションを含みます。 |
| [getDocProps()](#getDocProps--) | ドキュメントのプレビュー品質、範囲、出力形式を制御する要素を含みます。 |
| [getFillStyle()](#getFillStyle--) | このスタイルが塗りつぶし書式を継承する StyleSheet 要素。 |
| [getForeign()](#getForeign--) | Microsoft Visio ドキュメントで使用される別のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。 |
| [getForeignData()](#getForeignData--) | Windows メタファイル、ビットマップ、または OLE データなどの画像データの MIME (Multipurpose Internet Mail Extensions) エンコード BLOB を含みます。 |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 要素のコレクションを含みます。 |
| [getLineStyle()](#getLineStyle--) | このスタイルが線書式を継承する StyleSheet 要素。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getProps()](#getProps--) | Prop 要素のコレクションを含みます。 |
| [getReviewers()](#getReviewers--) | 文書レビュアーに関する識別情報を含む要素を含みます。 |
| [getScratchs()](#getScratchs--) | Scratch 要素のコレクションを含みます。 |
| [getTextStyle()](#getTextStyle--) | このスタイルがテキスト書式を継承する StyleSheet 要素。 |
| [getUniqueID()](#getUniqueID--) | 形状を識別する GUID（グローバルに一意な識別子）です。 |
| [getUsers()](#getUsers--) | User 要素のコレクションを含みます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) を参照してください。 |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/documentsheet\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) を参照してください。 |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | このプロパティの説明については、[getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) を参照してください。 |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) を参照してください。 |
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
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


ドキュメントのプレビュー品質、範囲、出力形式を制御する要素を含みます。

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


このスタイルが塗りつぶし書式を継承する StyleSheet 要素。

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
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


このスタイルが線書式を継承する StyleSheet 要素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 要素のコレクションを含みます。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


文書レビュアーに関する識別情報を含む要素を含みます。

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 要素のコレクションを含みます。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


このスタイルがテキスト書式を継承する StyleSheet 要素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


形状を識別する GUID（グローバルに一意な識別子）です。

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User 要素のコレクションを含みます。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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


このプロパティの説明については、[getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


このプロパティの説明については、[getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/documentsheet\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


このプロパティの説明については、[getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


このプロパティの説明については、[getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) を参照してください。

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

