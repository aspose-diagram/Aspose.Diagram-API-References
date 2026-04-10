---
title: EventItem
second_title: Aspose.Diagram för Java API-referens
description: Inkapslar en händelsekod.
type: docs
weight: 145
url: /sv/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Inkapslar en händelsekod. Ett EventItem-element kan utlösa två typer av åtgärder: det kan köra ett add-on, eller det kan skicka en notifikation om händelsen till det anropande programmet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EventItem()](#EventItem--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Anger åtgärdskoden för det överordnade EventItem-elementet. För att ett EventItem-element ska sparas i en DatadiagramML-fil måste det vara beständigt. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Representerar en flagga som indikerar om händelsen är aktiverad eller inaktiverad. |
| [getEventCode()](#getEventCode--) | En kod som indikerar händelsen som utlöser add-on. |
| [getID()](#getID--) | Händelsens ID. |
| [getTarget()](#getTarget--) | Anger målet för en händelse. |
| [getTargetArgs()](#getTargetArgs--) | Anger en sträng som innehåller argument som ska skickas till händelsens mål. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | För beskrivningen av denna egenskap, se [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | För beskrivningen av denna egenskap, se [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | För beskrivningen av denna egenskap, se [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | För beskrivningen av denna egenskap, se [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | För beskrivningen av denna egenskap, se [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


Konstruktor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public int getAction()
```


Anger åtgärdskoden för det överordnade EventItem-elementet. För att ett EventItem-element ska sparas i en DatadiagramML-fil måste det vara beständigt. För närvarande är den enda giltiga åtgärdskoden som ett beständigt evenemang kan ha 1 (ONEVENT_ACT_RUNADDON).

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


Representerar en flagga som indikerar om händelsen är aktiverad eller inaktiverad.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


En kod som indikerar händelsen som utlöser add-on. För mer information om händelsekoder, se Event Codes i Microsoft Visio 2007 Automation Reference.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Händelsens ID.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Anger målet för en händelse.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Anger en sträng som innehåller argument som ska skickas till händelsens mål.

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


För beskrivningen av denna egenskap, se [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


För beskrivningen av denna egenskap, se [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


För beskrivningen av denna egenskap, se [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


För beskrivningen av denna egenskap, se [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


För beskrivningen av denna egenskap, se [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

