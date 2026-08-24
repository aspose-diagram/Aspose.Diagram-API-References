---
title: Window
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili jendela terbuka dalam instance Microsoft Visio.
type: docs
weight: 444
url: /id/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Mewakili jendela terbuka dalam sebuah instance Microsoft Visio. Elemen ini berisi informasi yang diperlukan untuk secara tepat membuat kembali jendela antarmuka pengguna di ruang kerja aplikasi ketika file DatadiagramML pertama kali dibuka oleh Visio.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Window()](#Window--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID kontainer: Halaman, Lembar, atau Master. |
| [getContainerType()](#getContainerType--) | Bisa berupa salah satu nilai berikut: Document, Page, atau Master. |
| [getDocument()](#getDocument--) | Path file dokumen yang ditampilkan di jendela ini. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Menentukan apakah fitur kisi dinamis diaktifkan untuk sebuah dokumen atau jendela. |
| [getGlueSettings()](#getGlueSettings--) | Menentukan objek yang menjadi tempat lem bentuk ketika lem diaktifkan dalam dokumen. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getMaster()](#getMaster--) | ID master jika jendela ini menampilkan master. |
| [getPage()](#getPage--) | ID halaman jika jendela ini menampilkan halaman. |
| [getParentWindow()](#getParentWindow--) | ID jendela tempat jendela stensil ini berada. |
| [getReadOnly()](#getReadOnly--) | Bendera baca-saja jika stensil ini bukan stensil dokumen. |
| [getSheet()](#getSheet--) | ID lembar dalam kontainer. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Menentukan apakah titik koneksi ditampilkan di jendela. |
| [getShowGrid()](#getShowGrid--) | Menentukan apakah grid ditampilkan di jendela gambar. |
| [getShowGuides()](#getShowGuides--) | Menentukan apakah panduan ditampilkan di jendela gambar. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Menentukan apakah jeda halaman ditampilkan di jendela. |
| [getShowRulers()](#getShowRulers--) | Menentukan apakah penggaris ditampilkan di jendela gambar. |
| [getSnapAngles()](#getSnapAngles--) | Berisi kumpulan elemen SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Menentukan apakah pengaturan ekstensi snap tertentu diaktifkan atau dinonaktifkan untuk jendela aktif. |
| [getSnapSettings()](#getSnapSettings--) | Menentukan objek yang menjadi target snap bentuk ketika snap aktif di jendela. |
| [getStencilGroup()](#getStencilGroup--) | Menentukan grup jendela stensil yang digabungkan yang menjadi anggota jendela ini. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Berisi integer yang menentukan posisi relatif stensil dalam grup di sebuah jendela. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Menentukan lebar kontrol tab halaman dari jendela gambar (sebagai fraksi dari lebar total jendela gambar). |
| [getViewCenterX()](#getViewCenterX--) | Double opsional. |
| [getViewCenterY()](#getViewCenterY--) | Double opsional. |
| [getViewScale()](#getViewScale--) | Double opsional. |
| [getWindowHeight()](#getWindowHeight--) | Tinggi persegi panjang jendela. |
| [getWindowLeft()](#getWindowLeft--) | Koordinat kiri persegi panjang jendela. |
| [getWindowState()](#getWindowState--) | Atribut ini dapat berupa jumlah dari nilai-nilai berikut. |
| [getWindowTop()](#getWindowTop--) | Koordinat atas persegi panjang jendela. |
| [getWindowType()](#getWindowType--) | Nilai enumerasi yang dapat berupa salah satu dari berikut: Drawing, Sheet, Stencil, atau Icon. Elemen Window dengan WindowType='Stencil' harus muncul setelah jendela gambar induknya (WindowType='Drawing') dan sebelum elemen jendela gambar lainnya. |
| [getWindowWidth()](#getWindowWidth--) | Lebar persegi panjang jendela. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Untuk deskripsi properti ini, silakan lihat [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Untuk deskripsi properti ini, silakan lihat [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Untuk deskripsi properti ini, silakan lihat [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Untuk deskripsi properti ini, silakan lihat [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Untuk deskripsi properti ini, silakan lihat [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Untuk deskripsi properti ini, silakan lihat [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Untuk deskripsi properti ini, silakan lihat [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Untuk deskripsi properti ini, silakan lihat [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Untuk deskripsi properti ini, silakan lihat [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Untuk deskripsi properti ini, silakan lihat [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Untuk deskripsi properti ini, silakan lihat [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Untuk deskripsi properti ini, silakan lihat [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Untuk deskripsi properti ini, silakan lihat [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Untuk deskripsi properti ini, silakan lihat [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Untuk deskripsi properti ini, silakan lihat [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Untuk deskripsi properti ini, silakan lihat [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Untuk deskripsi properti ini, silakan lihat [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Untuk deskripsi properti ini, silakan lihat [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Untuk deskripsi properti ini, silakan lihat [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Untuk deskripsi properti ini, silakan lihat [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Untuk deskripsi properti ini, silakan lihat [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Untuk deskripsi properti ini, silakan lihat [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Untuk deskripsi properti ini, silakan lihat [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Untuk deskripsi properti ini, silakan lihat [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | For the description of this property, please see [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | For the description of this property, please see [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | For the description of this property, please see [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


ID kontainer: Page, Sheet, atau Master. Hanya relevan dan diperlukan jika ContainerType ditentukan.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Mungkin salah satu nilai berikut: Document, Page, atau Master. Hanya relevan ketika WindowType ditentukan sebagai Drawing atau Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Jalur file dokumen yang ditampilkan di jendela ini. Atribut ini relevan untuk jendela yang WindowType‑nya ditentukan sebagai Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Menentukan apakah fitur kisi dinamis diaktifkan untuk sebuah dokumen atau jendela.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Menentukan objek yang menjadi tempat lem bentuk ketika lem diaktifkan dalam dokumen.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


ID master jika jendela ini menampilkan master.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


ID halaman jika jendela ini menampilkan sebuah halaman. Hanya relevan ketika WindowType ditentukan sebagai Drawing dan ContainerType ditentukan sebagai Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID jendela tempat jendela stencil ini berada. Hanya relevan ketika WindowType ditentukan sebagai Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Bendera baca-saja jika stensil ini bukan stensil dokumen.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID lembar dalam kontainer. Hanya relevan ketika Container ditentukan sebagai Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Menentukan apakah titik koneksi ditampilkan di jendela.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Menentukan apakah grid ditampilkan di jendela gambar.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Menentukan apakah panduan ditampilkan di jendela gambar.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Menentukan apakah jeda halaman ditampilkan di jendela.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Menentukan apakah penggaris ditampilkan di jendela gambar.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Berisi kumpulan elemen SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Menentukan apakah pengaturan ekstensi snap tertentu diaktifkan atau dinonaktifkan untuk jendela aktif. Nilainya dapat berupa jumlah dari nilai-nilai dalam tabel berikut.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Menentukan objek yang akan dipasangkan (snap) oleh shape ketika snap aktif di jendela. Nilainya dapat berupa jumlah nilai-nilai dalam tabel berikut.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Menentukan grup jendela stencil yang digabungkan yang menjadi anggota jendela ini. Atribut ini hanya relevan untuk elemen Window yang atribut WindowType‑nya adalah Stencil, dan hanya jika jendela stencil merupakan bagian dari grup jendela stencil yang digabungkan. Semua jendela stencil yang merupakan bagian dari grup yang sama memiliki nilai elemen StencilGroup yang sama.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Berisi integer yang menentukan posisi relatif stensil dalam grup di sebuah jendela.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Menentukan lebar kontrol tab halaman dari jendela gambar (sebagai fraksi dari lebar total jendela gambar).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Double opsional.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Double opsional.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Double opsional.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Tinggi persegi panjang jendela.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Koordinat kiri persegi panjang jendela.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Atribut ini dapat berupa jumlah dari nilai-nilai berikut.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Koordinat atas persegi panjang jendela.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Nilai enumerasi yang dapat berupa salah satu dari berikut: Drawing, Sheet, Stencil, atau Icon. Elemen Window dengan WindowType='Stencil' harus muncul setelah jendela gambar induknya (WindowType='Drawing') dan sebelum elemen jendela gambar lainnya.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Lebar persegi panjang jendela.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


Untuk deskripsi properti ini, silakan lihat [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Untuk deskripsi properti ini, silakan lihat [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Untuk deskripsi properti ini, silakan lihat [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Untuk deskripsi properti ini, silakan lihat [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Untuk deskripsi properti ini, silakan lihat [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Untuk deskripsi properti ini, silakan lihat [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Untuk deskripsi properti ini, silakan lihat [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Untuk deskripsi properti ini, silakan lihat [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Untuk deskripsi properti ini, silakan lihat [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Untuk deskripsi properti ini, silakan lihat [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Untuk deskripsi properti ini, silakan lihat [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Untuk deskripsi properti ini, silakan lihat [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Untuk deskripsi properti ini, silakan lihat [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Untuk deskripsi properti ini, silakan lihat [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


For the description of this property, please see [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


For the description of this property, please see [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


For the description of this property, please see [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

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

