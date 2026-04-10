---
title: Fill
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi nilai pemformatan isi saat ini untuk bentuk dan bayangan jatuh bentuk termasuk warna latar depan pola dan warna latar belakang.
type: docs
weight: 153
url: /id/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

Berisi nilai format pengisian saat ini untuk bentuk dan bayangan jatuh bentuk, termasuk pola, warna latar depan, dan warna latar belakang.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getFillBkgnd()](#getFillBkgnd--) | Menentukan warna yang digunakan untuk latar belakang pola isi bentuk. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | Menentukan tingkat transparansi untuk warna latar belakang (isi) pola isi bentuk, dari 0 (sepenuhnya tidak tembus) hingga 1 (sepenuhnya tembus). |
| [getFillForegnd()](#getFillForegnd--) | Menentukan warna yang digunakan untuk latar depan (garis) pola isi bentuk. |
| [getFillForegndTrans()](#getFillForegndTrans--) | Menentukan tingkat transparansi untuk warna latar depan (isi) pola isi bentuk, dari 0 (sepenuhnya tidak tembus) hingga 1 (sepenuhnya tembus). |
| [getFillPattern()](#getFillPattern--) | Menentukan pola isi untuk bentuk. |
| [getGradientFill()](#getGradientFill--) | Berisi nilai pemformatan isi gradien saat ini untuk bentuk |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | Menentukan ukuran keburaman bayangan sebuah bentuk. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | Menentukan sudut arah miring bayangan bentuk. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | Menentukan jarak dalam satuan halaman dimana bayangan bentuk dipindahkan secara horizontal dari bentuk. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | Menentukan jarak dalam satuan halaman dimana bayangan bentuk dipindahkan secara vertikal dari bentuk. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | Menentukan persentase di mana bayangan bentuk dapat diperbesar atau diperkecil. |
| [getShapeShdwShow()](#getShapeShdwShow--) | Menentukan jenis bayangan untuk sebuah bentuk. |
| [getShapeShdwType()](#getShapeShdwType--) | Menentukan jenis bayangan untuk sebuah bentuk. |
| [getShdwBkgnd()](#getShdwBkgnd--) | Menentukan warna yang digunakan untuk latar belakang (isi) pola isi bayangan jatuh bentuk. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | Menentukan tingkat transparansi untuk latar belakang (isi) pola isi bayangan jatuh bentuk, dari 0.0 (sepenuhnya tidak tembus) hingga 1.0 (sepenuhnya tembus). |
| [getShdwForegnd()](#getShdwForegnd--) | Menentukan warna yang digunakan untuk latar depan (garis) pola isi bayangan jatuh bentuk. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | Menentukan tingkat transparansi untuk latar depan (garis) pola isi bayangan jatuh bentuk, dari 0.0 (sepenuhnya tidak tembus) hingga 1.0 (sepenuhnya tembus). |
| [getShdwPattern()](#getShdwPattern--) | Menentukan pola isi untuk bayangan bentuk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | Untuk deskripsi properti ini, silakan lihat [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | Untuk deskripsi properti ini, silakan lihat [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | Untuk deskripsi properti ini, silakan lihat [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | Untuk deskripsi properti ini, silakan lihat [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | Untuk deskripsi properti ini, silakan lihat [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | Untuk deskripsi properti ini, silakan lihat [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | Untuk deskripsi properti ini, silakan lihat [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


Menentukan warna yang digunakan untuk latar belakang pola isi bentuk.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


Menentukan tingkat transparansi untuk warna latar belakang (isi) pola isi bentuk, dari 0 (sepenuhnya tidak tembus) hingga 1 (sepenuhnya tembus).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


Menentukan warna yang digunakan untuk latar depan (garis) pola isi bentuk.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


Menentukan tingkat transparansi untuk warna latar depan (isi) pola isi bentuk, dari 0 (sepenuhnya tidak tembus) hingga 1 (sepenuhnya tembus).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


Menentukan pola isi untuk bentuk.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Berisi nilai pemformatan isi gradien saat ini untuk bentuk

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


Menentukan ukuran blur bayangan pada sebuah bentuk. Tidak dapat menggambar blur saat ini, tetapi dapat mengurai dari vsdx sekarang.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


Menentukan sudut arah miring bayangan bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


Menentukan jarak dalam satuan halaman dimana bayangan bentuk dipindahkan secara horizontal dari bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


Menentukan jarak dalam satuan halaman dimana bayangan bentuk dipindahkan secara vertikal dari bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


Menentukan persentase di mana bayangan bentuk dapat diperbesar atau diperkecil.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


Menentukan jenis bayangan untuk sebuah bentuk.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


Menentukan jenis bayangan untuk sebuah bentuk.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


Menentukan warna yang digunakan untuk latar belakang (isi) pola isi bayangan jatuh bentuk.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


Menentukan tingkat transparansi untuk latar belakang (isi) pola isi bayangan jatuh bentuk, dari 0.0 (sepenuhnya tidak tembus) hingga 1.0 (sepenuhnya tembus).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


Menentukan warna yang digunakan untuk latar depan (garis) pola isi bayangan jatuh bentuk.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


Menentukan tingkat transparansi untuk latar depan (garis) pola isi bayangan jatuh bentuk, dari 0.0 (sepenuhnya tidak tembus) hingga 1.0 (sepenuhnya tembus).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


Menentukan pola isi untuk bayangan bentuk.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


Untuk deskripsi properti ini, silakan lihat [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

