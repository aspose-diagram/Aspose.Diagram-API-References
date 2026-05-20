---
title: StreamProviderOptions
second_title: Aspose.Diagram for Java API リファレンス
description: ストリーム オプションを表します。
type: docs
weight: 390
url: /ja/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

ストリーム オプションを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | 参照されたソースのために生成された HTML ファイルに保存されるデフォルトのパス（URL）。 |
| [getStream()](#getStream--) | 保存されたデータを書き込む出力ストリームを取得/設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | 参照されたソースのために生成された HTML ファイルに保存されるユーザーカスタムパス（URL）。 |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | このプロパティの説明については、[getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


参照されたソースのために生成された HTML ファイルに保存されるデフォルトのパス（URL）。例えば、シートデータが xxx\_files/sheet001.htm に保存される場合、メイン HTML ファイルで使用される URL は "src=\"xxx\_files/sheet001.htm\"" のようになる必要があります。

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


保存されたデータを書き込む出力ストリームを取得/設定します。

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


参照されたソースのために生成された HTML ファイルに保存されるユーザーカスタムパス（URL）。ユーザーが定義しない場合は DefaultPath が使用されます。例えば、シートデータがユーザーによって d:/sheet001.htm に保存される場合、メイン HTML ファイルで使用される URL は "d:/sheet001.htm" もしくはメイン HTML ファイルからアクセス可能な他の有効な相対パスである必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


このプロパティの説明については、[getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.OutputStream |  |

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

