---
title: PageLayout
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi sel yang mengontrol pengaturan tata letak halaman untuk bentuk dan penghubung seperti jarak antar semua bentuk pada halaman, jarak antar semua penghubung pada halaman, dan gaya perutean untuk semua penghubung pada halaman.
type: docs
weight: 263
url: /id/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Berisi sel yang mengontrol pengaturan tata letak halaman untuk bentuk dan konektor, seperti jarak antar semua bentuk pada halaman, jarak antar semua konektor pada halaman, dan gaya perutean untuk semua konektor pada halaman.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Menentukan jumlah ruang vertikal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Menentukan jumlah ruang vertikal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Menentukan bagaimana bentuk ditempatkan pada halaman ketika bentuk ditata ketika pengguna memilih Lay Out Shapes (menu Shape). |
| [getBlockSizeX()](#getBlockSizeX--) | Menentukan ukuran blok vertikal, area di mana setiap bentuk Anda harus muat pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar. |
| [getBlockSizeY()](#getBlockSizeY--) | Menentukan jumlah ruang horizontal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Menentukan bentuk mana yang menjadi induk saat menggunakan bentuk dengan pegangan kontrol. |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getDynamicsOff()](#getDynamicsOff--) | Menentukan apakah bentuk yang dapat ditempatkan bergerak dan penghubung mengalihkan rute di sekitar bentuk dan penghubung lain pada halaman gambar. |
| [getEnableGrid()](#getEnableGrid--) | Menentukan apakah Microsoft Visio menata bentuk berdasarkan kisi internal halaman ketika pengguna memilih Lay Out Shapes (menu Shape). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Menentukan konektor dinamis mana yang dipisahkan jika mereka routing di atas satu sama lain. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Menentukan konektor dinamis mana yang disejajarkan di atas satu sama lain jika mereka routing di atas satu sama lain. |
| [getLineJumpCode()](#getLineJumpCode--) | Menentukan gaya loncatan garis untuk semua konektor pada halaman gambar yang tidak memiliki gaya loncatan garis lokal. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Menentukan ukuran loncatan garis pada segmen horizontal penghubung dinamis pada halaman, sebagai persentase dari nilai elemen LineToLineX (yang menentukan jarak horizontal antara semua penghubung pada halaman gambar). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Menentukan ukuran loncatan garis pada segmen vertikal penghubung dinamis pada halaman, sebagai persentase dari nilai elemen LineToLineY (yang menentukan jarak vertikal antara semua penghubung pada halaman gambar). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Menentukan arah lompatan garis pada segmen horizontal konektor dinamis pada halaman gambar yang belum Anda terapkan arah lompatan lokal. |
| [getLineRouteExt()](#getLineRouteExt--) | Menentukan tampilan default untuk semua konektor pada sebuah halaman. |
| [getLineToLineX()](#getLineToLineX--) | Menentukan jarak horizontal minimum antara penghubung dinamis pada halaman gambar. |
| [getLineToLineY()](#getLineToLineY--) | Menentukan jarak vertikal minimum antara penghubung dinamis pada halaman gambar. |
| [getLineToNodeX()](#getLineToNodeX--) | Menentukan jarak vertikal minimum antara penghubung dinamis dan bentuk pada halaman gambar. |
| [getLineToNodeY()](#getLineToNodeY--) | Menentukan ukuran blok horizontal, area di mana setiap bentuk Anda harus muat pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Menentukan arah lompatan garis pada konektor dinamis vertikal pada halaman gambar yang belum Anda terapkan arah lompatan lokal. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Menentukan jarak horizontal minimum antara penghubung dinamis dan bentuk pada halaman gambar. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Menunjukkan apakah bentuk pada halaman dapat dipisah secara otomatis. |
| [getPlaceDepth()](#getPlaceDepth--) | Menentukan apakah bentuk yang dapat ditempatkan bergerak menjauh ketika pengguna menyeret sebuah bentuk yang dapat ditempatkan dekat dengan bentuk lain yang dapat ditempatkan pada halaman gambar. |
| [getPlaceFlip()](#getPlaceFlip--) | Menentukan bagaimana bentuk yang dapat ditempatkan diputar dan/atau diputar pada halaman ketika bentuk ditata menggunakan perintah Lay Out Shapes di Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Menentukan gaya routing dan arah untuk semua konektor dinamis pada halaman gambar yang tidak memiliki gaya routing lokal. |
| [getPlowCode()](#getPlowCode--) | Menentukan konektor dinamis yang ingin Anda tambahkan loncatan. |
| [getResizePage()](#getResizePage--) | Menentukan apakah memperbesar halaman untuk menampung gambar setelah pengguna memilih Lay Out Shapes (menu Shapes). |
| [getRouteStyle()](#getRouteStyle--) | Untuk gambar yang ditata secara otomatis, menentukan metode di mana gambar dianalisis sebelum membuat tata letak dan menentukan jenis tata letak. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Menentukan jumlah ruang vertikal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Menentukan jumlah ruang vertikal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Menentukan bagaimana bentuk ditempatkan pada halaman ketika bentuk ditata ketika pengguna memilih Lay Out Shapes (menu Shape).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Menentukan ukuran blok vertikal, area di mana setiap bentuk Anda harus muat pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Menentukan jumlah ruang horizontal antara bentuk pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Menentukan bentuk mana yang menjadi induk saat menggunakan bentuk dengan pegangan kontrol. Elemen ini mengatur perilaku semua bentuk pada halaman gambar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Menentukan apakah bentuk yang dapat ditempatkan bergerak dan penghubung mengalihkan rute di sekitar bentuk dan penghubung lain pada halaman gambar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Menentukan apakah Microsoft Visio menata bentuk berdasarkan kisi internal halaman ketika pengguna memilih Lay Out Shapes (menu Shape).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Menentukan konektor dinamis mana yang dipisahkan jika mereka routing di atas satu sama lain.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Menentukan konektor dinamis mana yang disejajarkan di atas satu sama lain jika mereka routing di atas satu sama lain.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Menentukan gaya loncatan garis untuk semua konektor pada halaman gambar yang tidak memiliki gaya loncatan garis lokal.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Menentukan ukuran loncatan garis pada segmen horizontal penghubung dinamis pada halaman, sebagai persentase dari nilai elemen LineToLineX (yang menentukan jarak horizontal antara semua penghubung pada halaman gambar). Nilai elemen ini berkisar antara 0 hingga 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Menentukan ukuran loncatan garis pada segmen vertikal penghubung dinamis pada halaman, sebagai persentase dari nilai elemen LineToLineY (yang menentukan jarak vertikal antara semua penghubung pada halaman gambar). Elemen ini dapat berisi nilai antara 0 hingga 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Menentukan arah lompatan garis pada segmen horizontal konektor dinamis pada halaman gambar yang belum Anda terapkan arah lompatan lokal.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Menentukan tampilan default untuk semua konektor pada sebuah halaman.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Menentukan jarak horizontal minimum antara penghubung dinamis pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Menentukan jarak vertikal minimum antara penghubung dinamis pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Menentukan jarak vertikal minimum antara penghubung dinamis dan bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Menentukan ukuran blok horizontal, area di mana setiap bentuk Anda harus muat pada halaman gambar ketika Anda menggunakan Microsoft Visio untuk menata bentuk pada halaman gambar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Menentukan arah lompatan garis pada konektor dinamis vertikal pada halaman gambar yang belum Anda terapkan arah lompatan lokal.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Menentukan jarak horizontal minimum antara penghubung dinamis dan bentuk pada halaman gambar.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Menunjukkan apakah bentuk pada halaman dapat dipisah secara otomatis.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Menentukan apakah bentuk yang dapat ditempatkan bergerak menjauh ketika pengguna menyeret sebuah bentuk yang dapat ditempatkan dekat dengan bentuk lain yang dapat ditempatkan pada halaman gambar.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Menentukan bagaimana bentuk yang dapat ditempatkan diputar dan/atau diputar pada halaman ketika bentuk diatur menggunakan perintah Lay Out Shapes di Microsoft Visio. Nilai heksadesimal berikut diperbolehkan.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Menentukan gaya routing dan arah untuk semua konektor dinamis pada halaman gambar yang tidak memiliki gaya routing lokal.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Menentukan konektor dinamis yang ingin Anda tambahkan loncatan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Menentukan apakah memperbesar halaman untuk menampung gambar setelah pengguna memilih Lay Out Shapes (menu Shapes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Untuk gambar yang ditata secara otomatis, menentukan metode di mana gambar dianalisis sebelum membuat tata letak dan menentukan jenis tata letak.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--)

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

