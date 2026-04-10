---
title: PdfPermissions
second_title: Referensi API Aspose.Diagram untuk Java
description: Menentukan izin pengguna untuk dokumen PDF.
type: docs
weight: 280
url: /id/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Menentukan izin pengguna untuk dokumen PDF.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Mengizinkan semua operasi pada dokumen PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | Mengizinkan penyalinan atau ekstraksi teks dan grafik dari dokumen, termasuk ekstraksi untuk tujuan aksesibilitas. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Mengizinkan ekstraksi teks dan grafik untuk mendukung aksesibilitas bagi pengguna disabilitas atau untuk tujuan lain. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Melarang semua operasi pada dokumen PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Mengizinkan penyusunan dokumen: menyisipkan, memutar, atau menghapus halaman serta membuat elemen navigasi seperti bookmark atau gambar mini. |
| [FILL_IN](#FILL-IN) | Mengizinkan mengisi formulir dan menandatangani dokumen. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Mengizinkan pencetakan dokumen dengan resolusi tertinggi yang memungkinkan.Saat menggunakan enkripsi RC4 40-bit, opsi ini diabaikan dan pencetakan resolusi tinggi diizinkan ketika Printing diatur. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Mengizinkan penambahan atau modifikasi anotasi teks. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Mengizinkan memodifikasi isi dokumen\\u9225\\u6a9a. |
| [PRINTING](#PRINTING) | Mengizinkan pencetakan dokumen. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Mengizinkan semua operasi pada dokumen PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Mengizinkan penyalinan atau ekstraksi teks dan grafik dari dokumen, termasuk ekstraksi untuk tujuan aksesibilitas.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Mengizinkan mengekstrak teks dan grafik untuk mendukung aksesibilitas bagi pengguna disabilitas atau untuk tujuan lain. Saat menggunakan enkripsi RC4 40-bit, opsi ini diabaikan dan aksesibilitas diizinkan kapan pun ContentCopy diatur.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Melarang semua operasi pada dokumen PDF. Ini adalah nilai default.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Mengizinkan perakitan dokumen: menyisipkan, memutar, atau menghapus halaman serta membuat elemen navigasi seperti bookmark atau gambar mini. Saat menggunakan enkripsi RC4 40-bit, opsi ini diabaikan dan perakitan dokumen diizinkan ketika ModifyContents diatur.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Mengizinkan mengisi formulir dan menandatangani dokumen. Saat menggunakan enkripsi RC4 40-bit, opsi ini diabaikan dan pengisian formulir diizinkan kapan pun ModifyAnnotations diatur.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Mengizinkan pencetakan dokumen dengan resolusi tertinggi yang memungkinkan.Saat menggunakan enkripsi RC4 40-bit, opsi ini diabaikan dan pencetakan resolusi tinggi diizinkan ketika Printing diatur.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Mengizinkan penambahan atau modifikasi anotasi teks. Saat menggunakan enkripsi RC4 40-bit, opsi ini juga mengizinkan pengisian bidang formulir.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Mengizinkan memodifikasi isi dokumen\\u9225\\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Mengizinkan pencetakan dokumen.

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

