---
title: Hyperlink
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen untuk membuat beberapa lompatan antara shape atau halaman gambar dan halaman gambar lain, file lain, atau situs Web.
type: docs
weight: 193
url: /id/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Berisi elemen untuk membuat beberapa lompatan antara sebuah bentuk atau halaman gambar dan halaman gambar lain, file lain, atau situs Web.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Menentukan alamat URL, nama file DOS, atau jalur UNC untuk melompat ke. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Menentukan hyperlink default untuk shape atau halaman. |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getDescription()](#getDescription--) | Elemen Description berisi string teks yang menjelaskan hyperlink. |
| [getExtraInfo()](#getExtraInfo--) | Berisi informasi yang akan digunakan untuk menyelesaikan URL, seperti koordinat peta gambar. |
| [getFrame()](#getFrame--) | Berisi nama frame yang menjadi target ketika Microsoft Visio dibuka sebagai dokumen aktif dalam aplikasi kontainer. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getInvisible()](#getInvisible--) | Elemen Invisible menunjukkan apakah hyperlink muncul pada menu pintasan untuk shape atau halaman. |
| [getName()](#getName--) | Nama elemen. |
| [getNameU()](#getNameU--) | Nama universal elemen. |
| [getNewWindow()](#getNewWindow--) | Menentukan apakah Microsoft Visio membuka jendela di lokasi baru ketika mengikuti hyperlink untuk membuka halaman Web atau dokumen Visio lainnya. |
| [getSortKey()](#getSortKey--) | Elemen Invisible menunjukkan apakah hyperlink muncul pada menu pintasan untuk shape atau halaman. |
| [getSubAddress()](#getSubAddress--) | Menentukan lokasi dalam dokumen target untuk ditautkan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Menentukan alamat URL, nama file DOS, atau jalur UNC untuk melompat ke.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Menentukan hyperlink default untuk shape atau halaman.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Elemen Description berisi string teks yang menjelaskan hyperlink.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Berisi informasi yang akan digunakan untuk menyelesaikan URL, seperti koordinat peta gambar. Misalnya, x=41 y=7 akan menentukan koordinat peta gambar.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Berisi nama frame yang menjadi target ketika Microsoft Visio dibuka sebagai dokumen aktif dalam aplikasi kontainer. Nilai default adalah string kosong.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Elemen Invisible menunjukkan apakah hyperlink muncul pada menu pintasan untuk shape atau halaman.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public String getName()
```


Nama elemen.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Nama universal elemen.

**Returns:**
java.lang.String
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Menentukan apakah Microsoft Visio membuka jendela di lokasi baru ketika mengikuti hyperlink untuk membuka halaman Web atau dokumen Visio lainnya.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Elemen Invisible menunjukkan apakah hyperlink muncul pada menu pintasan untuk shape atau halaman.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Menentukan lokasi dalam dokumen target untuk ditautkan.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

