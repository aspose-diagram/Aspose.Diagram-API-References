---
title: ImageSaveOptions
second_title: Referensi API Aspose.Diagram untuk Java
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke gambar.
type: docs
weight: 200
url: /id/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan gambar yang dirender dalam format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, atau format Aspose.Diagram.SaveFileFormat. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Membuat objek opsi penyimpanan dari kelas yang sesuai untuk format penyimpanan yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Menentukan tingkat kualitas yang digunakan selama komposit. |
| [getContentZoom()](#getContentZoom--) | Parameter ini mirip dengan skala, tetapi tidak memengaruhi ukuran gambar yang dihasilkan. |
| [getDefaultFont()](#getDefaultFont--) | Ketika karakter dalam diagram menggunakan unicode dan tidak diatur dengan nilai font yang benar atau font tidak terpasang secara lokal, mereka dapat muncul sebagai blok dalam pdf, gambar, atau XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Pengaturan untuk merender file metafile Emf. |
| [getEnlargePage()](#getEnlargePage--) | Menentukan apakah memperbesar halaman. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Menentukan apakah perlu mengekspor bentuk panduan atau tidak. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Menentukan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [getImageBrightness()](#getImageBrightness--) | kecerahan untuk gambar yang dihasilkan. |
| [getImageColorMode()](#getImageColorMode--) | mode warna untuk gambar yang dihasilkan. |
| [getImageContrast()](#getImageContrast--) | kontras untuk gambar yang dihasilkan. |
| [getInterpolationMode()](#getInterpolationMode--) | Menentukan algoritma yang digunakan ketika gambar diubah skala atau diputar. |
| [getJpegQuality()](#getJpegQuality--) | nilai yang menentukan kualitas gambar JPEG yang dihasilkan. |
| [getPageCount()](#getPageCount--) | jumlah halaman yang akan dirender saat menyimpan ke file TIFF multipage. |
| [getPageIndex()](#getPageIndex--) | indeks berbasis 0 dari halaman pertama yang akan dirender. |
| [getPageSize()](#getPageSize--) | ukuran halaman untuk gambar yang dihasilkan. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | nilai yang menentukan bagaimana piksel di-offset selama proses rendering. |
| [getResolution()](#getResolution--) | resolusi untuk gambar yang dihasilkan, dalam dot per inci. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Menentukan apakah area penyimpanan sama dengan PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| [getSaveFormat()](#getSaveFormat--) | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. |
| [getScale()](#getScale--) | faktor zoom untuk gambar yang dihasilkan. |
| [getShapes()](#getShapes--) | bentuk yang akan dirender. |
| [getSmoothingMode()](#getSmoothingMode--) | Menentukan apakah smoothing (antialiasing) diterapkan pada garis dan kurva serta tepi area yang diisi. |
| [getTiffCompression()](#getTiffCompression--) | jenis kompresi yang diterapkan saat menyimpan gambar yang dihasilkan ke format TIFF. |
| [getWarningCallback()](#getWarningCallback--) | callback peringatan. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Menentukan apakah perlu mengekspor komentar atau tidak. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Untuk deskripsi properti ini, silakan lihat [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Untuk deskripsi properti ini, silakan lihat [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Untuk deskripsi properti ini, silakan lihat [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Untuk deskripsi properti ini, silakan lihat [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Untuk deskripsi properti ini, silakan lihat [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Untuk deskripsi properti ini, silakan lihat [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Untuk deskripsi properti ini, silakan lihat [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Untuk deskripsi properti ini, silakan lihat [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Untuk deskripsi properti ini, silakan lihat [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Untuk deskripsi properti ini, silakan lihat [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Untuk deskripsi properti ini, silakan lihat [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Untuk deskripsi properti ini, silakan lihat [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Untuk deskripsi properti ini, silakan lihat [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Untuk deskripsi properti ini, silakan lihat [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Untuk deskripsi properti ini, silakan lihat [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan gambar yang dirender dalam format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, atau format Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| saveFormat | int | Bisa berupa Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, atau Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Menentukan tingkat kualitas yang digunakan selama komposit. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Parameter ini mirip dengan skala, tetapi tidak memengaruhi ukuran gambar yang dihasilkan. Nilai default adalah 1.0. Nilai harus lebih besar dari 0.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


kecerahan untuk gambar yang dihasilkan. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah 0.5. Nilai harus berada dalam rentang antara 0 dan 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


mode warna untuk gambar yang dihasilkan. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


kontras untuk gambar yang dihasilkan. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah 0.5. Nilai harus berada dalam rentang antara 0 dan 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Menentukan algoritma yang digunakan saat gambar diubah skala atau diputar. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


nilai yang menentukan kualitas gambar JPEG yang dihasilkan. Berpengaruh hanya saat menyimpan ke JPEG. Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar yang dihasilkan saat menyimpan dalam format JPEG. Nilai dapat bervariasi dari 0 hingga 100 dimana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum. Nilai default adalah 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


jumlah halaman yang akan dirender saat menyimpan ke file TIFF multipage. Default adalah MaxValue yang berarti semua halaman diagram akan dirender.

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


nilai yang menentukan bagaimana piksel di-offset selama rendering. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


resolusi untuk gambar yang dihasilkan, dalam titik per inci. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Menentukan apakah area penyimpanan sama dengan PDF. Jika true - area yang dirender sama dengan PDF. Jika false - area yang dirender default. Nilai default adalah false.

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


Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. Bisa berupa Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, atau Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


faktor zoom untuk gambar yang dihasilkan. Nilai default adalah 1.0. Nilai harus lebih besar dari 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


bentuk yang akan dirender. Jumlah default adalah 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Menentukan apakah smoothing (antialiasing) diterapkan pada garis dan kurva serta tepi area yang diisi. Properti ini berpengaruh hanya saat menyimpan ke format gambar raster. Nilai default adalah Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


jenis kompresi yang diterapkan saat menyimpan gambar yang dihasilkan ke format TIFF. Berpengaruh hanya saat menyimpan ke TIFF. Nilai default adalah Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Untuk deskripsi properti ini, silakan lihat [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Untuk deskripsi properti ini, silakan lihat [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

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


Untuk deskripsi properti ini, silakan lihat [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Untuk deskripsi properti ini, silakan lihat [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Untuk deskripsi properti ini, silakan lihat [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Untuk deskripsi properti ini, silakan lihat [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Untuk deskripsi properti ini, silakan lihat [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Untuk deskripsi properti ini, silakan lihat [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Untuk deskripsi properti ini, silakan lihat [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Untuk deskripsi properti ini, silakan lihat [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

