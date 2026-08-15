---
title: IssueTarget
second_title: Aspose.Diagram för Java API-referens
description: Beroende på målet för det överordnade valideringsproblemet specificerar antingen sidan eller både sidan och formen som problemet är associerat med.
type: docs
weight: 210
url: /sv/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

Beroende på målet för det överordnade valideringsproblemet, specificerar antingen sidan, eller både sidan och formen, som problemet är associerat med. Om målet för det överordnade valideringsproblemet är ett dokument, specificerar IssueTarget varken en sida eller en form.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Specificerar den unika identifieraren för sidan som är associerad med det överordnade valideringsproblemet. |
| [getShapeId()](#getShapeId--) | Specificerar den unika identifieraren för formen som är associerad med det överordnade valideringsproblemet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | För beskrivningen av denna egenskap, se [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | För beskrivningen av denna egenskap, se [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Konstruktor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPageId() {#getPageId--}
```
public long getPageId()
```


Specificerar den unika identifieraren för sidan som är associerad med det överordnade valideringsproblemet. Om målet är dokumentet kan PageID‑värdet vara 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Specificerar den unika identifieraren för formen som är associerad med det överordnade valideringsproblemet. Om målet är dokumentet eller en sida kan ShapeID‑värdet vara 0xFFFFFFFF.

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


För beskrivningen av denna egenskap, se [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


För beskrivningen av denna egenskap, se [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

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

