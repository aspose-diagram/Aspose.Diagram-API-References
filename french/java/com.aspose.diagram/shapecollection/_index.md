---
title: ShapeCollection
second_title: Référence API d'Aspose.Diagram pour Java
description: Collection de formes.
type: docs
weight: 356
url: /fr/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Collection de formes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Ajouter la forme dans la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Obtient l'élément à l'index spécifié. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [getShape(String name)](#getShape-java.lang.String-) | Obtient l'élément au nom spécifié. |
| [getShape(long ID)](#getShape-long-) | Obtient l'élément à l'ID spécifié. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Obtient l'élément incluant sa forme enfant à l'ID spécifié. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Obtient l'élément incluant sa forme enfant au nom spécifié. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Regrouper les formes. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existe un élément dans la collection. |
| [iterator()](#iterator--) | Prend en charge une itération simple sur une collection non générique. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Supprimer la forme de la collection. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Supprimer les formes, y compris les formes DEPENDSON, de la collection. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Dégrouper la forme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Ajouter la forme dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Supprime tous les éléments de la collection.

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
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Obtient l'élément à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
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


Obtient le nombre d'éléments réellement contenus dans la collection.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Obtient l'élément au nom spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Obtient l'élément à l'ID spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Obtient l'élément incluant sa forme enfant à l'ID spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Obtient l'élément incluant sa forme enfant au nom spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Regrouper les formes. La forme dans groupItems ne doit pas être regroupée. La forme doit être dans cette collection Shapes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | les éléments du groupe. |

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


Existe un élément dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | indice de l'élément. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Prend en charge une itération simple sur une collection non générique.

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


Supprimer la forme de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Forme |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Supprimer les formes, y compris les formes DEPENDSON, de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Forme |

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


Dégrouper la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | la forme du groupe. |

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

