---
title: Issue
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente un problème de validation unique dans le document.
type: docs
weight: 208
url: /fr/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Représente un problème de validation unique dans le document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Issue()](#Issue--) | Constructeur |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Spécifie l'identifiant unique du problème de validation. |
| [getIgnored()](#getIgnored--) | Spécifie si le problème de validation est actuellement ignoré. |
| [getIssueTarget()](#getIssueTarget--) | Selon la cible du problème de validation parent, spécifie soit la page, soit la page et la forme auxquelles le problème de validation parent est associé. |
| [getRuleInfo()](#getRuleInfo--) | Spécifie les informations concernant la règle de validation à laquelle le problème de validation parent se rapporte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Pour la description de cette propriété, veuillez consulter [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Constructeur

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Spécifie l'identifiant unique du problème de validation.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Spécifie si le problème de validation est actuellement ignoré. La valeur par défaut est False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Selon la cible du problème de validation parent, spécifie soit la page, soit à la fois la page et la forme associées au problème de validation parent. Si la cible du problème de validation parent est un document, IssueTarget ne spécifie ni page ni forme.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Spécifie les informations concernant la règle de validation à laquelle le problème de validation parent se rapporte.

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


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Pour la description de cette propriété, veuillez consulter [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

