---
title: Issue
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta un singolo problema di convalida nel documento.
type: docs
weight: 208
url: /it/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Rappresenta un singolo problema di convalida nel documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Issue()](#Issue--) | Costruttore |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Specifica l'identificatore univoco del problema di convalida. |
| [getIgnored()](#getIgnored--) | Specifica se il problema di convalida è attualmente ignorato. |
| [getIssueTarget()](#getIssueTarget--) | A seconda dell'obiettivo del problema di convalida padre, specifica la pagina o sia la pagina che la forma a cui il problema di convalida padre è associato. |
| [getRuleInfo()](#getRuleInfo--) | Specifica le informazioni sulla regola di convalida a cui si riferisce il problema di convalida padre. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/issue\\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Per la descrizione di questa proprietà, consultare [getIgnored()](../../com.aspose.diagram/issue\\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Costruttore

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Specifica l'identificatore univoco del problema di convalida.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Specifica se il problema di convalida è attualmente ignorato. Il valore predefinito è False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


A seconda del target del problema di validazione padre, specifica la pagina o sia la pagina che la forma a cui il problema di validazione padre è associato. Se il target del problema di validazione padre è un documento, IssueTarget non specifica né una pagina né una forma.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Specifica le informazioni sulla regola di convalida a cui si riferisce il problema di convalida padre.

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


Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/issue\\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Per la descrizione di questa proprietà, consultare [getIgnored()](../../com.aspose.diagram/issue\\#getIgnored--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

