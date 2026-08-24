---
title: Issue
second_title: Referencia de API de Aspose.Diagram para Java
description: Representa un único problema de validación en el documento.
type: docs
weight: 208
url: /es/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Representa un único problema de validación en el documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Issue()](#Issue--) | Constructor |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Especifica el identificador único del problema de validación. |
| [getIgnored()](#getIgnored--) | Especifica si el problema de validación está actualmente ignorado. |
| [getIssueTarget()](#getIssueTarget--) | Según el objetivo del problema de validación principal, especifica ya sea la página, o tanto la página como la forma, con la que está asociado el problema de validación principal. |
| [getRuleInfo()](#getRuleInfo--) | Especifica información sobre la regla de validación a la que se refiere el problema de validación principal. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Para la descripción de esta propiedad, consulte [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
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
| Parámetro | Tipo | Descripción |
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


Especifica el identificador único del problema de validación.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Especifica si el problema de validación está actualmente ignorado. El valor predeterminado es False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Dependiendo del objetivo del problema de validación principal, especifica ya sea la página o tanto la página como la forma con la que está asociado el problema de validación principal. Si el objetivo del problema de validación principal es un documento, IssueTarget no especifica ni una página ni una forma.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Especifica información sobre la regla de validación a la que se refiere el problema de validación principal.

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


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Para la descripción de esta propiedad, consulte [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

