---
title: DataColumn
second_title: Aspose.Diagram for Java API Reference
description: Defines how a data column appears in the External Data window in the Visio user interface and qualifies the data in the column by defining its data type and formatting.
type: docs
weight: 108
url: /java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Defines how a data column appears in the External Data window in the Visio user interface and qualifies the data in the column by defining its data type and formatting.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataColumn()](#DataColumn--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Calendar ID of the data column. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | External name of the data column. |
| [getCurrency()](#getCurrency--) | Currency ID of the data column. |
| [getDataType()](#getDataType--) | Type of the data in the data column. |
| [getDegree()](#getDegree--) | Specifies the degree (power) of the units, for example squared, or cubed. |
| [getDisplayOrder()](#getDisplayOrder--) | Defines the display position of the data column in the External Data window, from the left-most column (0) to the right-most column (largest value). |
| [getDisplayWidth()](#getDisplayWidth--) | Width of the data column in the External Data window. |
| [getHyperlink()](#getHyperlink--) | Whether the data column creates a hyperlink in a shape when the shape is linked to data. |
| [getLabel()](#getLabel--) | Label of the data column. |
| [getLangID()](#getLangID--) | The language ID of the data column |
| [getMapped()](#getMapped--) | Specifies whether the column is visible in the External Data window. |
| [getName()](#getName--) | Internal name of the data column. |
| [getOrigLabel()](#getOrigLabel--) | Column label returned to Visio by the underlying ADO interface. |
| [getUnitType()](#getUnitType--) | Unit type of the data in the data column. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | For the description of this property, please see \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | For the description of this property, please see [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--) |
| [setCurrency(int value)](#setCurrency-int-) | For the description of this property, please see \{@link DataColumn\#(getCurrency() & 0xFFFF)\} |
| [setDataType(int value)](#setDataType-int-) | For the description of this property, please see \{@link DataColumn\#(getDataType() & 0xFFFF)\} |
| [setDegree(long value)](#setDegree-long-) | For the description of this property, please see [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--) |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | For the description of this property, please see [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--) |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | For the description of this property, please see [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--) |
| [setHyperlink(int value)](#setHyperlink-int-) | For the description of this property, please see [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--) |
| [setLabel(String value)](#setLabel-java.lang.String-) | For the description of this property, please see [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--) |
| [setLangID(long value)](#setLangID-long-) | For the description of this property, please see [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--) |
| [setMapped(int value)](#setMapped-int-) | For the description of this property, please see [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/datacolumn\#getName--) |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | For the description of this property, please see [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--) |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | For the description of this property, please see [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
```


Constructor.

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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


Calendar ID of the data column.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


External name of the data column. Appears in the headings in the External Data window and in labels in data graphics.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


Currency ID of the data column.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


Type of the data in the data column.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


Specifies the degree (power) of the units, for example squared, or cubed. The default (attribute absent) is 1.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


Defines the display position of the data column in the External Data window, from the left-most column (0) to the right-most column (largest value).

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


Width of the data column in the External Data window.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


Whether the data column creates a hyperlink in a shape when the shape is linked to data.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


Label of the data column.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


The language ID of the data column

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


Specifies whether the column is visible in the External Data window. True (1) for the column to be visible; false (0) for the column not to be visible. The default (attribute absent) is for the column to be visible.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Internal name of the data column. Used as the row name for the shape-data item (custom property) added to a shape when the shape is linked to a data row.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


Column label returned to Visio by the underlying ADO interface.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


Unit type of the data in the data column.

**Returns:**
java.lang.String
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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


For the description of this property, please see \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


For the description of this property, please see [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


For the description of this property, please see \{@link DataColumn\#(getCurrency() & 0xFFFF)\}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


For the description of this property, please see \{@link DataColumn\#(getDataType() & 0xFFFF)\}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


For the description of this property, please see [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


For the description of this property, please see [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


For the description of this property, please see [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


For the description of this property, please see [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


For the description of this property, please see [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


For the description of this property, please see [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


For the description of this property, please see [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/datacolumn\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


For the description of this property, please see [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


For the description of this property, please see [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

