---
title: IssueTarget
second_title: Référence API d'Aspose.Diagram pour Java
description: Selon la cible du problème de validation parent, spécifie soit la page, soit à la fois la page et la forme associées au problème de validation parent.
type: docs
weight: 210
url: /fr/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

Selon la cible du problème de validation parent, spécifie soit la page, soit à la fois la page et la forme associées au problème de validation parent. Si la cible du problème de validation parent est un document, IssueTarget ne spécifie ni page ni forme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Spécifie l'identifiant unique de la page associée au problème de validation parent. |
| [getShapeId()](#getShapeId--) | Spécifie l'identifiant unique de la forme associée au problème de validation parent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Pour la description de cette propriété, veuillez consulter [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Pour la description de cette propriété, veuillez consulter [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


Spécifie l'identifiant unique de la page associée au problème de validation parent. Si la cible est le document, la valeur PageID peut être 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Spécifie l'identifiant unique de la forme associée au problème de validation parent. Si la cible est le document ou une page, la valeur ShapeID peut être 0xFFFFFFFF.

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


Pour la description de cette propriété, veuillez consulter [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Pour la description de cette propriété, veuillez consulter [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

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

