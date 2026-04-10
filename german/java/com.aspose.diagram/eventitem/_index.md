---
title: EventItem
second_title: Aspose.Diagram for Java API-Referenz
description: Kapselt einen Ereigniscode.
type: docs
weight: 145
url: /de/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Kapselt einen Ereigniscode. Ein EventItem-Element kann zwei Arten von Aktionen auslösen: Es kann ein Add‑On ausführen oder eine Benachrichtigung des Ereignisses an das aufrufende Programm senden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EventItem()](#EventItem--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Gibt den Aktionscode des übergeordneten EventItem-Elements an. Damit ein EventItem-Element in einer DatadiagramML-Datei gespeichert werden kann, muss es persistierbar sein. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Stellt ein Flag dar, das angibt, ob das Ereignis aktiviert oder deaktiviert ist. |
| [getEventCode()](#getEventCode--) | Ein Code, der das Ereignis angibt, das das Add‑On auslöst. |
| [getID()](#getID--) | Die ID des Ereignisses. |
| [getTarget()](#getTarget--) | Gibt das Ziel eines Ereignisses an. |
| [getTargetArgs()](#getTargetArgs--) | Gibt eine Zeichenkette an, die Argumente enthält, die an das Ziel eines Ereignisses gesendet werden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public int getAction()
```


Gibt den Aktionscode des übergeordneten EventItem-Elements an. Damit ein EventItem-Element in einer DatadiagramML-Datei gespeichert werden kann, muss es persistierbar sein. Derzeit ist der einzige gültige Aktionscode, den ein persistierbares Ereignis haben kann, 1 (ONEVENT\_ACT\_RUNADDON).

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


Stellt ein Flag dar, das angibt, ob das Ereignis aktiviert oder deaktiviert ist.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Ein Code, der das Ereignis angibt, das das Add‑On auslöst. Weitere Informationen zu Ereigniscodes finden Sie in den Event Codes in der Microsoft Visio 2007 Automation Reference.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Die ID des Ereignisses.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Gibt das Ziel eines Ereignisses an.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Gibt eine Zeichenkette an, die Argumente enthält, die an das Ziel eines Ereignisses gesendet werden.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

