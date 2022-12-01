---
title: Act
second_title: Aspose.Diagram for Java API Reference
description: Defines custom command names that appear on an objects shortcut menu and specifies the actions that the commands take.
type: docs
weight: 11
url: /java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Defines custom command names that appear on an object's shortcut menu and specifies the actions that the commands take.
## Constructors

| Constructor | Description |
| --- | --- |
| [Act()](#Act--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element. |
| [getBeginGroup()](#getBeginGroup--) | Indicates whether a separator is inserted into the menu above this action. |
| [getButtonFace()](#getButtonFace--) | It identifies the icon that appears next to an item on a shortcut menu. |
| [getChecked()](#getChecked--) | Determines whether a check mark is displayed beside the command name on a shape's shortcut menu. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getDisabled()](#getDisabled--) | Disabled element determines whether the command name is displayed on the shortcut menu. |
| [getFlyoutChild()](#getFlyoutChild--) | Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getIX()](#getIX--) | The zero-based index of the element within its parent element. |
| [getInvisible()](#getInvisible--) | Invisible element indicates whether the action is visible on the smart tag or shortcut menu. |
| [getMenu()](#getMenu--) | Specifies the name of the command that appears on the shortcut menu for a shape or page. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getReadOnly()](#getReadOnly--) | Determines whether the action on a smart tag or shortcut menu is read-only. |
| [getSortKey()](#getSortKey--) | It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu. |
| [getTagName()](#getTagName--) | It contains the name of the smart tag that the action is associated with. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Indicates whether a separator is inserted into the menu above this action.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


It identifies the icon that appears next to an item on a shortcut menu.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Determines whether a check mark is displayed beside the command name on a shape's shortcut menu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Disabled element determines whether the command name is displayed on the shortcut menu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Invisible element indicates whether the action is visible on the smart tag or shortcut menu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Specifies the name of the command that appears on the shortcut menu for a shape or page.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Determines whether the action on a smart tag or shortcut menu is read-only.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


It contains the name of the smart tag that the action is associated with.

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


For the description of this property, please see [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/act\#getNameU--)

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

