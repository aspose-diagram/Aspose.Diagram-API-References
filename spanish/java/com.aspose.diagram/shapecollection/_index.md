---
title: ShapeCollection
second_title: Referencia de API de Aspose.Diagram para Java
description: Colección de Formas.
type: docs
weight: 356
url: /es/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Colección de Formas.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Agregar la forma en la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Obtiene el elemento en el índice especificado. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [getShape(String name)](#getShape-java.lang.String-) | Obtiene el elemento con el nombre especificado. |
| [getShape(long ID)](#getShape-long-) | Obtiene el elemento con el ID especificado. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Obtiene el elemento incluyendo su forma hija en el id especificado. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Obtiene el elemento incluyendo su forma hija en el nombre especificado. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Agrupar las formas. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existe un elemento en la colección. |
| [iterator()](#iterator--) | Admite una iteración simple sobre una colección no genérica. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Eliminar la forma de la colección. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Eliminar las formas, incluyendo las formas DEPENDSON, de la colección. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Desagrupar la forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Agregar la forma en la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Elimina todos los elementos de la colección.

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
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Obtiene el elemento en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |

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


Obtiene el número de elementos realmente contenidos en la colección.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Obtiene el elemento con el nombre especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Obtiene el elemento con el ID especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Obtiene el elemento incluyendo su forma hija en el id especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Obtiene el elemento incluyendo su forma hija en el nombre especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Agrupar las formas. La forma en groupItems no debe agruparse. La forma debe estar en esta colección Shapes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | los elementos del grupo. |

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


Existe un elemento en la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | índice del elemento. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Admite una iteración simple sobre una colección no genérica.

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


Eliminar la forma de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Forma |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Eliminar las formas, incluyendo las formas DEPENDSON, de la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Forma |

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


Desagrupar la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | la forma del grupo. |

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

