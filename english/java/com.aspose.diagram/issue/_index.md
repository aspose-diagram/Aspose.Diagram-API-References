---
title: Issue
second_title: Aspose.Diagram for Java API Reference
description: Represents a single validation issue in the document.
type: docs
weight: 216
url: /java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Represents a single validation issue in the document.
## Constructors

| Constructor | Description |
| --- | --- |
| [Issue()](#Issue--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Specifies the unique identifier of the validation issue. |
| [getIgnored()](#getIgnored--) | Specifies whether the validation issue is currently ignored. |
| [getIssueTarget()](#getIssueTarget--) | Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associated with. |
| [getRuleInfo()](#getRuleInfo--) | Specifies information about the validation rule that the parent validation issue pertains to. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | For the description of this property, please see [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | For the description of this property, please see [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Constructor

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


Specifies the unique identifier of the validation issue.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Specifies whether the validation issue is currently ignored. The default is False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associated with. If the target of the parent validation issue is a document, IssueTarget specifies neither a page nor a shape.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Specifies information about the validation rule that the parent validation issue pertains to.

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


For the description of this property, please see [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


For the description of this property, please see [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

