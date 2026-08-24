---
title: Issue
second_title: Aspose.Diagram for Java API-Referenz
description: Stellt ein einzelnes Validierungsproblem im Dokument dar.
type: docs
weight: 208
url: /de/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Stellt ein einzelnes Validierungsproblem im Dokument dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Issue()](#Issue--) | Konstruktor |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Gibt die eindeutige Kennung des Validierungsproblems an. |
| [getIgnored()](#getIgnored--) | Gibt an, ob das Validierungsproblem derzeit ignoriert wird. |
| [getIssueTarget()](#getIssueTarget--) | Abhängig vom Ziel des übergeordneten Validierungsproblems gibt es entweder die Seite oder sowohl die Seite als auch die Form an, mit denen das übergeordnete Validierungsproblem verknüpft ist. |
| [getRuleInfo()](#getRuleInfo--) | Gibt Informationen über die Validierungsregel an, auf die sich das übergeordnete Validierungsproblem bezieht. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Konstruktor

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
### getID() {#getID--}
```
public long getID()
```


Gibt die eindeutige Kennung des Validierungsproblems an.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Gibt an, ob das Validierungsproblem derzeit ignoriert wird. Der Standardwert ist False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Abhängig vom Ziel des übergeordneten Validierungsproblems gibt es entweder die Seite oder sowohl die Seite als auch die Form an, mit der das übergeordnete Validierungsproblem verknüpft ist. Wenn das Ziel des übergeordneten Validierungsproblems ein Dokument ist, gibt IssueTarget weder eine Seite noch eine Form an.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Gibt Informationen über die Validierungsregel an, auf die sich das übergeordnete Validierungsproblem bezieht.

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

