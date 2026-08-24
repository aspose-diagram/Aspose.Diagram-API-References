---
title: XAMLSaveOptions
second_title: Referensi API Aspose.Diagram untuk Java
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke XAML.
type: docs
weight: 448
url: /id/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke XAML.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen dalam format Aspose.Diagram.SaveFileFormat. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Membuat objek opsi penyimpanan dari kelas yang sesuai untuk format penyimpanan yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Ketika karakter dalam diagram menggunakan unicode dan tidak diatur dengan nilai font yang benar atau font tidak terpasang secara lokal, mereka dapat muncul sebagai blok dalam pdf, gambar, atau XPS. |
| [getPageCount()](#getPageCount--) | jumlah halaman yang akan dirender dalam XAML. |
| [getPageIndex()](#getPageIndex--) | indeks berbasis 0 dari halaman pertama yang akan dirender. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| [getSaveFormat()](#getSaveFormat--) | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider untuk mengekspor objek. |
| [getWarningCallback()](#getWarningCallback--) | callback peringatan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Untuk deskripsi properti ini, silakan lihat [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
```


Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen dalam format Aspose.Diagram.SaveFileFormat.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Membuat objek opsi penyimpanan dari kelas yang sesuai untuk format penyimpanan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| saveFormat | int | Aspose.Diagram.SaveFileFormat yang digunakan untuk membuat objek opsi penyimpanan. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Ketika karakter dalam diagram berupa unicode dan tidak diatur dengan nilai font yang benar atau font tidak terpasang secara lokal, mereka dapat muncul sebagai blok dalam pdf, gambar, atau XPS. Atur DefaultFont seperti MingLiu atau MS Gothic untuk menampilkan karakter tersebut.

**Returns:**
java.lang.String
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


jumlah halaman yang akan dirender dalam XAML. Default adalah MaxValue yang berarti semua halaman diagram akan dirender.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


indeks berbasis 0 dari halaman pertama yang akan dirender. Default adalah 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. Jika true – hanya halaman latar depan yang dirender (dengan latar belakang jika ada). Jika false – halaman latar depan dirender (dengan latar belakang jika ada) kemudian halaman latar belakang kosong. Hanya dapat mengembalikan true ketika PageCount > 1. Nilai default adalah false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. Hanya dapat berupa Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider untuk mengekspor objek.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


callback peringatan.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Untuk deskripsi properti ini, silakan lihat [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Untuk deskripsi properti ini, silakan lihat [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

