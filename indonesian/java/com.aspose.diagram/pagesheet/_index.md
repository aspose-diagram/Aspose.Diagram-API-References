---
title: PageSheet
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang mendefinisikan lembar halaman untuk elemen Page atau Master.
type: docs
weight: 270
url: /id/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Berisi elemen yang mendefinisikan lembar halaman untuk elemen Page atau Master.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Menyalin pagesheet dari objek sumber. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Berisi kumpulan elemen Act. |
| [getAnnotations()](#getAnnotations--) | Berisi elemen yang memuat informasi tentang komentar yang dimasukkan ke dalam halaman dokumen. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Berisi koleksi elemen ConnectionABCD. |
| [getConnections()](#getConnections--) | Berisi koleksi elemen Connection. |
| [getFillStyle()](#getFillStyle--) | Elemen StyleSheet yang menjadi sumber format isian bagi PageSheet. |
| [getForeign()](#getForeign--) | Berisi elemen yang menentukan lebar dan tinggi objek dari program lain yang digunakan dalam dokumen Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE. |
| [getHyperlinks()](#getHyperlinks--) | Berisi koleksi elemen Hyperlink. |
| [getLayers()](#getLayers--) | Berisi kumpulan elemen Layer. |
| [getLineStyle()](#getLineStyle--) | Elemen StyleSheet yang menjadi sumber format garis bagi PageSheet. |
| [getPageLayout()](#getPageLayout--) | Berisi Diagram yang mengontrol pengaturan tata letak halaman untuk bentuk dan konektor, seperti jarak antar semua bentuk pada halaman, jarak antar semua konektor pada halaman, dan gaya perutean untuk semua konektor pada halaman. |
| [getPageProps()](#getPageProps--) | Berisi Diagram yang mengontrol atribut halaman, seperti lebar, tinggi, dan skala halaman. |
| [getPrintProps()](#getPrintProps--) | Berisi elemen yang mengontrol bagaimana halaman gambar diformat (muncul) pada halaman printer. |
| [getProps()](#getProps--) | Berisi koleksi elemen Prop. |
| [getRulerGrid()](#getRulerGrid--) | Berisi elemen yang menentukan pengaturan penggaris dan grid halaman. |
| [getScratchs()](#getScratchs--) | Berisi kumpulan elemen Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Berisi kumpulan elemen SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Elemen StyleSheet yang menjadi sumber format teks bagi PageSheet. |
| [getUniqueID()](#getUniqueID--) | GUID (pengidentifikasi unik global) untuk elemen. |
| [getUsers()](#getUsers--) | Berisi kumpulan elemen User. |
| [getXForm()](#getXForm--) | Berisi elemen yang menentukan informasi penempatan umum tentang sebuah bentuk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Menyalin pagesheet dari objek sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | sumber pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Berisi kumpulan elemen Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Berisi elemen yang memuat informasi tentang komentar yang dimasukkan ke dalam halaman dokumen.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Berisi koleksi elemen ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Berisi koleksi elemen Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Elemen StyleSheet yang menjadi sumber format isian bagi PageSheet.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Berisi elemen yang menentukan lebar dan tinggi sebuah objek dari program lain yang digunakan dalam dokumen Microsoft Visio. Juga mencakup elemen yang menentukan jarak gambar objek dipindahkan dalam batasnya.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Berisi koleksi elemen Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Berisi kumpulan elemen Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Elemen StyleSheet yang menjadi sumber format garis bagi PageSheet.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Berisi Diagram yang mengontrol pengaturan tata letak halaman untuk bentuk dan konektor, seperti jarak antar semua bentuk pada halaman, jarak antar semua konektor pada halaman, dan gaya perutean untuk semua konektor pada halaman.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Berisi Diagram yang mengontrol atribut halaman, seperti lebar, tinggi, dan skala halaman.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Berisi elemen yang mengontrol bagaimana halaman gambar diformat (muncul) pada halaman printer.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Berisi koleksi elemen Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Berisi elemen yang menentukan pengaturan penggaris dan grid halaman.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Berisi kumpulan elemen Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Berisi kumpulan elemen SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Elemen StyleSheet yang menjadi sumber format teks bagi PageSheet.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID (pengidentifikasi unik global) untuk elemen.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Berisi kumpulan elemen User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Berisi elemen yang menentukan informasi penempatan umum tentang sebuah bentuk.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

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

