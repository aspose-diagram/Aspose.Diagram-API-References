---
title: TextBoxActiveXControl
second_title: Aspose.Diagram for Java API リファレンス
description: テキスト ボックス ActiveX コントロールを表します。
type: docs
weight: 401
url: /ja/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

テキスト ボックス ActiveX コントロールを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | 背景の OLE カラー。 |
| [getBorderOleColor()](#getBorderOleColor--) | 背景の OLE カラー。 |
| [getBorderStyle()](#getBorderStyle--) | コントロールで使用される境界線の種類。 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | コントロールのバイナリ データ。 |
| [getDropButtonStyle()](#getDropButtonStyle--) | ドロップボタンに表示されるシンボルを指定します。 |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | コントロールに入るときの選択動作を指定します。 |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | ENTER キーの動作を指定します。 |
| [getForeOleColor()](#getForeOleColor--) | 前景の OLE カラー。 |
| [getHeight()](#getHeight--) | ポイント単位のコントロールの高さ。 |
| [getHideSelection()](#getHideSelection--) | コントロールがフォーカスを持っていないときに、コントロール内の選択されたテキストがハイライト表示されるかどうかを示します。 |
| [getIMEMode()](#getIMEMode--) | コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。 |
| [getIntegralHeight()](#getIntegralHeight--) | コントロールが部分的な行を表示せず、完全な行のみを表示するかどうかを示します。 |
| [getMaxLength()](#getMaxLength--) | 最大文字数 |
| [getMouseIcon()](#getMouseIcon--) | コントロールのマウスポインタとして表示するカスタムアイコンです。 |
| [getMousePointer()](#getMousePointer--) | コントロールのマウスポインタとして表示されるアイコンの種類です。 |
| [getPasswordChar()](#getPasswordChar--) | 入力された文字の代わりに表示される文字。 |
| [getScrollBars()](#getScrollBars--) | コントロールに垂直スクロールバー、水平スクロールバー、両方、またはどちらもないかを示します。 |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | ドロップボタンに表示されるシンボルを指定します。 |
| [getSpecialEffect()](#getSpecialEffect--) | コントロールの特殊効果です。 |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | コントロールのテキストでタブ文字が許可されているかどうかを示します。 |
| [getText()](#getText--) | コントロールのテキスト。 |
| [getType()](#getType--) | ActiveX コントロールのタイプを取得します。 |
| [getWidth()](#getWidth--) | ポイント単位のコントロールの幅です。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。 |
| [isAutoTab()](#isAutoTab--) | ユーザーが最大文字数を入力したときに、フォーカスが自動的に次のコントロールへ移動するかどうかを示します。 |
| [isAutoWordSelected()](#isAutoWordSelected--) | 選択範囲を拡張する際に使用される基本単位を指定します。 |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | コントロールでドラッグ アンド ドロップが有効かどうかを示します。 |
| [isEditable()](#isEditable--) | ユーザーがコントロールに入力できるかどうかを示します。 |
| [isEnabled()](#isEnabled--) | コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。 |
| [isLocked()](#isLocked--) | コントロール内のデータが編集ロックされているかどうかを示します。 |
| [isMultiLine()](#isMultiLine--) | コントロールが複数行のテキストを表示できるかどうかを示します。 |
| [isTransparent()](#isTransparent--) | コントロールが透明かどうかを示します。 |
| [isWordWrapped()](#isWordWrapped--) | コントロールの内容が行末で自動的に折り返されるかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | このプロパティの説明については、[isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) を参照してください。 |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | このプロパティの説明については、[isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) を参照してください。 |
| [setBackOleColor(int value)](#setBackOleColor-int-) | このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) を参照してください。 |
| [setBorderStyle(int value)](#setBorderStyle-int-) | このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) を参照してください。 |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | このプロパティの説明については、[isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) を参照してください。 |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | このプロパティの説明については、[getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) を参照してください。 |
| [setEditable(boolean value)](#setEditable-boolean-) | このプロパティの説明については、[isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) を参照してください。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | このプロパティの説明については、[getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) を参照してください。 |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | このプロパティの説明については、[getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) を参照してください。 |
| [setForeOleColor(int value)](#setForeOleColor-int-) | このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください |
| [setHeight(double value)](#setHeight-double-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | このプロパティの説明については、[getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) を参照してください。 |
| [setIMEMode(int value)](#setIMEMode-int-) | このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | このプロパティの説明については、[getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) を参照してください。 |
| [setLocked(boolean value)](#setLocked-boolean-) | このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください |
| [setMaxLength(int value)](#setMaxLength-int-) | このプロパティの説明については、[getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) を参照してください。 |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください |
| [setMousePointer(int value)](#setMousePointer-int-) | このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | このプロパティの説明については、[isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) を参照してください。 |
| [setPasswordChar(char value)](#setPasswordChar-char-) | このプロパティの説明については、[getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) を参照してください。 |
| [setScrollBars(int value)](#setScrollBars-int-) | このプロパティの説明については、[getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) を参照してください。 |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | このプロパティの説明については、[getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) を参照してください。 |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) を参照してください。 |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | このプロパティの説明については、[getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) を参照してください。 |
| [setText(String value)](#setText-java.lang.String-) | このプロパティの説明については、[getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) を参照してください。 |
| [setTransparent(boolean value)](#setTransparent-boolean-) | このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください |
| [setWidth(double value)](#setWidth-double-) | このプロパティの説明については、[getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) を参照してください |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | このプロパティの説明については、[isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) を参照してください。 |
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
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


ドロップボタンに表示されるシンボルを指定します。

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


コントロールに入るときの選択動作を指定します。True の場合、選択は前回コントロールがアクティブだったときから変更されません。False の場合、コントロールに入るときにテキスト全体が選択されます。

**Returns:**
boolean
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


ENTER キーの動作を指定します。True の場合、ENTER を押すと新しい行が作成されます。False の場合、ENTER を押すとタブ順の次のオブジェクトにフォーカスが移動します。

**Returns:**
boolean
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


コントロールがフォーカスを持っていないときに、コントロール内の選択されたテキストがハイライト表示されるかどうかを示します。

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


コントロールが部分的な行を表示せず、完全な行のみを表示するかどうかを示します。

**Returns:**
boolean
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


最大文字数

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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


入力された文字の代わりに表示される文字。

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


コントロールに垂直スクロールバー、水平スクロールバー、両方、またはどちらもないかを示します。

**Returns:**
int
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


ドロップボタンに表示されるシンボルを指定します。

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


コントロールの特殊効果です。

**Returns:**
int
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


コントロールのテキストでタブ文字が許可されているかどうかを示します。

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


コントロールのテキスト。

**Returns:**
java.lang.String
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


ユーザーが最大文字数を入力したときに、フォーカスが自動的に次のコントロールへ移動するかどうかを示します。

**Returns:**
boolean
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


選択を拡張する際に使用される基本単位を指定します。True の場合、基本単位は単一文字です。false の場合、基本単位は単語全体です。

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


コントロールでドラッグ アンド ドロップが有効かどうかを示します。

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


ユーザーがコントロールに入力できるかどうかを示します。

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


コントロールが複数行のテキストを表示できるかどうかを示します。

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




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


このプロパティの説明については、[isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


このプロパティの説明については、[isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) を参照してください。

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


このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


このプロパティの説明については、[isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


このプロパティの説明については、[getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


このプロパティの説明については、[isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


このプロパティの説明については、[getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


このプロパティの説明については、[getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) を参照してください。

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


このプロパティの説明については、[getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


このプロパティの説明については、[getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


このプロパティの説明については、[getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


このプロパティの説明については、[isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


このプロパティの説明については、[getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


このプロパティの説明については、[getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


このプロパティの説明については、[getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


このプロパティの説明については、[getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


このプロパティの説明については、[getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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


このプロパティの説明については、[isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) を参照してください。

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

