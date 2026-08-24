---
title: RenderingSaveOptions
second_title: Referensi API Aspose.Diagram untuk Java
description: Ini adalah kelas dasar abstrak untuk kelas-kelas yang memungkinkan pengguna menentukan opsi tambahan saat menyimpan diagram ke dalam format tertentu.
type: docs
weight: 327
url: /id/java/com.aspose.diagram/renderingsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public abstract class RenderingSaveOptions extends SaveOptions
```

Ini adalah kelas dasar abstrak untuk kelas-kelas yang memungkinkan pengguna menentukan opsi tambahan saat menyimpan diagram ke dalam format tertentu.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Membuat objek opsi penyimpanan dari kelas yang sesuai untuk format penyimpanan yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Ketika karakter dalam diagram menggunakan unicode dan tidak diatur dengan nilai font yang benar atau font tidak terpasang secara lokal, mereka dapat muncul sebagai blok dalam pdf, gambar, atau XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Pengaturan untuk merender file metafile Emf. |
| [getEnlargePage()](#getEnlargePage--) | Menentukan apakah memperbesar halaman. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Menentukan apakah perlu mengekspor bentuk panduan atau tidak. |
| [getPageSize()](#getPageSize--) | ukuran halaman untuk gambar yang dihasilkan. |
| [getSaveFormat()](#getSaveFormat--) | Menentukan format di mana dokumen akan disimpan jika objek opsi penyimpanan ini digunakan. |
| [getShapes()](#getShapes--) | bentuk yang akan dirender. |
| [getWarningCallback()](#getWarningCallback--) | callback peringatan. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Menentukan apakah perlu mengekspor komentar atau tidak. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Untuk deskripsi properti ini, silakan lihat [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Untuk deskripsi properti ini, silakan lihat [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Pengaturan untuk merender file metafile Emf. File metafile EMF yang diidentifikasi sebagai "EMF+ Dual" dapat berisi baik rekaman EMF+ maupun rekaman EMF. Kedua jenis rekaman dapat digunakan untuk merender gambar, hanya rekaman EMF+, atau hanya rekaman EMF. Ketika EmfPlusPrefer diatur, maka rekaman EMF+ akan diparsing, jika tidak hanya rekaman EMF yang akan diparsing. Nilai default adalah EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Menentukan apakah memperbesar halaman. Jika true - memperbesar halaman. Jika false - tidak memperbesar halaman. Nilai default adalah true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Menentukan apakah perlu mengekspor bentuk panduan atau tidak. Nilai default adalah true.

**Returns:**
boolean
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


ukuran halaman untuk gambar yang dihasilkan. Dapat berupa [PageSize](../../com.aspose.diagram/pagesize) atau null. Nilai default adalah null. Jika PageSize null maka ukuran halaman untuk gambar yang dihasilkan diambil dari diagram sumber.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Menentukan format di mana dokumen akan disimpan jika objek opsi penyimpanan ini digunakan.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


bentuk yang akan dirender. Jumlah default adalah 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Menentukan apakah perlu mengekspor komentar atau tidak. Nilai default adalah false.

**Returns:**
boolean
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

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Untuk deskripsi properti ini, silakan lihat [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

