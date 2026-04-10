---
title: EllipticalArcTo
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang menentukan informasi tentang busur elips.
type: docs
weight: 140
url: /id/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

Berisi elemen yang menentukan informasi tentang busur elips.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | Membuat sebuah instance dari kelas [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | Koordinat x dari titik kontrol busur. |
| [getB()](#getB--) | Koordinat y dari titik kontrol busur. |
| [getC()](#getC--) | Sudut sumbu utama busur relatif terhadap sumbu x induknya. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Rasio sumbu utama busur terhadap sumbu minornya. |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getIX()](#getIX--) | Indeks berbasis nol dari elemen dalam elemen induknya. |
| [getX()](#getX--) | Koordinat x dari simpul akhir busur elips. |
| [getY()](#getY--) | Koordinat y dari simpul akhir busur elips. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


Membuat sebuah instance dari kelas [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan mendalam dari instance ini.

**Returns:**
java.lang.Object -
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
### getA() {#getA--}
```
public DoubleValue getA()
```


Koordinat x dari titik kontrol busur. Titik kontrol paling baik ditempatkan kira-kira setengah jalan antara titik awal dan akhir busur. Jika tidak, busur dapat tumbuh menjadi ukuran yang ekstrem untuk melewati titik kontrol, dengan hasil yang tidak dapat diprediksi.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


Koordinat y dari titik kontrol busur.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


Sudut sumbu utama busur relatif terhadap sumbu x induknya.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


Rasio antara sumbu utama busur dengan sumbu minornya. Meskipun makna umum kata-kata ini, sumbu utama tidak harus lebih besar daripada sumbu minor, sehingga rasio ini tidak harus lebih besar dari 1. Menetapkan elemen ini ke nilai kurang dari atau sama dengan 0 atau lebih besar dari 1000 dapat menyebabkan hasil yang tidak dapat diprediksi.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Indeks berbasis nol dari elemen dalam elemen induknya.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


Koordinat x dari simpul akhir busur elips.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Koordinat y dari simpul akhir busur elips.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

