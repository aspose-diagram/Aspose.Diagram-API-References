---
title: HTMLSaveOptions
second_title: Referensi API Aspose.Diagram untuk Java
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke HTML.
type: docs
weight: 187
url: /id/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke HTML.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen dalam format Aspose.Diagram.SaveFileFormat. |
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
| [getExportHiddenPage()](#getExportHiddenPage--) | Menentukan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [getPageCount()](#getPageCount--) | jumlah halaman yang akan dirender dalam HTML. |
| [getPageIndex()](#getPageIndex--) | indeks berbasis 0 dari halaman pertama yang akan dirender. |
| [getPageSize()](#getPageSize--) | ukuran halaman untuk gambar yang dihasilkan. |
| [getResolution()](#getResolution--) | resolusi untuk html yang dihasilkan, dalam dot per inci. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Menunjukkan apakah html disimpan sebagai satu file. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| [getSaveFormat()](#getSaveFormat--) | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. |
| [getSaveTitle()](#getSaveTitle--) | Menentukan apakah perlu mengekspor judul atau tidak. |
| [getSaveToolBar()](#getSaveToolBar--) | Menentukan apakah menyimpan toolbar. Nilai default adalah true. |
| [getShapes()](#getShapes--) | bentuk yang akan dirender. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider untuk mengekspor objek. |
| [getTitle()](#getTitle--) | judul diagram yang akan dirender dalam HTML. |
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
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Untuk deskripsi properti ini, silakan lihat [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Untuk deskripsi properti ini, silakan lihat [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Menentukan apakah perlu mengekspor halaman tersembunyi atau tidak. Nilai default adalah true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


jumlah halaman yang akan dirender dalam HTML. Default adalah MaxValue yang berarti semua halaman diagram akan dirender.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


indeks berbasis 0 dari halaman pertama yang akan dirender. Default adalah 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


ukuran halaman untuk gambar yang dihasilkan. Dapat berupa [PageSize](../../com.aspose.diagram/pagesize) atau null. Nilai default adalah null. Jika PageSize null maka ukuran halaman untuk gambar yang dihasilkan diambil dari diagram sumber.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


resolusi untuk html yang dihasilkan, dalam dot per inci. Properti ini hanya berpengaruh saat menyimpan ke html. Nilai default adalah 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Menunjukkan apakah html disimpan sebagai satu file. Nilai default adalah false. Jika ada beberapa halaman, halaman‑halaman tersebut dan sumber daya lainnya harus disimpan ke file terpisah. Untuk beberapa skenario, pengguna mungkin perlu mendapatkan hanya satu file hasil demi kemudahan transfer. Jika demikian, pengguna dapat mengatur properti ini menjadi true.

**Returns:**
boolean
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
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Menentukan apakah perlu mengekspor judul atau tidak. Nilai default adalah true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Menentukan apakah menyimpan toolbar. Nilai default adalah true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


bentuk yang akan dirender. Jumlah default adalah 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider untuk mengekspor objek.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


judul diagram yang akan dirender dalam HTML. Jika Title null, Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) akan digunakan sebagai Title. Jika Diagram.DocumentProperties.Title null atau kosong, nama file Diagram akan digunakan sebagai Title.

**Returns:**
java.lang.String
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Untuk deskripsi properti ini, silakan lihat [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Untuk deskripsi properti ini, silakan lihat [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Untuk deskripsi properti ini, silakan lihat [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

