---
title: Geom
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang menentukan koordinat titik sudut untuk garis dan busur yang membentuk bentuk.
type: docs
weight: 169
url: /id/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Berisi elemen yang menentukan koordinat titik sudut untuk garis dan busur yang membentuk bentuk. Jika bentuk memiliki lebih dari satu jalur, terdapat elemen Geom untuk setiap jalur.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Geom()](#Geom--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Koleksi koordinat. |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getIX()](#getIX--) | Indeks berbasis nol dari elemen dalam elemen induknya. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Mengembalikan nilai IX untuk anggota koleksi koordinat bentuk berikutnya. |
| [getNoFill()](#getNoFill--) | Menentukan apakah jalur dapat diisi. |
| [getNoLine()](#getNoLine--) | Menentukan apakah garis digambar di sekitar batas jalur. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Menentukan apakah bentuk dapat dipilih atau diseret ketika pengguna mengklik area terisi yang didefinisikan oleh bagian Geometri. |
| [getNoShow()](#getNoShow--) | Menentukan apakah jalur ditampilkan pada halaman gambar. |
| [getNoSnap()](#getNoSnap--) | Menentukan apakah bentuk lain menempel pada jalur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan mendalam dari instance ini.

**Returns:**
java.lang.Object -
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Koleksi koordinat. Ini menunjukkan urutan koordinat.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Indeks berbasis nol dari elemen dalam elemen induknya.

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Mengembalikan nilai IX untuk anggota koleksi koordinat bentuk berikutnya.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Menentukan apakah jalur dapat diisi.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Menentukan apakah garis digambar di sekitar batas jalur.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Menentukan apakah bentuk dapat dipilih atau diseret ketika pengguna mengklik area terisi yang didefinisikan oleh bagian Geometri.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Menentukan apakah jalur ditampilkan pada halaman gambar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Menentukan apakah bentuk lain menempel pada jalur.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


For the description of this property, please see [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


For the description of this property, please see [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


For the description of this property, please see [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


For the description of this property, please see [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


For the description of this property, please see [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

