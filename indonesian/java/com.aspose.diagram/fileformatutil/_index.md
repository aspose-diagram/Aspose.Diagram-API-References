---
title: FileFormatUtil
second_title: Referensi API Aspose.Diagram untuk Java
description: Menyediakan metode utilitas untuk mengonversi enum format file menjadi string atau ekstensi file dan sebaliknya.
type: docs
weight: 152
url: /id/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

Menyediakan metode utilitas untuk mengonversi enum format file menjadi string atau ekstensi file dan sebaliknya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | Mendeteksi dan mengembalikan informasi tentang format Visio yang disimpan dalam aliran. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | Mendeteksi dan mengembalikan informasi tentang format Visio yang disimpan dalam berkas. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


Mendeteksi dan mengembalikan informasi tentang format Visio yang disimpan dalam aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


Mendeteksi dan mengembalikan informasi tentang format Visio yang disimpan dalam berkas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
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

