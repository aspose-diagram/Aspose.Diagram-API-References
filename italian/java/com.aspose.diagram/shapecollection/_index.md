---
title: ShapeCollection
second_title: Riferimento API di Aspose.Diagram per Java
description: Raccolta di forme.
type: docs
weight: 356
url: /it/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Raccolta di forme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Aggiungi la forma nella collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Ottiene l'elemento all'indice specificato. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [getShape(String name)](#getShape-java.lang.String-) | Restituisce l'elemento con il nome specificato. |
| [getShape(long ID)](#getShape-long-) | Restituisce l'elemento con l'ID specificato. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Ottiene l'elemento includendo la sua forma figlia all'ID specificato. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Ottiene l'elemento includendo la sua forma figlia al nome specificato. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Raggruppa le forme. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Esiste un elemento nella collezione. |
| [iterator()](#iterator--) | Supporta un'iterazione semplice su una collezione non generica. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Remove the shape from the collection. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Remove the shapes including DEPENDSON shapes from the collection. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | UnGroup the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Aggiungi la forma nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Rimuove tutti gli elementi dalla collezione.

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
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Ottiene l'elemento all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Ottiene il numero di elementi effettivamente contenuti nella collezione.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Restituisce l'elemento con il nome specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Restituisce l'elemento con l'ID specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Ottiene l'elemento includendo la sua forma figlia all'ID specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Ottiene l'elemento includendo la sua forma figlia al nome specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | the group items. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Return the group shape.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


Esiste un elemento nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | indice dell'elemento. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Supporta un'iterazione semplice su una collezione non generica.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Shape item) {#remove-com.aspose.diagram.Shape-}
```
public void remove(Shape item)
```


Remove the shape from the collection.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Remove the shapes including DEPENDSON shapes from the collection.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unGroup(Shape groupShape) {#unGroup-com.aspose.diagram.Shape-}
```
public void unGroup(Shape groupShape)
```


UnGroup the shape.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | the group shape. |

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

