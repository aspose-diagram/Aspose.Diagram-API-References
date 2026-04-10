---
title: FontConfigs
second_title: Referensi API Aspose.Diagram untuk Java
description: Menentukan pengaturan font
type: docs
weight: 160
url: /id/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Menentukan pengaturan font
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | nama font default. |
| [getFontSources()](#getFontSources--) | Mendapatkan salinan array yang berisi daftar sumber |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Mengembalikan array yang berisi nama substitusi font yang akan digunakan jika font asli tidak tersedia. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Menunjukkan apakah akan menggunakan substitusi font sistem terlebih dahulu atau tidak ketika sebuah font tidak tersedia dan substitusi font tersebut belum diatur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Mengatur folder font |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Mengatur folder-folder font |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Mengatur sumber font. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Nama substitusi font untuk nama font asli yang diberikan. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Untuk deskripsi properti ini, silakan lihat [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontConfigs() {#FontConfigs--}
```
public FontConfigs()
```


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
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


nama font default.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Mendapatkan salinan array yang berisi daftar sumber

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Mengembalikan array yang berisi nama substitusi font yang akan digunakan jika font asli tidak tersedia.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Sebuah array yang berisi nama pengganti font yang akan digunakan jika font asli tidak tersedia.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Tunjukkan apakah akan menggunakan pengganti font sistem terlebih dahulu atau tidak ketika sebuah font tidak tersedia dan pengganti font tersebut belum disetel. misalnya pada Ubuntu, font "Arial" biasanya digantikan oleh "Liberation Sans". Nilai default adalah false.

**Returns:**
boolean
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




### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Mengatur folder font

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFolder | java.lang.String | Folder yang berisi font TrueType. |
| recursive | boolean | Menentukan apakah akan memindai subfolder atau tidak. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Mengatur folder-folder font

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Folder-folder yang berisi font TrueType. |
| recursive | boolean | Menentukan apakah akan memindai subfolder atau tidak. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Mengatur sumber font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Array sumber yang berisi font TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Nama substitusi font untuk nama font asli yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originalFontName | java.lang.String | Nama font asli. |
| substituteFontNames | java.lang.String[] | Daftar nama pengganti font yang akan digunakan jika font asli tidak tersedia. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

