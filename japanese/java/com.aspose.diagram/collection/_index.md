---
title: コレクション
second_title: Aspose.Diagram for Java API リファレンス
description: コレクションの基底クラスです。
type: docs
weight: 49
url: /ja/java/com.aspose.diagram/collection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Collection implements Iterable
```

コレクションの基底クラスです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Collection()](#Collection--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | コレクションに項目が存在するかどうかを確認します。 |
| [iterator()](#iterator--) | ジェネリックではないコレクションに対するシンプルな反復をサポートします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Collection() {#Collection--}
```
public Collection()
```


コンストラクタ。

### clear() {#clear--}
```
public void clear()
```


コレクションからすべての要素を削除します。

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
### getCount() {#getCount--}
```
public int getCount()
```


コレクションに実際に含まれる要素数を取得します。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


コレクションに項目が存在するかどうかを確認します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | 要素のインデックス。 |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


ジェネリックではないコレクションに対するシンプルな反復をサポートします。

**Returns:**
java.util.Iterator -
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

