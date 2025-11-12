---
title: ListBoxActiveXControl
second_title: Aspose.Diagram for Java API Reference
description: Represents a ListBox ActiveX control.
type: docs
weight: 238
url: /java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

Represents a ListBox ActiveX control.
## Methods

| Method | Description |
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
| [getIntegralHeight()](#getIntegralHeight--) | Indicates whether the control will only show complete lines of text without showing any partial lines. |
| [getListStyle()](#getListStyle--) | the visual appearance. |
| [getListWidth()](#getListWidth--) | the width in unit of points. |
| [getMatchEntry()](#getMatchEntry--) | Indicates how a ListBox or ComboBox searches its list as the user types. |
| [getMouseIcon()](#getMouseIcon--) | a custom icon to display as the mouse pointer for the control. |
| [getMousePointer()](#getMousePointer--) | the type of icon displayed as the mouse pointer for the control. |
| [getScrollBars()](#getScrollBars--) | Indicates specifies whether the control has vertical scroll bars, horizontal scroll bars, both, or neither. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Indicates whether column headings are displayed. |
| [getSpecialEffect()](#getSpecialEffect--) | the special effect of the control. |
| [getTextColumn()](#getTextColumn--) | Represents the column in a ComboBox or ListBox to display to the user. |
| [getType()](#getType--) | Gets the type of the ActiveX control. |
| [getValue()](#getValue--) | the value of the control. |
| [getWidth()](#getWidth--) | the width of the control in unit of point. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indicates whether the control will automatically resize to display its entire contents. |
| [isEnabled()](#isEnabled--) | Indicates whether the control can receive the focus and respond to user-generated events. |
| [isLocked()](#isLocked--) | Indicates whether data in the control is locked for editing. |
| [isTransparent()](#isTransparent--) | Indicates whether the control is transparent. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | For the description of this property, please see [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | For the description of this property, please see [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | For the description of this property, please see [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | For the description of this property, please see [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | For the description of this property, please see [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | For the description of this property, please see [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | For the description of this property, please see [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | For the description of this property, please see [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | For the description of this property, please see [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | For the description of this property, please see [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | For the description of this property, please see [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | For the description of this property, please see [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--) |
| [setListStyle(int value)](#setListStyle-int-) | For the description of this property, please see [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | For the description of this property, please see [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | For the description of this property, please see [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | For the description of this property, please see [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | For the description of this property, please see [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | For the description of this property, please see [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setScrollBars(int value)](#setScrollBars-int-) | For the description of this property, please see [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | For the description of this property, please see [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | For the description of this property, please see [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | For the description of this property, please see [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | For the description of this property, please see [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | For the description of this property, please see [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | For the description of this property, please see [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


the ole color of the foreground. Not applies to Image control.

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


Indicates whether the control will only show complete lines of text without showing any partial lines.

**Returns:**
boolean
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


the visual appearance.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


the width in unit of points.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Indicates how a ListBox or ComboBox searches its list as the user types.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


a custom icon to display as the mouse pointer for the control.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


the type of icon displayed as the mouse pointer for the control.

**Returns:**
int
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indicates specifies whether the control has vertical scroll bars, horizontal scroll bars, both, or neither.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Indicates whether column headings are displayed.

**Returns:**
boolean
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


the special effect of the control.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Represents the column in a ComboBox or ListBox to display to the user.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Gets the type of the ActiveX control.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


the value of the control.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


the width of the control in unit of point.

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


Indicates whether the control will automatically resize to display its entire contents.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indicates whether the control can receive the focus and respond to user-generated events.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indicates whether data in the control is locked for editing.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indicates whether the control is transparent.

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


For the description of this property, please see [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


For the description of this property, please see [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


For the description of this property, please see [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


For the description of this property, please see [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


For the description of this property, please see [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


For the description of this property, please see [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


For the description of this property, please see [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


For the description of this property, please see [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


For the description of this property, please see [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


For the description of this property, please see [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


For the description of this property, please see [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


For the description of this property, please see [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


For the description of this property, please see [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


For the description of this property, please see [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


For the description of this property, please see [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


For the description of this property, please see [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


For the description of this property, please see [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


For the description of this property, please see [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


For the description of this property, please see [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


For the description of this property, please see [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


For the description of this property, please see [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


For the description of this property, please see [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


For the description of this property, please see [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


For the description of this property, please see [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


For the description of this property, please see [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

