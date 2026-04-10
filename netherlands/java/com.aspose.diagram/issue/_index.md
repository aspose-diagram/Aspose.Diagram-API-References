---
title: Issue
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een enkel validatieprobleem in het document voor.
type: docs
weight: 208
url: /nl/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Stelt een enkel validatieprobleem in het document voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Issue()](#Issue--) | Constructor |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Specificeert de unieke identifier van het validatieprobleem. |
| [getIgnored()](#getIgnored--) | Specificeert of het validatieprobleem momenteel wordt genegeerd. |
| [getIssueTarget()](#getIssueTarget--) | Afhankelijk van het doel van het bovenliggende validatieprobleem, specificeert het ofwel de pagina, of zowel de pagina als de vorm, waaraan het bovenliggende validatieprobleem is gekoppeld. |
| [getRuleInfo()](#getRuleInfo--) | Specificeert informatie over de validatieregel waar het bovenliggende validatieprobleem betrekking op heeft. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Voor de beschrijving van deze eigenschap, zie [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
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
| Parameter | Type | Beschrijving |
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


Specificeert de unieke identifier van het validatieprobleem.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Specificeert of het validatieprobleem momenteel wordt genegeerd. De standaard is False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Afhankelijk van het doel van het bovenliggende validatie‑issue specificeert dit of de pagina, of zowel de pagina als de vorm, waarmee het bovenliggende validatie‑issue is geassocieerd. Als het doel van het bovenliggende validatie‑issue een document is, specificeert IssueTarget geen pagina noch een vorm.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Specificeert informatie over de validatieregel waar het bovenliggende validatieprobleem betrekking op heeft.

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


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

