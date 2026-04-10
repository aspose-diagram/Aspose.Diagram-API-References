---
title: PdfSaveOptions
second_title: Referensi API Aspose.Diagram untuk Java
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke PDF.
type: docs
weight: 281
url: /id/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke PDF.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen dalam format Aspose.Diagram.SaveFileFormat. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Membuat objek opsi penyimpanan dari kelas yang sesuai untuk format penyimpanan yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. |
| [getDefaultFont()](#getDefaultFont--) | Ketika karakter dalam diagram menggunakan unicode dan tidak diatur dengan nilai font yang benar atau font tidak terpasang secara lokal, mereka dapat muncul sebagai blok dalam pdf, gambar, atau XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Pengaturan untuk merender file metafile Emf. |
| [getEncryptionDetails()](#getEncryptionDetails--) | detail enkripsi. |
| [getEnlargePage()](#getEnlargePage--) | Menentukan apakah memperbesar halaman. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Menentukan apakah perlu mengekspor bentuk panduan atau tidak. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Menentukan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [getHorizontalResolution()](#getHorizontalResolution--) | resolusi horizontal untuk gambar yang dihasilkan, dalam dot per inci. |
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas kompresi JPEG untuk gambar (jika kompresi JPEG digunakan). |
| [getPageCount()](#getPageCount--) | jumlah halaman yang akan dirender dalam PDF. |
| [getPageIndex()](#getPageIndex--) | indeks berbasis 0 dari halaman pertama yang akan dirender. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Mengontrol/menunjukkan kemajuan proses penyimpanan halaman. |
| [getPageSize()](#getPageSize--) | ukuran halaman untuk gambar yang dihasilkan. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| [getSaveFormat()](#getSaveFormat--) | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. |
| [getShapes()](#getShapes--) | bentuk yang akan dirender. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Menentukan apakah diagram dibagi menjadi beberapa halaman sesuai pengaturan halaman. |
| [getTextCompression()](#getTextCompression--) | Menentukan jenis kompresi yang akan digunakan untuk semua aliran konten kecuali gambar. |
| [getVerticalResolution()](#getVerticalResolution--) | resolusi vertikal untuk gambar yang dihasilkan, dalam dot per inci. |
| [getWarningCallback()](#getWarningCallback--) | callback peringatan. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Menentukan apakah perlu mengekspor komentar atau tidak. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Untuk deskripsi properti ini, silakan lihat [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Untuk deskripsi properti ini, silakan lihat [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Untuk deskripsi properti ini, silakan lihat [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Untuk deskripsi properti ini, silakan lihat [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Untuk deskripsi properti ini, silakan lihat [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Untuk deskripsi properti ini, silakan lihat [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Untuk deskripsi properti ini, silakan lihat [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Untuk deskripsi properti ini, silakan lihat [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Untuk deskripsi properti ini, silakan lihat [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Default adalah PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


detail enkripsi. Jika tidak disetel, maka tidak ada enkripsi yang akan dilakukan.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


resolusi horizontal untuk gambar yang dihasilkan, dalam dot per inci. Berlaku untuk metode pembuatan gambar kecuali gambar format Emf. Nilai default adalah 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Menentukan kualitas kompresi JPEG untuk gambar (jika kompresi JPEG digunakan). Default adalah 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


jumlah halaman yang akan dirender dalam PDF. Default adalah MaxValue yang berarti semua halaman diagram akan dirender.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


indeks berbasis 0 dari halaman pertama yang akan dirender. Default adalah 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Mengontrol/menunjukkan kemajuan proses penyimpanan halaman.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


ukuran halaman untuk gambar yang dihasilkan. Dapat berupa [PageSize](../../com.aspose.diagram/pagesize) atau null. Nilai default adalah null. Jika PageSize null maka ukuran halaman untuk gambar yang dihasilkan diambil dari diagram sumber.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


bentuk yang akan dirender. Jumlah default adalah 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Menentukan apakah diagram dibagi menjadi beberapa halaman sesuai pengaturan halaman. Nilai default adalah false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Menentukan jenis kompresi yang akan digunakan untuk semua aliran konten kecuali gambar. Defaultnya adalah PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Resolusi vertikal untuk gambar yang dihasilkan, dalam dot per inci. Berlaku untuk metode pembuatan gambar kecuali gambar format Emf. Nilai defaultnya adalah 96.

**Returns:**
int
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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Untuk deskripsi properti ini, silakan lihat [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Untuk deskripsi properti ini, silakan lihat [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Untuk deskripsi properti ini, silakan lihat [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Untuk deskripsi properti ini, silakan lihat [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Untuk deskripsi properti ini, silakan lihat [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Untuk deskripsi properti ini, silakan lihat [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Untuk deskripsi properti ini, silakan lihat [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

