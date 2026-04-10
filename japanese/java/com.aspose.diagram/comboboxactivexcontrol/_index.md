---
title: ComboBoxActiveXControl
second_title: Aspose.Diagram for Java API リファレンス
description: ComboBox ActiveX コントロールを表します。
type: docs
weight: 55
url: /ja/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

ComboBox ActiveX コントロールを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | 背景の OLE カラー。 |
| [getBorderOleColor()](#getBorderOleColor--) | 背景の OLE カラー。 |
| [getBorderStyle()](#getBorderStyle--) | コントロールで使用される境界線の種類。 |
| [getBoundColumn()](#getBoundColumn--) | ComboBox または ListBox の Value プロパティが MultiSelect プロパティの値 (fmMultiSelectSingle) のときにどのように決定されるかを表します。 |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | ComboBox または ListBox に表示する列数を表します。 |
| [getColumnWidths()](#getColumnWidths--) | 列の幅。 |
| [getData()](#getData--) | コントロールのバイナリ データ。 |
| [getDropButtonStyle()](#getDropButtonStyle--) | ドロップボタンに表示されるシンボルを指定します。 |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | コントロールに入るときの選択動作を指定します。 |
| [getForeOleColor()](#getForeOleColor--) | 前景の OLE カラー。 |
| [getHeight()](#getHeight--) | ポイント単位のコントロールの高さ。 |
| [getHideSelection()](#getHideSelection--) | コントロールがフォーカスを持っていないときに、コントロール内の選択されたテキストがハイライト表示されるかどうかを示します。 |
| [getIMEMode()](#getIMEMode--) | コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。 |
| [getListRows()](#getListRows--) | リストに表示する最大行数を表します。 |
| [getListStyle()](#getListStyle--) | 視覚的な外観です。 |
| [getListWidth()](#getListWidth--) | ポイント単位の幅です。 |
| [getMatchEntry()](#getMatchEntry--) | ユーザーが入力する際に ListBox または ComboBox がリストを検索する方法を示します。 |
| [getMaxLength()](#getMaxLength--) | 最大文字数 |
| [getMouseIcon()](#getMouseIcon--) | コントロールのマウスポインタとして表示するカスタムアイコンです。 |
| [getMousePointer()](#getMousePointer--) | コントロールのマウスポインタとして表示されるアイコンの種類です。 |
| [getSelectionMargin()](#getSelectionMargin--) | ユーザーがテキストの左側領域をクリックしてテキスト行を選択できるかどうかを示します。 |
| [getShowColumnHeads()](#getShowColumnHeads--) | 列見出しが表示されるかどうかを示します。 |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | ドロップボタンに表示されるシンボルを指定します。 |
| [getSpecialEffect()](#getSpecialEffect--) | コントロールの特殊効果です。 |
| [getTextColumn()](#getTextColumn--) | ユーザーに表示する ComboBox または ListBox の列を表します。 |
| [getType()](#getType--) | ActiveX コントロールのタイプを取得します。 |
| [getValue()](#getValue--) | コントロールの値です。 |
| [getWidth()](#getWidth--) | ポイント単位のコントロールの幅です。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。 |
| [isAutoWordSelected()](#isAutoWordSelected--) | 選択範囲を拡張する際に使用される基本単位を指定します。 |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | コントロールでドラッグ アンド ドロップが有効かどうかを示します。 |
| [isEditable()](#isEditable--) | ユーザーがコントロールに入力できるかどうかを示します。 |
| [isEnabled()](#isEnabled--) | コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。 |
| [isLocked()](#isLocked--) | コントロール内のデータが編集ロックされているかどうかを示します。 |
| [isTransparent()](#isTransparent--) | コントロールが透明かどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | このプロパティの説明については、[isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) を参照してください |
| [setBackOleColor(int value)](#setBackOleColor-int-) | このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) を参照してください |
| [setBorderStyle(int value)](#setBorderStyle-int-) | このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) を参照してください |
| [setBoundColumn(int value)](#setBoundColumn-int-) | このプロパティの説明については、[getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) を参照してください |
| [setColumnCount(int value)](#setColumnCount-int-) | このプロパティの説明については、[getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) を参照してください |
| [setColumnWidths(double value)](#setColumnWidths-double-) | このプロパティの説明については、[getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) を参照してください |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | このプロパティの説明については、[isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) を参照してください |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | このプロパティの説明については、[getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) を参照してください |
| [setEditable(boolean value)](#setEditable-boolean-) | このプロパティの説明については、[isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) を参照してください |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | このプロパティの説明については、[getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) を参照してください |
| [setForeOleColor(int value)](#setForeOleColor-int-) | このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください |
| [setHeight(double value)](#setHeight-double-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | このプロパティの説明については、[getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) を参照してください |
| [setIMEMode(int value)](#setIMEMode-int-) | このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください |
| [setListRows(int value)](#setListRows-int-) | このプロパティの説明については、[getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) を参照してください |
| [setListStyle(int value)](#setListStyle-int-) | このプロパティの説明については、[getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) を参照してください |
| [setListWidth(double value)](#setListWidth-double-) | このプロパティの説明については、[getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) を参照してください |
| [setLocked(boolean value)](#setLocked-boolean-) | このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください |
| [setMatchEntry(int value)](#setMatchEntry-int-) | このプロパティの説明については、[getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) を参照してください |
| [setMaxLength(int value)](#setMaxLength-int-) | このプロパティの説明については、[getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) を参照してください |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください |
| [setMousePointer(int value)](#setMousePointer-int-) | このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | このプロパティの説明については、[getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) を参照してください |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | このプロパティの説明については、[getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) を参照してください |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | このプロパティの説明については、[getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) を参照してください |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) を参照してください |
| [setTextColumn(int value)](#setTextColumn-int-) | このプロパティの説明については、[getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) を参照してください |
| [setTransparent(boolean value)](#setTransparent-boolean-) | このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください |
| [setValue(String value)](#setValue-java.lang.String-) | このプロパティの説明については、[getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) を参照してください |
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
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


ComboBox または ListBox の Value プロパティが MultiSelect プロパティの値 (fmMultiSelectSingle) のときにどのように決定されるかを表します。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


ComboBox または ListBox に表示する列数を表します。

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


列の幅。

**Returns:**
double
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
### getListRows() {#getListRows--}
```
public int getListRows()
```


リストに表示する最大行数を表します。

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


視覚的な外観です。

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


ポイント単位の幅です。

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


ユーザーが入力する際に ListBox または ComboBox がリストを検索する方法を示します。

**Returns:**
int
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
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


ユーザーがテキストの左側領域をクリックしてテキスト行を選択できるかどうかを示します。

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


列見出しが表示されるかどうかを示します。

**Returns:**
boolean
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
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


ユーザーに表示する ComboBox または ListBox の列を表します。

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


ActiveX コントロールのタイプを取得します。

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


コントロールの値です。

**Returns:**
java.lang.String
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


このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


このプロパティの説明については、[isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) を参照してください

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


このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


このプロパティの説明については、[getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


このプロパティの説明については、[getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


このプロパティの説明については、[getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


このプロパティの説明については、[isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


このプロパティの説明については、[getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


このプロパティの説明については、[isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) を参照してください

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


このプロパティの説明については、[getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) を参照してください

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


このプロパティの説明については、[getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) を参照してください

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

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


このプロパティの説明については、[getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


このプロパティの説明については、[getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


このプロパティの説明については、[getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


このプロパティの説明については、[getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


このプロパティの説明については、[getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) を参照してください

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

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


このプロパティの説明については、[getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


このプロパティの説明については、[getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


このプロパティの説明については、[getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


このプロパティの説明については、[getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


このプロパティの説明については、[getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

