---
title: Perlindungan
second_title: Referensi API Aspose.Diagram untuk Java
description: Penguncian membantu mencegah perubahan tidak sengaja pada bentuk tetapi tidak mencegah Microsoft Visio mengatur ulang nilai dalam keadaan lain.
type: docs
weight: 312
url: /id/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Penguncian membantu mencegah perubahan tidak sengaja pada bentuk tetapi tidak mencegah Microsoft Visio mengatur ulang nilai dalam keadaan lain. Ini juga tidak melindungi dari perubahan yang dibuat di jendela ShapeSheet.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getLockAspect()](#getLockAspect--) | Menentukan apakah rasio aspek bentuk terkunci. |
| [getLockBegin()](#getLockBegin--) | Menentukan apakah titik awal bentuk 1-D terkunci pada lokasi tertentu. |
| [getLockCalcWH()](#getLockCalcWH--) | Menentukan apakah persegi pilihan bentuk terkunci sehingga tidak dapat dihitung ulang ketika sebuah simpul diedit atau tipe elemen diubah dalam elemen Geom. |
| [getLockCrop()](#getLockCrop--) | Menentukan apakah objek asing terkunci agar tidak dapat dipotong dengan alat Crop di Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Menentukan apakah pengguna dapat menambah, menghapus, atau memodifikasi properti khusus di antarmuka pengguna (UI) dengan menggunakan kotak dialog Define Custom Properties. |
| [getLockDelete()](#getLockDelete--) | Menentukan apakah bentuk terkunci agar tidak dapat dihapus. |
| [getLockEnd()](#getLockEnd--) | Menentukan apakah titik akhir bentuk 1-D terkunci pada lokasi tertentu. |
| [getLockFormat()](#getLockFormat--) | Menentukan apakah pemformatan bentuk terkunci sehingga tidak dapat diubah. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Mengizinkan subshape untuk memblokir perubahan pemformatan yang diterapkan pada shape grup induk di antarmuka pengguna Visio dan yang sebaliknya akan menyebar ke shape grup individu. |
| [getLockGroup()](#getLockGroup--) | Menentukan apakah grup terkunci sehingga tidak dapat dibongkar. |
| [getLockHeight()](#getLockHeight--) | Menentukan apakah tinggi bentuk terkunci. |
| [getLockMoveX()](#getLockMoveX--) | Menentukan apakah posisi horizontal bentuk terkunci sehingga tidak dapat dipindahkan secara horizontal. |
| [getLockMoveY()](#getLockMoveY--) | Menentukan apakah posisi vertikal bentuk terkunci sehingga tidak dapat dipindahkan secara vertikal. |
| [getLockRotate()](#getLockRotate--) | Menentukan apakah bentuk terkunci agar tidak dapat diputar dengan alat Rotation atau perintah Rotate Left atau Rotate Right di Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Menentukan apakah persegi pilihan bentuk terkunci sehingga tidak dapat dihitung ulang ketika sebuah simpul diedit atau tipe elemen diubah dalam elemen Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Menentukan apakah teks bentuk terkunci sehingga tidak dapat diedit. |
| [getLockThemeColors()](#getLockThemeColors--) | Mencegah pengguna menerapkan warna tema pada bentuk. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Mencegah pengguna menerapkan efek tema pada bentuk. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Menentukan apakah titik-titik sudut sebuah bentuk terkunci sehingga tidak dapat diedit dengan alat apa pun pada bilah alat. |
| [getLockWidth()](#getLockWidth--) | Menentukan apakah lebar bentuk terkunci sehingga tetap tidak berubah ketika bentuk diubah ukurannya. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/protection\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Menentukan apakah rasio aspek bentuk terkunci. Jika terkunci, bentuk hanya dapat diubah ukurannya secara proporsional; tidak dapat diubah ukurannya dalam satu dimensi.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Menentukan apakah titik awal bentuk 1-D terkunci pada lokasi tertentu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Menentukan apakah persegi pilihan bentuk terkunci sehingga tidak dapat dihitung ulang ketika sebuah simpul diedit atau tipe elemen diubah dalam elemen Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Menentukan apakah objek asing terkunci agar tidak dapat dipotong dengan alat Crop di Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Menentukan apakah pengguna dapat menambah, menghapus, atau memodifikasi properti khusus di antarmuka pengguna (UI) dengan menggunakan kotak dialog Define Custom Properties.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Menentukan apakah bentuk terkunci agar tidak dapat dihapus.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Menentukan apakah titik akhir bentuk 1-D terkunci pada lokasi tertentu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Menentukan apakah pemformatan sebuah bentuk terkunci sehingga tidak dapat diubah. Secara khusus, elemen ini melindungi dari perubahan teks, garis, dan pemformatan isi, atau mengubah elemen Style yang diwarisi oleh bentuk.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Mengizinkan subshape untuk memblokir perubahan pemformatan yang diterapkan pada shape grup induk di antarmuka pengguna Visio dan yang sebaliknya akan menyebar ke shape grup individu.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Menentukan apakah grup terkunci sehingga tidak dapat dibongkar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Menentukan apakah tinggi bentuk terkunci. Jika terkunci, tinggi bentuk tetap tidak berubah ketika bentuk diubah ukurannya.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Menentukan apakah posisi horizontal bentuk terkunci sehingga tidak dapat dipindahkan secara horizontal.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Menentukan apakah posisi vertikal bentuk terkunci sehingga tidak dapat dipindahkan secara vertikal.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Menentukan apakah bentuk terkunci agar tidak dapat diputar dengan alat Rotation atau perintah Rotate Left atau Rotate Right di Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Menentukan apakah persegi pilihan bentuk terkunci sehingga tidak dapat dihitung ulang ketika sebuah simpul diedit atau tipe elemen diubah dalam elemen Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Menentukan apakah teks sebuah bentuk terkunci sehingga tidak dapat diedit. Namun, teks masih dapat diformat dengan menerapkan gaya, menggunakan opsi Style pada tab Font di kotak dialog Teks.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Mencegah pengguna menerapkan warna tema pada bentuk.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Mencegah pengguna menerapkan efek tema pada bentuk.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Menentukan apakah titik-titik sudut sebuah bentuk terkunci sehingga tidak dapat diedit dengan alat apa pun pada bilah alat.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Menentukan apakah lebar bentuk terkunci sehingga tetap tidak berubah ketika bentuk diubah ukurannya.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/protection\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

