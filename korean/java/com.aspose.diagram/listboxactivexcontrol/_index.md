---
title: ListBoxActiveXControl
second_title: Aspose.Diagram for Java API 참조
description: ListBox ActiveX 컨트롤을 나타냅니다.
type: docs
weight: 234
url: /ko/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

ListBox ActiveX 컨트롤을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getBorderOleColor()](#getBorderOleColor--) | the ole color of the background. |
| [getBorderStyle()](#getBorderStyle--) | the type of border used by the control. |
| [getBoundColumn()](#getBoundColumn--) | Represents how the Value property is determined for a ComboBox or ListBox when the MultiSelect propertys value (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Represents the number of columns to display in a ComboBox or ListBox. |
| [getColumnWidths()](#getColumnWidths--) | the width of the column. |
| [getData()](#getData--) | the binary data of the control. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getIntegralHeight()](#getIntegralHeight--) | 컨트롤이 부분적인 줄을 표시하지 않고 전체 텍스트 줄만 표시할지 여부를 나타냅니다. |
| [getListStyle()](#getListStyle--) | 시각적 모양. |
| [getListWidth()](#getListWidth--) | 포인트 단위의 너비. |
| [getMatchEntry()](#getMatchEntry--) | 사용자가 입력할 때 ListBox 또는 ComboBox가 목록을 검색하는 방식을 나타냅니다. |
| [getMouseIcon()](#getMouseIcon--) | 컨트롤에 대한 마우스 포인터로 표시할 사용자 지정 아이콘. |
| [getMousePointer()](#getMousePointer--) | 컨트롤에 대한 마우스 포인터로 표시되는 아이콘 유형. |
| [getScrollBars()](#getScrollBars--) | 컨트롤에 수직 스크롤 바, 수평 스크롤 바, 둘 다, 또는 전혀 없는지를 나타냅니다. |
| [getShowColumnHeads()](#getShowColumnHeads--) | 열 머리글이 표시되는지 여부를 나타냅니다. |
| [getSpecialEffect()](#getSpecialEffect--) | 컨트롤의 특수 효과. |
| [getTextColumn()](#getTextColumn--) | 사용자에게 표시할 ComboBox 또는 ListBox의 열을 나타냅니다. |
| [getType()](#getType--) | ActiveX 컨트롤의 유형을 가져옵니다. |
| [getValue()](#getValue--) | 컨트롤의 값. |
| [getWidth()](#getWidth--) | 포인트 단위의 컨트롤 너비. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | 컨트롤이 전체 내용을 표시하도록 자동으로 크기를 조정하는지 여부를 나타냅니다. |
| [isEnabled()](#isEnabled--) | 컨트롤이 포커스를 받을 수 있고 사용자 생성 이벤트에 응답할 수 있는지 여부를 나타냅니다. |
| [isLocked()](#isLocked--) | 컨트롤의 데이터가 편집을 위해 잠겨 있는지 여부를 나타냅니다. |
| [isTransparent()](#isTransparent--) | 컨트롤이 투명한지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | 이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)을 참조하십시오 |
| [setBackOleColor(int value)](#setBackOleColor-int-) | 이 속성에 대한 설명은 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)을 참조하십시오 |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | 이 속성에 대한 설명은 [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)을(를) 참조하십시오. |
| [setBorderStyle(int value)](#setBorderStyle-int-) | 이 속성에 대한 설명은 [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)을(를) 참조하십시오. |
| [setBoundColumn(int value)](#setBoundColumn-int-) | 이 속성에 대한 설명은 [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)을(를) 참조하십시오. |
| [setColumnCount(int value)](#setColumnCount-int-) | 이 속성에 대한 설명은 [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)을(를) 참조하십시오. |
| [setColumnWidths(double value)](#setColumnWidths-double-) | 이 속성에 대한 설명은 [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)을(를) 참조하십시오. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 이 속성에 대한 설명은 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)을(를) 참조하십시오. |
| [setForeOleColor(int value)](#setForeOleColor-int-) | 이 속성에 대한 설명은 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)을(를) 참조하십시오. |
| [setHeight(double value)](#setHeight-double-) | 이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)을(를) 참조하십시오. |
| [setIMEMode(int value)](#setIMEMode-int-) | 이 속성에 대한 설명은 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)을(를) 참조하십시오. |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | 이 속성에 대한 설명은 [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)을(를) 참조하십시오. |
| [setListStyle(int value)](#setListStyle-int-) | 이 속성에 대한 설명은 [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)을(를) 참조하십시오. |
| [setListWidth(double value)](#setListWidth-double-) | 이 속성에 대한 설명은 [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)을(를) 참조하십시오. |
| [setLocked(boolean value)](#setLocked-boolean-) | 이 속성에 대한 설명은 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)을(를) 참조하십시오. |
| [setMatchEntry(int value)](#setMatchEntry-int-) | 이 속성에 대한 설명은 [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)을(를) 참조하십시오. |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | 이 속성에 대한 설명은 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)을(를) 참조하십시오. |
| [setMousePointer(int value)](#setMousePointer-int-) | 이 속성에 대한 설명은 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)을(를) 참조하십시오. |
| [setScrollBars(int value)](#setScrollBars-int-) | 이 속성에 대한 설명은 [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)을(를) 참조하십시오. |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | 이 속성에 대한 설명은 [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)을(를) 참조하십시오. |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | 이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)을(를) 참조하십시오. |
| [setTextColumn(int value)](#setTextColumn-int-) | 이 속성에 대한 설명은 [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)을(를) 참조하십시오. |
| [setTransparent(boolean value)](#setTransparent-boolean-) | 이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오. |
| [setValue(String value)](#setValue-java.lang.String-) | 이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)을(를) 참조하십시오. |
| [setWidth(double value)](#setWidth-double-) | 이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


the ole color of the background.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


the ole color of the background.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


the type of border used by the control.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Represents how the Value property is determined for a ComboBox or ListBox when the MultiSelect propertys value (fmMultiSelectSingle).

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


Represents the number of columns to display in a ComboBox or ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


the width of the column.

**Returns:**
double
### getData() {#getData--}
```
public byte[] getData()
```


the binary data of the control.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


전경의 OLE 색상입니다. Image 컨트롤에는 적용되지 않습니다.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


the height of the control in unit of points.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


the default run-time mode of the Input Method Editor for the control as it receives focus.

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


컨트롤이 부분적인 줄을 표시하지 않고 전체 텍스트 줄만 표시할지 여부를 나타냅니다.

**Returns:**
boolean
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


시각적 모양.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


포인트 단위의 너비.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


사용자가 입력할 때 ListBox 또는 ComboBox가 목록을 검색하는 방식을 나타냅니다.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


컨트롤에 대한 마우스 포인터로 표시할 사용자 지정 아이콘.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


컨트롤에 대한 마우스 포인터로 표시되는 아이콘 유형.

**Returns:**
int
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


컨트롤에 수직 스크롤 바, 수평 스크롤 바, 둘 다, 또는 전혀 없는지를 나타냅니다.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


열 머리글이 표시되는지 여부를 나타냅니다.

**Returns:**
boolean
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


컨트롤의 특수 효과.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


사용자에게 표시할 ComboBox 또는 ListBox의 열을 나타냅니다.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


ActiveX 컨트롤의 유형을 가져옵니다.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


컨트롤의 값.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


포인트 단위의 컨트롤 너비.

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


컨트롤이 전체 내용을 표시하도록 자동으로 크기를 조정하는지 여부를 나타냅니다.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


컨트롤이 포커스를 받을 수 있고 사용자 생성 이벤트에 응답할 수 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


컨트롤의 데이터가 편집을 위해 잠겨 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


컨트롤이 투명한지 여부를 나타냅니다.

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


이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)을 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


이 속성에 대한 설명은 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)을 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


이 속성에 대한 설명은 [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


이 속성에 대한 설명은 [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


이 속성에 대한 설명은 [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


이 속성에 대한 설명은 [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


이 속성에 대한 설명은 [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


이 속성에 대한 설명은 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


이 속성에 대한 설명은 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


이 속성에 대한 설명은 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


이 속성에 대한 설명은 [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


이 속성에 대한 설명은 [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


이 속성에 대한 설명은 [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


이 속성에 대한 설명은 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


이 속성에 대한 설명은 [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


이 속성에 대한 설명은 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


이 속성에 대한 설명은 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


이 속성에 대한 설명은 [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


이 속성에 대한 설명은 [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


이 속성에 대한 설명은 [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

