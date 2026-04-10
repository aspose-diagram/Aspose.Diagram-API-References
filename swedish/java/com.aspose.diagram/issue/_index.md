---
title: Issue
second_title: Aspose.Diagram för Java API-referens
description: Representerar ett enskilt valideringsproblem i dokumentet.
type: docs
weight: 208
url: /sv/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Representerar ett enskilt valideringsproblem i dokumentet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Issue()](#Issue--) | Konstruktor |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Anger det unika identifieraren för valideringsproblemet. |
| [getIgnored()](#getIgnored--) | Anger om valideringsproblemet för närvarande ignoreras. |
| [getIssueTarget()](#getIssueTarget--) | Beroende på målet för det överordnade valideringsproblemet specificeras antingen sidan, eller både sidan och formen, som det överordnade valideringsproblemet är associerat med. |
| [getRuleInfo()](#getRuleInfo--) | Anger information om valideringsregeln som det överordnade valideringsproblemet avser. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | För beskrivningen av den här egenskapen, se [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
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
### getID() {#getID--}
```
public long getID()
```


Anger det unika identifieraren för valideringsproblemet.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Anger om valideringsproblemet för närvarande ignoreras. Standardvärdet är False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Beroende på målet för det överordnade valideringsproblemet, specificerar antingen sidan, eller både sidan och formen, som problemet är associerat med. Om målet för det överordnade valideringsproblemet är ett dokument, specificerar IssueTarget varken en sida eller en form.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Anger information om valideringsregeln som det överordnade valideringsproblemet avser.

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


För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


För beskrivningen av den här egenskapen, se [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

