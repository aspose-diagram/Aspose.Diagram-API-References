---
title: DocumentSettings
second_title: Aspose.Diagram for Java API リファレンス
description: ドキュメント設定を指定する要素を含みます。
type: docs
weight: 126
url: /ja/java/com.aspose.diagram/documentsettings/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSettings
```

ドキュメント設定を指定する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachedToolbars()](#getAttachedToolbars--) | カスタムツールバーを表す、MIME（Multipurpose Internet Mail Extensions）エンコードされた Microsoft Visio ユーザーインターフェイス（VSU）ファイルです。 |
| [getClass()](#getClass--) |  |
| [getCustomMenusFile()](#getCustomMenusFile--) | ドキュメント用のカスタムメニューとアクセラレータを定義する Microsoft Visio ユーザーインターフェイス（.vsu）ファイルの名前を含みます。 |
| [getCustomToolbarsFile()](#getCustomToolbarsFile--) | ドキュメント用のカスタムツールバーとステータスバーを定義する Microsoft Visio ユーザーインターフェイス（.vsu）ファイルの名前を含みます。 |
| [getDefaultFillStyle()](#getDefaultFillStyle--) | StyleSheet 要素の ID を指定します。 |
| [getDefaultGuideStyle()](#getDefaultGuideStyle--) | StyleSheet 要素の ID を指定します。 |
| [getDefaultLineStyle()](#getDefaultLineStyle--) | StyleSheet 要素の ID を指定します。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | StyleSheet 要素の ID を指定します。 |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | ドキュメントまたはウィンドウに対して動的グリッド機能が有効かどうかを指定します。 |
| [getGlueSettings()](#getGlueSettings--) | ドキュメントで接着が有効な場合に、シェイプが接着するオブジェクトを指定します。 |
| [getProtectBkgnds()](#getProtectBkgnds--) | ユーザーが背景ページを削除または編集できないようにするかどうかを指定します。 |
| [getProtectMasters()](#getProtectMasters--) | ユーザーがマスターを作成、編集、または削除できないようにするかどうかを指定します。 |
| [getProtectShapes()](#getProtectShapes--) | ユーザーが LockSelect 要素が 1 に設定されているシェイプの選択を防止されているかどうかを指定します。 |
| [getProtectStyles()](#getProtectStyles--) | ユーザーがスタイルの作成または編集を防止されているかどうかを指定します。 |
| [getSnapAngles()](#getSnapAngles--) | SnapAngle 要素のコレクションを含みます。 |
| [getSnapExtensions()](#getSnapExtensions--) | アクティブ ウィンドウに対して特定のスナップ拡張設定が有効か無効かを指定します。 |
| [getSnapSettings()](#getSnapSettings--) | ウィンドウでスナップが有効なときにシェイプがスナップするオブジェクトを指定します。 |
| [getTopPage()](#getTopPage--) | Microsoft Visio でドキュメントが開かれたときに表示されるページの ID を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachedToolbars(byte[] value)](#setAttachedToolbars-byte---) | このプロパティの説明については、[getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--) を参照してください。 |
| [setCustomMenusFile(String value)](#setCustomMenusFile-java.lang.String-) | このプロパティの説明については、[getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--) を参照してください。 |
| [setCustomToolbarsFile(String value)](#setCustomToolbarsFile-java.lang.String-) | このプロパティの説明については、[getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--) を参照してください。 |
| [setDefaultFillStyle(int value)](#setDefaultFillStyle-int-) | このプロパティの説明については、[getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--) を参照してください。 |
| [setDefaultGuideStyle(int value)](#setDefaultGuideStyle-int-) | このプロパティの説明については、[getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--) を参照してください。 |
| [setDefaultLineStyle(int value)](#setDefaultLineStyle-int-) | このプロパティの説明については、[getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--) を参照してください。 |
| [setDefaultTextStyle(int value)](#setDefaultTextStyle-int-) | このプロパティの説明については、[getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--) を参照してください。 |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | このプロパティの説明については、[getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--) を参照してください。 |
| [setGlueSettings(int value)](#setGlueSettings-int-) | このプロパティの説明については、[getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--) を参照してください。 |
| [setProtectBkgnds(int value)](#setProtectBkgnds-int-) | このプロパティの説明については、[getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--) を参照してください。 |
| [setProtectMasters(int value)](#setProtectMasters-int-) | このプロパティの説明については、[getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--) を参照してください。 |
| [setProtectShapes(int value)](#setProtectShapes-int-) | このプロパティの説明については、[getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--) を参照してください。 |
| [setProtectStyles(int value)](#setProtectStyles-int-) | このプロパティの説明については、[getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--) を参照してください。 |
| [setSnapAngles(FloatPointNumCollection value)](#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-) | このプロパティの説明については、[getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--) を参照してください。 |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | このプロパティの説明については、[getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--) を参照してください。 |
| [setSnapSettings(int value)](#setSnapSettings-int-) | このプロパティの説明については、[getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--) を参照してください。 |
| [setTopPage(int value)](#setTopPage-int-) | このプロパティの説明については、[getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--) を参照してください。 |
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
### getAttachedToolbars() {#getAttachedToolbars--}
```
public byte[] getAttachedToolbars()
```


カスタムツールバーを表す、MIME（Multipurpose Internet Mail Extensions）エンコードされた Microsoft Visio ユーザーインターフェイス（VSU）ファイルです。

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMenusFile() {#getCustomMenusFile--}
```
public String getCustomMenusFile()
```


ドキュメント用のカスタムメニューとアクセラレータを定義する Microsoft Visio ユーザーインターフェイス（.vsu）ファイルの名前を含みます。

**Returns:**
java.lang.String
### getCustomToolbarsFile() {#getCustomToolbarsFile--}
```
public String getCustomToolbarsFile()
```


ドキュメント用のカスタムツールバーとステータスバーを定義する Microsoft Visio ユーザーインターフェイス（.vsu）ファイルの名前を含みます。

**Returns:**
java.lang.String
### getDefaultFillStyle() {#getDefaultFillStyle--}
```
public int getDefaultFillStyle()
```


StyleSheet 要素の ID を指定します。次にユーザーが描画ツールを使用してシェイプを作成するとき、そのシェイプは指定された StyleSheet 要素から塗りつぶしスタイルを継承します。

**Returns:**
int
### getDefaultGuideStyle() {#getDefaultGuideStyle--}
```
public int getDefaultGuideStyle()
```


StyleSheet 要素の ID を指定します。次にユーザーがガイドを作成するとき、そのガイドは指定された StyleSheet 要素からガイドスタイルを継承します。

**Returns:**
int
### getDefaultLineStyle() {#getDefaultLineStyle--}
```
public int getDefaultLineStyle()
```


StyleSheet 要素の ID を指定します。次にユーザーが描画ツールを使用してシェイプを作成するとき、そのシェイプは指定された StyleSheet 要素から線スタイルを継承します。

**Returns:**
int
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public int getDefaultTextStyle()
```


