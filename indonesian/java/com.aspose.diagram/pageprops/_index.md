---
title: PageProps
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi sel yang mengontrol atribut halaman seperti lebar, tinggi, dan skala halaman.
type: docs
weight: 268
url: /id/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Berisi sel yang mengontrol atribut halaman, seperti lebar, tinggi, dan skala halaman.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Menentukan apakah halaman gambar secara otomatis mengubah ukuran untuk menyesuaikan diagram. |
| [getDrawingScale()](#getDrawingScale--) | Menunjukkan nilai satuan gambar dalam skala gambar saat ini. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Menentukan jenis skala gambar yang digunakan untuk sebuah halaman. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Menentukan ukuran gambar sebuah halaman. |
| [getInhibitSnap()](#getInhibitSnap--) | Menentukan apakah bentuk pada halaman latar depan menempel pada objek lain di halaman dan bentuk pada halaman latar belakang. |
| [getPageHeight()](#getPageHeight--) | Menentukan tinggi halaman dalam satuan gambar. |
| [getPageScale()](#getPageScale--) | Menentukan nilai satuan halaman default dalam skala gambar saat ini. |
| [getPageWidth()](#getPageWidth--) | Menentukan lebar halaman dalam satuan gambar. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Berisi angka yang menentukan sudut arah miring ketika tipe bayangan halaman default diterapkan. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Menentukan jarak dalam satuan halaman di mana bayangan jatuh sebuah bentuk dipindahkan secara horizontal dari bentuk tersebut. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Menentukan jarak dalam satuan halaman di mana bayangan jatuh sebuah bentuk dipindahkan secara vertikal dari bentuk tersebut. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Menentukan persentase untuk memperbesar atau memperkecil bayangan sebuah bentuk. |
| [getShdwType()](#getShdwType--) | Menunjukkan tipe bayangan default untuk sebuah halaman. |
| [getUIVisibility()](#getUIVisibility--) | Menentukan apakah nama halaman ditampilkan di antarmuka pengguna (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Menentukan apakah halaman gambar secara otomatis mengubah ukuran untuk menyesuaikan diagram.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Menunjukkan nilai satuan gambar dalam skala gambar saat ini. Skala gambar untuk halaman adalah rasio antara satuan halaman yang terdapat dalam elemen PageScale dengan satuan gambar. Satuan elemen ini menentukan satuan panjang default (DL) untuk halaman.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Menentukan jenis skala gambar yang digunakan untuk sebuah halaman.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Menentukan ukuran gambar sebuah halaman.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Menentukan apakah bentuk pada halaman latar depan menempel pada objek lain di halaman dan bentuk pada halaman latar belakang.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Menentukan tinggi halaman dalam satuan gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Menentukan nilai satuan halaman default dalam skala gambar saat ini. Skala gambar untuk halaman adalah rasio antara satuan halaman dalam elemen PageScale dengan satuan gambar yang ditampilkan dalam elemen DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Menentukan lebar halaman dalam satuan gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Berisi angka yang menentukan sudut arah miring ketika tipe bayangan halaman default diterapkan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Menentukan jarak dalam satuan halaman di mana bayangan jatuh sebuah bentuk dipindahkan secara horizontal dari bentuk tersebut.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Menentukan jarak dalam satuan halaman di mana bayangan jatuh sebuah bentuk dipindahkan secara vertikal dari bentuk tersebut.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Menentukan persentase untuk memperbesar atau memperkecil bayangan sebuah bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Menunjukkan tipe bayangan default untuk sebuah halaman.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Menentukan apakah nama halaman ditampilkan di antarmuka pengguna (UI). Nilai satu menunjukkan bahwa halaman tidak terlihat; nilai nol menunjukkan halaman terlihat.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

