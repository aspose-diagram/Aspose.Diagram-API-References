---
title: InterpolationMode
second_title: Aspose.Diagram for Java API リファレンス
description: InterpolationMode 列挙体は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。
type: docs
weight: 206
url: /ja/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

InterpolationMode 列挙体は、画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。
## Fields

| Field | 説明 |
| --- | --- |
| [BICUBIC](#BICUBIC) | バイキュービック補間を指定します。 |
| [BILINEAR](#BILINEAR) | 双一次補間を指定します。 |
| [DEFAULT](#DEFAULT) | デフォルトモードを指定します。 |
| [HIGH](#HIGH) | 高品質の補間を指定します。 |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | 高品質のバイキュービック補間を指定します。 |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | 高品質の双一次補間を指定します。 |
| [INVALID](#INVALID) | QualityMode 列挙体の Invalid 要素に相当します。 |
| [LOW](#LOW) | 低品質の補間を指定します。 |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | 最近傍補間を指定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


バイキュービック補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 25％ 未満に縮小する場合には適していません。

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


双一次補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 50％ 未満に縮小する場合には適していません。

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


デフォルトモードを指定します。

### HIGH {#HIGH}
```
public static final int HIGH
```


高品質の補間を指定します。

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


高品質のバイキュービック補間を指定します。高品質な縮小を保証するために事前フィルタリングが実行されます。このモードは最高品質の変換画像を生成します。

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


高品質の双一次補間を指定します。高品質な縮小を保証するために事前フィルタリングが実行されます。

### INVALID {#INVALID}
```
public static final int INVALID
```


QualityMode 列挙体の Invalid 要素に相当します。

### LOW {#LOW}
```
public static final int LOW
```


低品質の補間を指定します。

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


最近傍補間を指定します。

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