StyleSheet 要素の ID を指定します。次にユーザーが描画ツールを使用してシェイプを作成するとき、そのシェイプは指定された StyleSheet 要素からテキストスタイルを継承します。

**Returns:**
int
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
### getProtectBkgnds() {#getProtectBkgnds--}
```
public int getProtectBkgnds()
```


ユーザーが背景ページを削除または編集できないようにするかどうかを指定します。

**Returns:**
int
### getProtectMasters() {#getProtectMasters--}
```
public int getProtectMasters()
```


ユーザーがマスターの作成、編集、削除を防止されているかどうかを指定します。この設定に関係なく、ユーザーはマスターのインスタンスを作成できます。

**Returns:**
int
### getProtectShapes() {#getProtectShapes--}
```
public int getProtectShapes()
```


ユーザーが LockSelect 要素が 1 に設定されているシェイプの選択を防止されているかどうかを指定します。

**Returns:**
int
### getProtectStyles() {#getProtectStyles--}
```
public int getProtectStyles()
```


ユーザーがスタイルの作成または編集を防止されているかどうかを指定します。ただし、この設定に関係なく、ユーザーはスタイルを適用できます。

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


アクティブ ウィンドウに対して特定のスナップ拡張設定が有効か無効かを指定します。

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


ウィンドウでスナップが有効なときにシェイプがスナップするオブジェクトを指定します。

**Returns:**
int
### getTopPage() {#getTopPage--}
```
public int getTopPage()
```


Microsoft Visio でドキュメントが開かれたときに表示されるページの ID を指定します。

**Returns:**
int
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




### setAttachedToolbars(byte[] value) {#setAttachedToolbars-byte---}
```
public void setAttachedToolbars(byte[] value)
```


このプロパティの説明については、[getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setCustomMenusFile(String value) {#setCustomMenusFile-java.lang.String-}
```
public void setCustomMenusFile(String value)
```


このプロパティの説明については、[getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCustomToolbarsFile(String value) {#setCustomToolbarsFile-java.lang.String-}
```
public void setCustomToolbarsFile(String value)
```


このプロパティの説明については、[getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDefaultFillStyle(int value) {#setDefaultFillStyle-int-}
```
public void setDefaultFillStyle(int value)
```


このプロパティの説明については、[getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDefaultGuideStyle(int value) {#setDefaultGuideStyle-int-}
```
public void setDefaultGuideStyle(int value)
```


このプロパティの説明については、[getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDefaultLineStyle(int value) {#setDefaultLineStyle-int-}
```
public void setDefaultLineStyle(int value)
```


このプロパティの説明については、[getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDefaultTextStyle(int value) {#setDefaultTextStyle-int-}
```
public void setDefaultTextStyle(int value)
```


このプロパティの説明については、[getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


このプロパティの説明については、[getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


このプロパティの説明については、[getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setProtectBkgnds(int value) {#setProtectBkgnds-int-}
```
public void setProtectBkgnds(int value)
```


このプロパティの説明については、[getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setProtectMasters(int value) {#setProtectMasters-int-}
```
public void setProtectMasters(int value)
```


このプロパティの説明については、[getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setProtectShapes(int value) {#setProtectShapes-int-}
```
public void setProtectShapes(int value)
```


このプロパティの説明については、[getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setProtectStyles(int value) {#setProtectStyles-int-}
```
public void setProtectStyles(int value)
```


このプロパティの説明については、[getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSnapAngles(FloatPointNumCollection value) {#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-}
```
public void setSnapAngles(FloatPointNumCollection value)
```


このプロパティの説明については、[getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection) |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


このプロパティの説明については、[getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


このプロパティの説明については、[getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTopPage(int value) {#setTopPage-int-}
```
public void setTopPage(int value)
```


このプロパティの説明については、[getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--) を参照してください。

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

