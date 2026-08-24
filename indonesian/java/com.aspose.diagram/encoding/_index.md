---
title: Encoding
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili pengkodean karakter.
type: docs
weight: 143
url: /id/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

Mewakili pengkodean karakter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | Menentukan apakah objek Encoding yang ditentukan sama dengan instance saat ini. |
| [equals(Object o)](#equals-java.lang.Object-) | Menentukan apakah Object yang ditentukan sama dengan instance saat ini. |
| [getASCII()](#getASCII--) | Mendapatkan pengkodean untuk set karakter ASCII (7-bit). |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | Mendapatkan pengkodean untuk format UTF-16 menggunakan urutan byte big endian. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Mendapatkan pengkodean untuk halaman kode ANSI saat ini pada sistem operasi. |
| [getEncoding(int codePage)](#getEncoding-int-) | Mengembalikan pengkodean yang terkait dengan pengidentifikasi halaman kode yang ditentukan. |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | Mengembalikan pengkodean yang terkait dengan nama charset yang ditentukan. |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | Mengembalikan pengkodean yang terkait dengan objek charset yang ditentukan. |
| [getUTF7()](#getUTF7--) | Mendapatkan pengkodean untuk format UTF-7. |
| [getUTF8()](#getUTF8--) | Mendapatkan pengkodean untuk format UTF-8. |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | Mendapatkan pengkodean untuk format UTF-8 tanpa pengidentifikasi UTF-8. |
| [getUnicode()](#getUnicode--) | Mendapatkan pengkodean untuk format UTF-16 menggunakan urutan byte little endian. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


Menentukan apakah objek Encoding yang ditentukan sama dengan instance saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | Objek Encoding untuk dibandingkan dengan instance saat ini. |

**Returns:**
boolean - true jika nilai sama dengan instance saat ini; jika tidak, false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Menentukan apakah Object yang ditentukan sama dengan instance saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | The Object to compare with the current instance. |

**Returns:**
boolean - true if value is an instance of Encoding and is equal to the current instance; otherwise, false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


Mendapatkan pengkodean untuk set karakter ASCII (7-bit).

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


Mendapatkan pengkodean untuk format UTF-16 menggunakan urutan byte big endian.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


Mendapatkan pengkodean untuk halaman kode ANSI saat ini pada sistem operasi.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


Mengembalikan pengkodean yang terkait dengan pengidentifikasi halaman kode yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codePage | int | The code page identifier of the preferred encoding. -or- 0, to use the default encoding. |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


Mengembalikan pengkodean yang terkait dengan nama charset yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charsetName | java.lang.String | specified charset name |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


Mengembalikan pengkodean yang terkait dengan objek charset yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charset | java.nio.charset.Charset | specified charset object |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


Mendapatkan pengkodean untuk format UTF-7.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


Mendapatkan pengkodean untuk format UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


Mendapatkan pengkodean untuk format UTF-8 tanpa pengidentifikasi UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


Mendapatkan pengkodean untuk format UTF-16 menggunakan urutan byte little endian.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

