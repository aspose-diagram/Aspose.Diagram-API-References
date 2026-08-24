---
title: VbaProjectReferenceCollection
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili semua referensi proyek VBA.
type: docs
weight: 435
url: /id/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

Mewakili semua referensi proyek VBA.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Menambahkan item ke instance CollectionBase. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Tambahkan referensi ke perpustakaan tipe yang dimodifikasi dan perpustakaan tipe yang diperluas. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | Tambahkan referensi ke proyek VBA eksternal. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Tambahkan referensi ke perpustakaan tipe Otomasi. |
| [clear()](#clear--) | Menghapus semua objek dari instance CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | Mengembalikan apakah instance berisi objek ini |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | Dapatkan referensi dalam daftar berdasarkan indeks. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang terdapat dalam instance CollectionBase. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | Menentukan indeks dari item tertentu dalam instance CollectionBase. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi instance CollectionBase. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Menghapus item pada indeks yang ditentukan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


Menambahkan item ke instance CollectionBase.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | Objek yang akan ditambahkan ke instance CollectionBase. |

**Returns:**
int - Posisi dimana elemen baru disisipkan.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


Tambahkan referensi ke perpustakaan tipe yang dimodifikasi dan perpustakaan tipe yang diperluas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama referensi. |
| libid | java.lang.String | Pengidentifikasi perpustakaan tipe Otomasi. |
| twiddledlibid | java.lang.String | Pengidentifikasi perpustakaan tipe yang dimodifikasi |
| extendedLibid | java.lang.String | Pengidentifikasi dari perpustakaan tipe yang diperluas |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


Tambahkan referensi ke proyek VBA eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama referensi. |
| absoluteLibid | java.lang.String | Pengidentifikasi proyek VBA\u9225\u6a9a yang direferensikan dengan jalur absolut. |
| relativeLibid | java.lang.String | Pengidentifikasi proyek VBA\u9225\u6a9a yang direferensikan dengan jalur relatif. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Tambahkan referensi ke perpustakaan tipe Otomasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama referensi. |
| libid | java.lang.String | Pengidentifikasi perpustakaan tipe Otomasi. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Menghapus semua objek dari instance CollectionBase.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


Mengembalikan apakah instance berisi objek ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | objek tes |

**Returns:**
boolean - Apakah instance berisi objek ini
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


Dapatkan referensi dalam daftar berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | int | Indeks. |

**Returns:**
[VbaProjectReference](../../com.aspose.diagram/vbaprojectreference) - 
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


Mendapatkan jumlah elemen yang terdapat dalam instance CollectionBase.

**Returns:**
int - Jumlah elemen yang terdapat dalam instance CollectionBase.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```


Menentukan indeks dari item tertentu dalam instance CollectionBase.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | Menentukan indeks dari item tertentu dalam instance CollectionBase. |

**Returns:**
int - Indeks nilai jika ditemukan dalam daftar; jika tidak, -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


Mengembalikan enumerator yang mengiterasi instance CollectionBase.

**Returns:**
java.util.Iterator - Iterator untuk instance CollectionBase.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Menghapus item pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks berbasis nol dari item yang akan dihapus. |

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

