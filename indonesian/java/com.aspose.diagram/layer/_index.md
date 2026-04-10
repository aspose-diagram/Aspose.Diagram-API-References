---
title: Layer
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang mendefinisikan satu lapisan dan propertinya untuk sebuah halaman.
type: docs
weight: 212
url: /id/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Berisi elemen yang mendefinisikan satu lapisan dan propertinya untuk sebuah halaman.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Layer()](#Layer--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Menentukan apakah sebuah lapisan aktif. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Indeks warna dalam tabel warna yang digunakan untuk menampilkan lapisan atau nilai RGB yang menentukan warna khusus yang tidak ada dalam tabel warna (misalnya, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Menentukan tingkat transparansi untuk warna teks lapisan atau bentuk, dari 0 (sepenuhnya buram) hingga 1 (sepenuhnya transparan). |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getGlue()](#getGlue--) | Menentukan apakah bentuk yang termasuk dalam lapisan dapat ditempelkan. |
| [getIX()](#getIX--) | Indeks berbasis nol dari elemen dalam elemen induknya. |
| [getLock()](#getLock--) | Menentukan apakah bentuk yang termasuk dalam lapisan dikunci sehingga tidak dapat dipilih atau diedit. |
| [getName()](#getName--) | Elemen Name menentukan nama lapisan. |
| [getNameUniv()](#getNameUniv--) | Menentukan nama universal sebuah lapisan. |
| [getPrint()](#getPrint--) | Menentukan apakah bentuk yang termasuk dalam lapisan dicetak ketika gambar dicetak. |
| [getSnap()](#getSnap--) | Menentukan apakah bentuk lain dapat menempel pada bentuk yang ditetapkan ke lapisan. |
| [getStatus()](#getStatus--) | Menentukan apakah lapisan tersebut merupakan lapisan yang valid untuk sebuah dokumen. |
| [getVisible()](#getVisible--) | Menentukan apakah bentuk yang termasuk dalam lapisan terlihat pada halaman gambar. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Bendera yang menunjukkan apakah elemen telah diperiksa secara lokal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Untuk deskripsi properti ini, silakan lihat [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Konstruktor.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Menentukan apakah sebuah lapisan aktif. Bentuk yang tidak ditetapkan sebelumnya ke lapisan akan ditetapkan ke lapisan aktif ketika ditempatkan pada halaman gambar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Indeks warna dalam tabel warna yang digunakan untuk menampilkan lapisan atau nilai RGB yang menentukan warna khusus yang tidak ada dalam tabel warna (misalnya, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Menentukan tingkat transparansi untuk warna teks lapisan atau bentuk, dari 0 (sepenuhnya buram) hingga 1 (sepenuhnya transparan).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Menentukan apakah bentuk yang termasuk dalam lapisan dapat ditempelkan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Indeks berbasis nol dari elemen dalam elemen induknya.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Menentukan apakah bentuk yang termasuk dalam lapisan dikunci sehingga tidak dapat dipilih atau diedit.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Elemen Name menentukan nama lapisan.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Menentukan nama universal sebuah lapisan.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Menentukan apakah bentuk yang termasuk dalam lapisan dicetak ketika gambar dicetak.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Menentukan apakah bentuk lain dapat menempel pada bentuk yang ditetapkan ke lapisan. Bentuk yang ditetapkan ke lapisan dapat menempel pada bentuk lain, tetapi bentuk lain tidak dapat menempel pada mereka.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Menentukan apakah lapisan tersebut merupakan lapisan yang valid untuk sebuah dokumen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Menentukan apakah bentuk yang termasuk dalam lapisan terlihat pada halaman gambar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Bendera yang menunjukkan apakah elemen telah diperiksa secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut diperiksa secara lokal.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Untuk deskripsi properti ini, silakan lihat [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

