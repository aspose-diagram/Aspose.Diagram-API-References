---
title: IssueTarget
second_title: Riferimento API di Aspose.Diagram per Java
description: A seconda del target del problema di validazione padre, specifica o la pagina o sia la pagina che la forma a cui il problema di validazione padre è associato.
type: docs
weight: 210
url: /it/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

A seconda del target del problema di validazione padre, specifica la pagina o sia la pagina che la forma a cui il problema di validazione padre è associato. Se il target del problema di validazione padre è un documento, IssueTarget non specifica né una pagina né una forma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Specifica l'identificatore univoco della pagina associata al problema di validazione padre. |
| [getShapeId()](#getShapeId--) | Specifica l'identificatore univoco della forma associata al problema di validazione padre. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Per la descrizione di questa proprietà, consultare [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Per la descrizione di questa proprietà, consultare [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


Specifica l'identificatore univoco della pagina associata al problema di validazione padre. Se il target è il documento, il valore PageID può essere 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Specifica l'identificatore univoco della forma associata al problema di validazione padre. Se il target è il documento o una pagina, il valore ShapeID può essere 0xFFFFFFFF.

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


Per la descrizione di questa proprietà, consultare [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Per la descrizione di questa proprietà, consultare [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

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

