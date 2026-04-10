---
title: IssueTarget
second_title: Aspose.Diagram for Java API-Referenz
description: Abhängig vom Ziel des übergeordneten Validierungsproblems gibt es entweder die Seite oder sowohl die Seite als auch die Form an, mit der das übergeordnete Validierungsproblem verknüpft ist.
type: docs
weight: 210
url: /de/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

Abhängig vom Ziel des übergeordneten Validierungsproblems gibt es entweder die Seite oder sowohl die Seite als auch die Form an, mit der das übergeordnete Validierungsproblem verknüpft ist. Wenn das Ziel des übergeordneten Validierungsproblems ein Dokument ist, gibt IssueTarget weder eine Seite noch eine Form an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Gibt die eindeutige Kennung der Seite an, die dem übergeordneten Validierungsproblem zugeordnet ist. |
| [getShapeId()](#getShapeId--) | Gibt die eindeutige Kennung der Form an, die dem übergeordneten Validierungsproblem zugeordnet ist. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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


Gibt die eindeutige Kennung der Seite an, die dem übergeordneten Validierungsproblem zugeordnet ist. Wenn das Ziel das Dokument ist, kann der PageID-Wert 0xFFFFFFFF sein.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Gibt die eindeutige Kennung der Form an, die dem übergeordneten Validierungsproblem zugeordnet ist. Wenn das Ziel das Dokument oder eine Seite ist, kann der ShapeID-Wert 0xFFFFFFFF sein.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

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

