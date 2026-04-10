---
title: InterpolationMode
second_title: Referensi API Aspose.Diagram untuk Java
description: Enumerasi InterpolationMode menentukan algoritma yang digunakan saat gambar diskalakan atau diputar.
type: docs
weight: 206
url: /id/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

Enumerasi InterpolationMode menentukan algoritma yang digunakan saat gambar diskalakan atau diputar.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BICUBIC](#BICUBIC) | Menentukan interpolasi bikubik. |
| [BILINEAR](#BILINEAR) | Menentukan interpolasi bilinear. |
| [DEFAULT](#DEFAULT) | Menentukan mode default. |
| [HIGH](#HIGH) | Menentukan interpolasi berkualitas tinggi. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Menentukan interpolasi bikubik berkualitas tinggi. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Menentukan interpolasi bilinear berkualitas tinggi. |
| [INVALID](#INVALID) | Setara dengan elemen Invalid dari enumerasi QualityMode. |
| [LOW](#LOW) | Menentukan interpolasi kualitas rendah. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Menentukan interpolasi tetangga terdekat. |
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
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


Menentukan interpolasi bikubik. Tidak ada prefiltering yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 25 persen dari ukuran aslinya.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Menentukan interpolasi bilinear. Tidak ada prefiltering yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 50 persen dari ukuran aslinya.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Menentukan mode default.

### HIGH {#HIGH}
```
public static final int HIGH
```


Menentukan interpolasi berkualitas tinggi.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Menentukan interpolasi bikubik berkualitas tinggi. Prefiltering dilakukan untuk memastikan pengecilan berkualitas tinggi. Mode ini menghasilkan gambar yang diubah dengan kualitas tertinggi.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Menentukan interpolasi bilinear berkualitas tinggi. Prefiltering dilakukan untuk memastikan pengecilan berkualitas tinggi.

### INVALID {#INVALID}
```
public static final int INVALID
```


Setara dengan elemen Invalid dari enumerasi QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Menentukan interpolasi kualitas rendah.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Menentukan interpolasi tetangga terdekat.

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

