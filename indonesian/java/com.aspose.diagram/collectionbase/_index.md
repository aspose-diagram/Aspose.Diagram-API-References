---
title: CollectionBase
second_title: Referensi API Aspose.Diagram untuk Java
description: Menyediakan kelas dasar abstrak untuk koleksi yang kuat tipe.
type: docs
weight: 50
url: /id/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

Menyediakan kelas dasar abstrak untuk koleksi yang kuat tipe.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | Menginisialisasi instance baru dari kelas CollectionBase dengan kapasitas awal default. |
| [CollectionBase(int capacity)](#CollectionBase-int-) | Menginisialisasi instance baru dari kelas CollectionBase dengan kapasitas yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Menambahkan item ke instance CollectionBase. |
| [clear()](#clear--) | Menghapus semua objek dari instance CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | Mengembalikan apakah instance berisi objek ini |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Mendapatkan item pada posisi yang ditentukan. |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


Menginisialisasi instance baru dari kelas CollectionBase dengan kapasitas awal default.

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


Menginisialisasi instance baru dari kelas CollectionBase dengan kapasitas yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kapasitas | int | Jumlah elemen yang dapat disimpan secara awal oleh daftar baru. |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


Mendapatkan item pada posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks posisi yang ditentukan. |

**Returns:**
java.lang.Object - Item pada posisi yang ditentukan.
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

