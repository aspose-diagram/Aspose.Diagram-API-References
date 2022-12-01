---
title: Prop
second_title: Aspose.Diagram for Java API Reference
description: Contains elements for defining custom properties and elements for associating data with a shape.
type: docs
weight: 309
url: /java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Contains elements for defining custom properties and elements for associating data with a shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [Prop()](#Prop--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Determines the calendar that is used for custom properties, text fields, and element formulas. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getFormat()](#getFormat--) | Format element specifies the formatting of a custom property that is a string, fixed list, number, variable list, date or time, duration, or currency. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getIX()](#getIX--) | The zero-based index of the element within its parent element. |
| [getInvisible()](#getInvisible--) | Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visio. |
| [getLabel()](#getLabel--) | Specifies the label that appears to users in the Custom Properties dialog box. |
| [getLangID()](#getLangID--) | Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getPrompt()](#getPrompt--) | Prompt element specifies descriptive or instructional text that appears to users in the Custom Properties dialog box when the property is selected. |
| [getSortKey()](#getSortKey--) | It specifies a key that determines the order in which custom properties are listed in the application's user interface. |
| [getType()](#getType--) | Type specifies a data type for the custom property value. |
| [getValue()](#getValue--) | Contains solution-specific, well-formed XML data that is prefixed in an explicit namespace and is stored with a document. |
| [getVerify()](#getVerify--) | Specifies whether the user is queried to enter custom property information for a shape when an instance is created or the shape is duplicated or copied. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Constructor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Creates deep copy of this instance.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
public Calendar getCalendar()
```


Determines the calendar that is used for custom properties, text fields, and element formulas.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Format element specifies the formatting of a custom property that is a string, fixed list, number, variable list, date or time, duration, or currency. The custom property type is specified in the corresponding Type element.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


The unique ID of the element within its parent element.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


The zero-based index of the element within its parent element.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Specifies the label that appears to users in the Custom Properties dialog box.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


The name of the element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


The universal name of the element.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt element specifies descriptive or instructional text that appears to users in the Custom Properties dialog box when the property is selected. This text also appears as a tool tip when the mouse pointer is paused over the property in the Custom Properties window.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


It specifies a key that determines the order in which custom properties are listed in the application's user interface.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Type specifies a data type for the custom property value.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Contains solution-specific, well-formed XML data that is prefixed in an explicit namespace and is stored with a document.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Specifies whether the user is queried to enter custom property information for a shape when an instance is created or the shape is duplicated or copied.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

