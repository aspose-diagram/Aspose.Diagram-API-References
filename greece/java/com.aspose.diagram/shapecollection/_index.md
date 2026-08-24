---
title: ShapeCollection
second_title: Αναφορά API του Aspose.Diagram για Java
description: Συλλογή Σχημάτων.
type: docs
weight: 356
url: /el/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Συλλογή Σχημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Add the shape in the collection. |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getShape(String name)](#getShape-java.lang.String-) | Λαμβάνει το στοιχείο με το καθορισμένο όνομα. |
| [getShape(long ID)](#getShape-long-) | Λαμβάνει το στοιχείο με το καθορισμένο ID. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Gets the element including it's child shape at the specified id. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Gets the element including it's child shape at the specified name. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Group the shapes. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Αφαιρέστε το σχήμα από τη συλλογή. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Αφαιρέστε τα σχήματα, συμπεριλαμβανομένων των σχήματων DEPENDSON, από τη συλλογή. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Αποομαδοποιήστε το σχήμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Add the shape in the collection.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Gets the element at the specified index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |

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


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Λαμβάνει το στοιχείο με το καθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Λαμβάνει το στοιχείο με το καθορισμένο ID.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Gets the element including it's child shape at the specified id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Gets the element including it's child shape at the specified name.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Ομαδοποιήστε τα σχήματα. Το σχήμα στο groupItems δεν πρέπει να ομαδοποιηθεί. Το σχήμα πρέπει να βρίσκεται σε αυτή τη συλλογή Shapes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | τα group items. |

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


Is exist item in the collection.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | δείκτης του στοιχείου. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή.

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


Αφαιρέστε το σχήμα από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Αφαιρέστε τα σχήματα, συμπεριλαμβανομένων των σχήματων DEPENDSON, από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Αποομαδοποιήστε το σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | το group shape. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

