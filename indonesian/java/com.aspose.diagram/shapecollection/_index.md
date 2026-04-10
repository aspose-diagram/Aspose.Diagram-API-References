---
title: ShapeCollection
second_title: Referensi API Aspose.Diagram untuk Java
description: Koleksi Bentuk.
type: docs
weight: 356
url: /id/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

Koleksi Bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | Tambahkan bentuk ke dalam koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [getShape(String name)](#getShape-java.lang.String-) | Mendapatkan elemen dengan nama yang ditentukan. |
| [getShape(long ID)](#getShape-long-) | Mendapatkan elemen pada ID yang ditentukan. |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | Mendapatkan elemen termasuk bentuk anaknya pada id yang ditentukan. |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | Mendapatkan elemen termasuk bentuk anaknya pada nama yang ditentukan. |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | Kelompokkan bentuk-bentuk. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Apakah ada item dalam koleksi. |
| [iterator()](#iterator--) | Mendukung iterasi sederhana atas koleksi non-generic. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Hapus bentuk dari koleksi. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Hapus bentuk termasuk bentuk DEPENDSON dari koleksi. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | Batalkan pengelompokan bentuk. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


Tambahkan bentuk ke dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


Menghapus semua elemen dari koleksi.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |

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


Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi.

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


Mendapatkan elemen dengan nama yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


Mendapatkan elemen pada ID yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


Mendapatkan elemen termasuk bentuk anaknya pada id yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


Mendapatkan elemen termasuk bentuk anaknya pada nama yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Kelompokkan bentuk-bentuk. Bentuk dalam groupItems tidak boleh dikelompokkan. Bentuk harus berada dalam koleksi Shapes ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | item grup. |

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


Apakah ada item dalam koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | indeks elemen. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Mendukung iterasi sederhana atas koleksi non-generic.

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


Hapus bentuk dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Bentuk |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Hapus bentuk termasuk bentuk DEPENDSON dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Bentuk |

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


Batalkan pengelompokan bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | bentuk grup. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

