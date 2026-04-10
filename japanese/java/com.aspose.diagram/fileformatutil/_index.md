---
title: FileFormatUtil
second_title: Aspose.Diagram for Java API リファレンス
description: ファイル形式列挙体を文字列またはファイル拡張子に変換し、逆変換するユーティリティ メソッドを提供します。
type: docs
weight: 152
url: /ja/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

ファイル形式列挙体を文字列またはファイル拡張子に変換し、逆変換するユーティリティ メソッドを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | ストリームに格納された Visio の形式に関する情報を検出し、返します。 |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | ファイルに格納された Visio の形式に関する情報を検出し、返します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


ストリームに格納された Visio の形式に関する情報を検出し、返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ストリーム |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


ファイルに格納された Visio の形式に関する情報を検出し、返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパス。 |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
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

