---
title: EventItem
second_title: Aspose.Diagram for Java API Reference
description: Encapsulates an event code.
type: docs
weight: 149
url: /java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Encapsulates an event code. An EventItem element can trigger two kinds of actions: it can run an add-on, or it can send a notification of the event to the calling program.
## Constructors

| Constructor | Description |
| --- | --- |
| [EventItem()](#EventItem--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file, it must be persistable. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Represents a flag indicating if the event is enabled or disabled. |
| [getEventCode()](#getEventCode--) | A code indicating the event that triggers the add-on. |
| [getID()](#getID--) | The ID of the event. |
| [getTarget()](#getTarget--) | Specifies the target of an event. |
| [getTargetArgs()](#getTargetArgs--) | Specifies a string containing arguments to be sent to the target of an event. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | For the description of this property, please see [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | For the description of this property, please see [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | For the description of this property, please see [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | For the description of this property, please see [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | For the description of this property, please see [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file, it must be persistable. Currently, the only valid action code a persistable event can have is 1 (ONEVENT\_ACT\_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Represents a flag indicating if the event is enabled or disabled.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Microsoft Visio 2007 Automation Reference.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


The ID of the event.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Specifies the target of an event.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Specifies a string containing arguments to be sent to the target of an event.

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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


For the description of this property, please see [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


For the description of this property, please see [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


For the description of this property, please see [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


For the description of this property, please see [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


For the description of this property, please see [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

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

