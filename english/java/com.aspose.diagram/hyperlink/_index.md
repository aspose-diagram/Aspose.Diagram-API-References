---
title: Hyperlink
second_title: Aspose.Diagram for Java API Reference
description: Contains elements for creating multiple jumps between a shape or drawing page and another drawing page another file or a Web site.
type: docs
weight: 193
url: /java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Contains elements for creating multiple jumps between a shape or drawing page and another drawing page, another file, or a Web site.
## Constructors

| Constructor | Description |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Specifies a URL address, DOS file name, or UNC path to jump to. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Specifies the default hyperlink for a shape or page. |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getDescription()](#getDescription--) | Description element contains a text string that describes the hyperlink. |
| [getExtraInfo()](#getExtraInfo--) | Contains information to be used in resolving a URL, such as the coordinates of an image map. |
| [getFrame()](#getFrame--) | Contains the name of a frame to target when Microsoft Visio is open as an active document in a container application. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getInvisible()](#getInvisible--) | Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getNewWindow()](#getNewWindow--) | Specifies whether Microsoft Visio opens a window in a new location when it follows a hyperlink to open a Web page or another Visio document. |
| [getSortKey()](#getSortKey--) | Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page. |
| [getSubAddress()](#getSubAddress--) | Specifies a location within the target document to link to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates deep copy of this instance.

**Returns:**
java.lang.Object - 
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Specifies a URL address, DOS file name, or UNC path to jump to.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Specifies the default hyperlink for a shape or page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Description element contains a text string that describes the hyperlink.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Contains information to be used in resolving a URL, such as the coordinates of an image map. For example, x=41 y=7 would specify the coordinates of an image map.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Contains the name of a frame to target when Microsoft Visio is open as an active document in a container application. The default is an empty string.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


The unique ID of the element within its parent element.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Specifies whether Microsoft Visio opens a window in a new location when it follows a hyperlink to open a Web page or another Visio document.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Specifies a location within the target document to link to.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

