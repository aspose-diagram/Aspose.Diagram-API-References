---
title: CommandButtonActiveXControl
second_title: Aspose.Diagram for Java API リファレンス
description: コマンドボタンを表します。
type: docs
weight: 56
url: /ja/java/com.aspose.diagram/commandbuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class CommandButtonActiveXControl extends ActiveXControl
```

コマンドボタンを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | コントロールのアクセラレータキーです。 |
| [getBackOleColor()](#getBackOleColor--) | 背景の OLE カラー。 |
| [getCaption()](#getCaption--) | コントロール上に表示される説明テキストです。 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | コントロールのバイナリ データ。 |
| [getForeOleColor()](#getForeOleColor--) | 前景の OLE カラー。 |
| [getHeight()](#getHeight--) | ポイント単位のコントロールの高さ。 |
| [getIMEMode()](#getIMEMode--) | コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。 |
| [getMouseIcon()](#getMouseIcon--) | コントロールのマウスポインタとして表示するカスタムアイコンです。 |
| [getMousePointer()](#getMousePointer--) | コントロールのマウスポインタとして表示されるアイコンの種類です。 |
| [getPicture()](#getPicture--) | 画像のデータです。 |
| [getPicturePosition()](#getPicturePosition--) | コントロールのキャプションに対する画像の位置。 |
| [getTakeFocusOnClick()](#getTakeFocusOnClick--) | コントロールがクリックされたときにフォーカスを取得するかどうかを示します。 |
| [getType()](#getType--) | ActiveX コントロールのタイプを取得します。 |
| [getWidth()](#getWidth--) | ポイント単位のコントロールの幅です。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。 |
| [isEnabled()](#isEnabled--) | コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。 |
| [isLocked()](#isLocked--) | コントロール内のデータが編集ロックされているかどうかを示します。 |
| [isTransparent()](#isTransparent--) | コントロールが透明かどうかを示します。 |
| [isWordWrapped()](#isWordWrapped--) | コントロールの内容が行末で自動的に折り返されるかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | このプロパティの説明については、[getAccelerator()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getAccelerator--)をご覧ください。 |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください |
| [setBackOleColor(int value)](#setBackOleColor-int-) | このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください |
| [setCaption(String value)](#setCaption-java.lang.String-) | このプロパティの説明については、[getCaption()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getCaption--)をご覧ください。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください |
| [setForeOleColor(int value)](#setForeOleColor-int-) | このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください |
| [setHeight(double value)](#setHeight-double-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください |
| [setIMEMode(int value)](#setIMEMode-int-) | このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください |
| [setLocked(boolean value)](#setLocked-boolean-) | このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください |
| [setMousePointer(int value)](#setMousePointer-int-) | このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください |
| [setPicture(byte[] value)](#setPicture-byte---) | このプロパティの説明については、[getPicture()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicture--)をご覧ください。 |
| [setPicturePosition(int value)](#setPicturePosition-int-) | このプロパティの説明については、[getPicturePosition()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicturePosition--)をご覧ください。 |
| [setTakeFocusOnClick(boolean value)](#setTakeFocusOnClick-boolean-) | このプロパティの説明については、[getTakeFocusOnClick()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getTakeFocusOnClick--)をご覧ください。 |
| [setTransparent(boolean value)](#setTransparent-boolean-) | このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください |
| [setWidth(double value)](#setWidth-double-) | このプロパティの説明については、[getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) を参照してください |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | このプロパティの説明については、[isWordWrapped()](../../com.aspose.diagram/commandbuttonactivexcontrol\#isWordWrapped--)をご覧ください。 |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


コントロールのアクセラレータキーです。

**Returns:**
char
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


背景の OLE カラー。

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


コントロール上に表示される説明テキストです。

**Returns:**
java.lang.String
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
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


コントロールのキャプションに対する画像の位置。

**Returns:**
int
### getTakeFocusOnClick() {#getTakeFocusOnClick--}
```
public boolean getTakeFocusOnClick()
```


コントロールがクリックされたときにフォーカスを取得するかどうかを示します。

**Returns:**
boolean
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
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


コントロールが透明かどうかを示します。

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


コントロールの内容が行末で自動的に折り返されるかどうかを示します。

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




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


このプロパティの説明については、[getAccelerator()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getAccelerator--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | char |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください

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

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


このプロパティの説明については、[getCaption()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getCaption--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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


このプロパティの説明については、[getPicture()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicture--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


このプロパティの説明については、[getPicturePosition()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicturePosition--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTakeFocusOnClick(boolean value) {#setTakeFocusOnClick-boolean-}
```
public void setTakeFocusOnClick(boolean value)
```


このプロパティの説明については、[getTakeFocusOnClick()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getTakeFocusOnClick--)をご覧ください。

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

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


このプロパティの説明については、[isWordWrapped()](../../com.aspose.diagram/commandbuttonactivexcontrol\#isWordWrapped--)をご覧ください。

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

