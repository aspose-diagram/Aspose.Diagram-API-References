---
title: ImageActiveXControl
second_title: Aspose.Diagram for Java API リファレンス
description: 画像コントロールを表します。
type: docs
weight: 197
url: /ja/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

画像コントロールを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | 背景の OLE カラー。 |
| [getBorderOleColor()](#getBorderOleColor--) | 背景の OLE カラー。 |
| [getBorderStyle()](#getBorderStyle--) | コントロールで使用される境界線の種類。 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | コントロールのバイナリ データ。 |
| [getForeOleColor()](#getForeOleColor--) | 前景の OLE カラー。 |
| [getHeight()](#getHeight--) | ポイント単位のコントロールの高さ。 |
| [getIMEMode()](#getIMEMode--) | コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。 |
| [getMouseIcon()](#getMouseIcon--) | コントロールのマウスポインタとして表示するカスタムアイコンです。 |
| [getMousePointer()](#getMousePointer--) | コントロールのマウスポインタとして表示されるアイコンの種類です。 |
| [getPicture()](#getPicture--) | 画像のデータです。 |
| [getPictureAlignment()](#getPictureAlignment--) | フォームまたは画像内の画像の配置です。 |
| [getPictureSizeMode()](#getPictureSizeMode--) | 画像の表示方法です。 |
| [getSpecialEffect()](#getSpecialEffect--) | コントロールの特殊効果です。 |
| [getType()](#getType--) | ActiveX コントロールのタイプを取得します。 |
| [getWidth()](#getWidth--) | ポイント単位のコントロールの幅です。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。 |
| [isEnabled()](#isEnabled--) | コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。 |
| [isLocked()](#isLocked--) | コントロール内のデータが編集ロックされているかどうかを示します。 |
| [isTiled()](#isTiled--) | 画像が背景全体にタイル状に配置されるかどうかを示します。 |
| [isTransparent()](#isTransparent--) | コントロールが透明かどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\\#isAutoSize--) を参照してください。 |
| [setBackOleColor(int value)](#setBackOleColor-int-) | このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\\#getBorderOleColor--) を参照してください。 |
| [setBorderStyle(int value)](#setBorderStyle-int-) | このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\\#getBorderStyle--) を参照してください。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください |
| [setForeOleColor(int value)](#setForeOleColor-int-) | このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください |
| [setHeight(double value)](#setHeight-double-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください |
| [setIMEMode(int value)](#setIMEMode-int-) | このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください |
| [setLocked(boolean value)](#setLocked-boolean-) | このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください |
| [setMousePointer(int value)](#setMousePointer-int-) | このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください |
| [setPicture(byte[] value)](#setPicture-byte---) | このプロパティの説明については、[getPicture()](../../com.aspose.diagram/imageactivexcontrol\\#getPicture--) を参照してください。 |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | このプロパティの説明については、[getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) を参照してください。 |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | このプロパティの説明については、[getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) を参照してください。 |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) を参照してください。 |
| [setTiled(boolean value)](#setTiled-boolean-) | このプロパティの説明については、[isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) を参照してください。 |
| [setTransparent(boolean value)](#setTransparent-boolean-) | このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください |
| [setWidth(double value)](#setWidth-double-) | このプロパティの説明については、[getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) を参照してください |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


背景の OLE カラー。

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


背景の OLE カラー。

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


コントロールで使用される境界線の種類。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


コントロールのバイナリ データ。

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


前景の OLE カラーです。Image コントロールには適用されません。

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


ポイント単位のコントロールの高さ。

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


コントロールのマウスポインタとして表示するカスタムアイコンです。

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


コントロールのマウスポインタとして表示されるアイコンの種類です。

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


画像のデータです。

**Returns:**
byte[]
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


フォームまたは画像内の画像の配置です。

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


画像の表示方法です。

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


コントロールの特殊効果です。

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


ActiveX コントロールのタイプを取得します。

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


ポイント単位のコントロールの幅です。

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


コントロール内のデータが編集ロックされているかどうかを示します。

**Returns:**
boolean
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


画像が背景全体にタイル状に配置されるかどうかを示します。

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


コントロールが透明かどうかを示します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\\#isAutoSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\\#getBorderOleColor--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\\#getBorderStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


このプロパティの説明については、[getPicture()](../../com.aspose.diagram/imageactivexcontrol\\#getPicture--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


このプロパティの説明については、[getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


このプロパティの説明については、[getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


このプロパティの説明については、[isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


このプロパティの説明については、[getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

