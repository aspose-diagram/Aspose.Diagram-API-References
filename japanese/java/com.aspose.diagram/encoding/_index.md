---
title: Encoding
second_title: Aspose.Diagram for Java API リファレンス
description: 文字エンコーディングを表します。
type: docs
weight: 143
url: /ja/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

文字エンコーディングを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | 指定された Encoding オブジェクトが現在のインスタンスと等しいかどうかを判断します。 |
| [equals(Object o)](#equals-java.lang.Object-) | 指定された Object が現在のインスタンスと等しいかどうかを判断します。 |
| [getASCII()](#getASCII--) | ASCII（7 ビット）文字セット用のエンコーディングを取得します。 |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | ビッグエンディアン バイト順序を使用した UTF-16 形式のエンコーディングを取得します。 |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | オペレーティングシステムの現在の ANSI コードページ用のエンコーディングを取得します。 |
| [getEncoding(int codePage)](#getEncoding-int-) | 指定されたコードページ識別子に関連付けられたエンコーディングを返します。 |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | 指定された charset 名に関連付けられたエンコーディングを返します。 |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | 指定された charset オブジェクトに関連付けられたエンコーディングを返します。 |
| [getUTF7()](#getUTF7--) | UTF-7 形式のエンコーディングを取得します。 |
| [getUTF8()](#getUTF8--) | UTF-8 形式のエンコーディングを取得します。 |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | UTF-8 識別子なしの UTF-8 形式のエンコーディングを取得します。 |
| [getUnicode()](#getUnicode--) | リトルエンディアン バイト順序を使用した UTF-16 形式のエンコーディングを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


指定された Encoding オブジェクトが現在のインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | 現在のインスタンスと比較する Encoding オブジェクトです。 |

**Returns:**
boolean - 値が現在のインスタンスと等しい場合は true、そうでない場合は false。
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


指定された Object が現在のインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object | 現在のインスタンスと比較するオブジェクト。 |

**Returns:**
boolean - 値が Encoding のインスタンスであり現在のインスタンスと等しい場合は true、そうでない場合は false。
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


ASCII（7 ビット）文字セット用のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


ビッグエンディアン バイト順序を使用した UTF-16 形式のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


オペレーティングシステムの現在の ANSI コードページ用のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


指定されたコードページ識別子に関連付けられたエンコーディングを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| codePage | int | 優先エンコーディングのコードページ識別子。-or- 0 はデフォルトエンコーディングを使用します。 |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


指定された charset 名に関連付けられたエンコーディングを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| charsetName | java.lang.String | 指定された文字セット名 |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


指定された charset オブジェクトに関連付けられたエンコーディングを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| charset | java.nio.charset.Charset | 指定された文字セットオブジェクト |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


UTF-7 形式のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


UTF-8 形式のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


UTF-8 識別子なしの UTF-8 形式のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


リトルエンディアン バイト順序を使用した UTF-16 形式のエンコーディングを取得します。

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

