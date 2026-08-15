---
title: ListBoxActiveXControl
second_title: Aspose.Diagram for Java API リファレンス
description: ListBox ActiveX コントロールを表します。
type: docs
weight: 234
url: /ja/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

ListBox ActiveX コントロールを表します。
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
| [getForeOleColor()](#getForeOleColor--) | 前景の OLE カラー。 |
| [getHeight()](#getHeight--) | ポイント単位のコントロールの高さ。 |
| [getIMEMode()](#getIMEMode--) | コントロールがフォーカスを受け取る際の Input Method Editor のデフォルト実行時モード。 |
| [getIntegralHeight()](#getIntegralHeight--) | コントロールが部分的な行を表示せず、完全な行のみを表示するかどうかを示します。 |
| [getListStyle()](#getListStyle--) | 視覚的な外観です。 |
| [getListWidth()](#getListWidth--) | ポイント単位の幅です。 |
| [getMatchEntry()](#getMatchEntry--) | ユーザーが入力する際に ListBox または ComboBox がリストを検索する方法を示します。 |
| [getMouseIcon()](#getMouseIcon--) | コントロールのマウスポインタとして表示するカスタムアイコンです。 |
| [getMousePointer()](#getMousePointer--) | コントロールのマウスポインタとして表示されるアイコンの種類です。 |
| [getScrollBars()](#getScrollBars--) | コントロールに垂直スクロールバー、水平スクロールバー、両方、またはどちらもないかを示します。 |
| [getShowColumnHeads()](#getShowColumnHeads--) | 列見出しが表示されるかどうかを示します。 |
| [getSpecialEffect()](#getSpecialEffect--) | コントロールの特殊効果です。 |
| [getTextColumn()](#getTextColumn--) | ユーザーに表示する ComboBox または ListBox の列を表します。 |
| [getType()](#getType--) | ActiveX コントロールのタイプを取得します。 |
| [getValue()](#getValue--) | コントロールの値です。 |
| [getWidth()](#getWidth--) | ポイント単位のコントロールの幅です。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | コントロールが全内容を表示するために自動的にサイズ変更されるかどうかを示します。 |
| [isEnabled()](#isEnabled--) | コントロールがフォーカスを受け取り、ユーザー生成イベントに応答できるかどうかを示します。 |
| [isLocked()](#isLocked--) | コントロール内のデータが編集ロックされているかどうかを示します。 |
| [isTransparent()](#isTransparent--) | コントロールが透明かどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | このプロパティの説明については、[isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) を参照してください |
| [setBackOleColor(int value)](#setBackOleColor-int-) | このプロパティの説明については、[getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) を参照してください |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)をご覧ください。 |
| [setBorderStyle(int value)](#setBorderStyle-int-) | このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)をご覧ください。 |
| [setBoundColumn(int value)](#setBoundColumn-int-) | このプロパティの説明については、[getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)をご覧ください。 |
| [setColumnCount(int value)](#setColumnCount-int-) | このプロパティの説明については、[getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)をご覧ください。 |
| [setColumnWidths(double value)](#setColumnWidths-double-) | このプロパティの説明については、[getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)をご覧ください。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | このプロパティの説明については、[isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) を参照してください |
| [setForeOleColor(int value)](#setForeOleColor-int-) | このプロパティの説明については、[getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) を参照してください |
| [setHeight(double value)](#setHeight-double-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) を参照してください |
| [setIMEMode(int value)](#setIMEMode-int-) | このプロパティの説明については、[getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) を参照してください |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | このプロパティの説明については、[getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)をご覧ください。 |
| [setListStyle(int value)](#setListStyle-int-) | このプロパティの説明については、[getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) を参照してください |
| [setListWidth(double value)](#setListWidth-double-) | このプロパティの説明については、[getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) を参照してください |
| [setLocked(boolean value)](#setLocked-boolean-) | このプロパティの説明については、[isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) を参照してください |
| [setMatchEntry(int value)](#setMatchEntry-int-) | このプロパティの説明については、[getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) を参照してください |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | このプロパティの説明については、[getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) を参照してください |
| [setMousePointer(int value)](#setMousePointer-int-) | このプロパティの説明については、[getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) を参照してください |
| [setScrollBars(int value)](#setScrollBars-int-) | このプロパティの説明については、[getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) を参照してください |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | このプロパティの説明については、[getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) を参照してください |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) を参照してください |
| [setTextColumn(int value)](#setTextColumn-int-) | このプロパティの説明については、[getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) を参照してください |
| [setTransparent(boolean value)](#setTransparent-boolean-) | このプロパティの説明については、[isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) を参照してください |
| [setValue(String value)](#setValue-java.lang.String-) | このプロパティの説明については、[getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) を参照してください |
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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


コントロールが部分的な行を表示せず、完全な行のみを表示するかどうかを示します。

**Returns:**
boolean
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
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


コントロールに垂直スクロールバー、水平スクロールバー、両方、またはどちらもないかを示します。

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


列見出しが表示されるかどうかを示します。

**Returns:**
boolean
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


このプロパティの説明については、[getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


このプロパティの説明については、[getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


このプロパティの説明については、[getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


このプロパティの説明については、[getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


このプロパティの説明については、[getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


このプロパティの説明については、[getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


このプロパティの説明については、[getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


このプロパティの説明については、[getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) を参照してください

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


このプロパティの説明については、[getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) を参照してください

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

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


このプロパティの説明については、[getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


このプロパティの説明については、[getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


このプロパティの説明については、[getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


このプロパティの説明については、[getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) を参照してください

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


このプロパティの説明については、[getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) を参照してください

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

