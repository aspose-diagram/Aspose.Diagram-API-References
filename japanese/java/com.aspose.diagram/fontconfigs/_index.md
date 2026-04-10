---
title: FontConfigs
second_title: Aspose.Diagram for Java API リファレンス
description: フォント設定を指定します。
type: docs
weight: 160
url: /ja/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

フォント設定を指定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | デフォルトのフォント名。 |
| [getFontSources()](#getFontSources--) | ソースのリストを含む配列のコピーを取得します |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | 元のフォントが存在しない場合に使用されるフォント代替名を含む配列を返します。 |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | フォントが存在せず、そのフォントの代替が設定されていない場合に、システムフォント代替を優先するかどうかを示します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | このプロパティの説明については、[getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) を参照してください |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | フォントフォルダーを設定します |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | フォントフォルダーを設定します |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | フォントソースを設定します。 |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | 指定された元フォント名のフォント代替名。 |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | このプロパティの説明については、[getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) を参照してください |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontConfigs() {#FontConfigs--}
```
public FontConfigs()
```


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
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


デフォルトのフォント名。

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


ソースのリストを含む配列のコピーを取得します

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


元のフォントが存在しない場合に使用されるフォント代替名を含む配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - 元のフォントが存在しない場合に使用されるフォント代替名の配列。
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


フォントが存在せず、そのフォントの代替が設定されていない場合に、システムフォント代替を最初に使用するかどうかを示します。例: Ubuntu では、"Arial" フォントは通常 "Liberation Sans" に置き換えられます。デフォルト値は false です。

**Returns:**
boolean
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




### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String value)
```


このプロパティの説明については、[getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


フォントフォルダーを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFolder | java.lang.String | TrueType フォントを含むフォルダー。 |
| 再帰的 | boolean | サブフォルダーをスキャンするかどうかを決定します。 |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


フォントフォルダーを設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFolders | java.lang.String[] | TrueType フォントを含むフォルダー群。 |
| 再帰的 | boolean | サブフォルダーをスキャンするかどうかを決定します。 |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


フォントソースを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | TrueType フォントを含むソースの配列。 |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


指定された元フォント名のフォント代替名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| originalFontName | java.lang.String | 元のフォント名。 |
| substituteFontNames | java.lang.String[] | 元のフォントが存在しない場合に使用されるフォント代替名のリスト。 |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


このプロパティの説明については、[getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

