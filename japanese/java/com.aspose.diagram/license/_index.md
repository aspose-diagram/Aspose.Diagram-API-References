---
title: ライセンス
second_title: Aspose.Diagram for Java API リファレンス
description: コンポーネントのライセンスを取得するためのメソッドを提供します。
type: docs
weight: 219
url: /ja/java/com.aspose.diagram/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントのライセンスを取得するためのメソッドを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


このクラスの新しいインスタンスを初期化します。

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


コンポーネントにライセンスを付与します。

このメソッドを使用して、ストリームからライセンスをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ライセンスを含むストリームです。 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


コンポーネントにライセンスを付与します。

次の場所でライセンスを検索します：

1. 明示的なパス。

2. コンポーネント アセンブリのフォルダー。

3. クライアントの呼び出しアセンブリのフォルダー。

4. エントリ アセンブリのフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

2. コンポーネント JAR ファイルのフォルダー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseName | java.lang.String |  |

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

