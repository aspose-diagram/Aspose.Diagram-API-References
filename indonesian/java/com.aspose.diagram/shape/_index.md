---
title: Bentuk
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang mendefinisikan bentuk dalam Halaman Master atau elemen bentuk grup.
type: docs
weight: 355
url: /id/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Berisi elemen yang mendefinisikan bentuk dalam elemen Master, Page, atau grup bentuk.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Shape()](#Shape--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [bringForward()](#bringForward--) | Membawa bentuk maju satu posisi dalam urutan z. |
| [bringToFront()](#bringToFront--) | Membawa bentuk ke depan urutan z. |
| [centerDrawing()](#centerDrawing--) | Pusatkan bentuk relatif terhadap ukuran halaman |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Mengembalikan array yang berisi pengidentifikasi (ID) dari bentuk yang terhubung ke bentuk tersebut. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Mengembalikan array yang berisi pengidentifikasi bentuk yang bergantung pada sebuah bentuk. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Mendapatkan kontrol ActiveX. |
| [getActs()](#getActs--) | Berisi kumpulan elemen Act. |
| [getAlign()](#getAlign--) | Menunjukkan perataan bentuk relatif terhadap panduan atau titik panduan tempat bentuk tersebut ditempelkan. |
| [getChars()](#getChars--) | Berisi koleksi elemen Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Berisi koleksi elemen ConnectionABCD. |
| [getConnections()](#getConnections--) | Berisi koleksi elemen Connection. |
| [getConnectorRule()](#getConnectorRule--) | Mengembalikan connectorRule yang berisi id bentuk dan koneksi yang terhubung ke bentuk tersebut. |
| [getConnectorsType()](#getConnectorsType--) | Dapatkan tipe konektor |
| [getControlData()](#getControlData--) | Mendapatkan data kontrol. |
| [getControls()](#getControls--) | Berisi koleksi elemen Control. |
| [getData1()](#getData1--) | Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk. |
| [getData2()](#getData2--) | Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk. |
| [getData3()](#getData3--) | Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk. |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen dihapus secara lokal. |
| [getDiagram()](#getDiagram--) | Elemen akar hierarki objek Visio. |
| [getDisplayText()](#getDisplayText--) | Dapatkan teks yang ditampilkan pada antarmuka |
| [getEvent()](#getEvent--) | Berisi elemen yang menentukan formula yang mengontrol peristiwa bentuk. |
| [getFields()](#getFields--) | Berisi koleksi elemen Field. |
| [getFill()](#getFill--) | Berisi nilai format pengisian saat ini untuk bentuk dan bayangan jatuh bentuk, termasuk pola, warna latar depan, dan warna latar belakang. |
| [getFillStyle()](#getFillStyle--) | StyleSheet dari mana bentuk ini mewarisi format pengisian. |
| [getForeign()](#getForeign--) | Berisi elemen yang menentukan lebar dan tinggi objek dari program lain yang digunakan dalam dokumen Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE. |
| [getGeoms()](#getGeoms--) | Berisi koleksi elemen Geom. |
| [getGroup()](#getGroup--) | Berisi elemen yang mengontrol cara Anda menambahkan bentuk ke grup, memindahkan anggota grup, dan memilih grup. |
| [getHelp()](#getHelp--) | Berisi elemen yang menentukan topik file Bantuan elemen Shape dan informasi hak cipta. |
| [getHyperlinks()](#getHyperlinks--) | Berisi koleksi elemen Hyperlink. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getImage()](#getImage--) | Berisi nilai gamma, kecerahan, kontras, blur, penajaman, pengurangan noise, dan transparansi untuk bitmap. |
| [getInheritChars()](#getInheritChars--) | Berisi nilai karakter untuk bentuk yang diwarisi oleh bentuk master. |
| [getInheritFill()](#getInheritFill--) | Berisi nilai format pengisian untuk bentuk yang diwarisi oleh gaya induk dan bentuk master. |
| [getInheritGeoms()](#getInheritGeoms--) | Berisi nilai Geoms untuk bentuk yang diwarisi oleh bentuk master. |
| [getInheritLine()](#getInheritLine--) | Berisi nilai pemformatan garis untuk bentuk yang diwarisi oleh gaya induk dan bentuk master. |
| [getInheritParas()](#getInheritParas--) | Berisi paras untuk bentuk yang diwarisi oleh gaya induk dan bentuk master. |
| [getInheritProps()](#getInheritProps--) | Berisi properti untuk bentuk yang diwarisi oleh bentuk master. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Berisi nilai blok teks untuk bentuk yang diwarisi oleh gaya induk dan bentuk master. |
| [getInheritUsers()](#getInheritUsers--) | Berisi pengguna untuk bentuk yang diwarisi oleh bentuk master. |
| [getLayerMem()](#getLayerMem--) | Berisi elemen LayerMember, yang menentukan setiap lapisan yang ditugaskan ke bentuk. |
| [getLayout()](#getLayout--) | Berisi elemen yang mengontrol penempatan bentuk dan pengaturan routing konektor. |
| [getLine()](#getLine--) | Berisi elemen yang mengontrol atribut garis untuk sebuah bentuk, seperti pola, ketebalan, dan warna. |
| [getLineStyle()](#getLineStyle--) | StyleSheet dari mana bentuk ini mewarisi pemformatan garis |
| [getMaster()](#getMaster--) | Master dari mana bentuk mewarisi datanya. |
| [getMasterShape()](#getMasterShape--) | Atribut ini hanya dapat hadir pada bentuk yang merupakan anggota grup bentuk, dan grup tersebut merupakan contoh dari master. |
| [getMisc()](#getMisc--) | Berisi elemen yang menentukan topik file Bantuan elemen Shape dan informasi hak cipta. |
| [getName()](#getName--) | Nama elemen. |
| [getNameU()](#getNameU--) | Nama universal elemen. |
| [getOneD()](#getOneD--) | Menentukan apakah bentuk berperilaku sebagai objek satu dimensi (1-D). |
| [getPage()](#getPage--) | Elemen akar hierarki objek Visio. |
| [getParas()](#getParas--) | Berisi koleksi elemen Para. |
| [getParentShape()](#getParentShape--) | Induk bentuk. |
| [getProps()](#getProps--) | Berisi koleksi elemen Prop. |
| [getProtection()](#getProtection--) | Penguncian membantu mencegah perubahan tidak sengaja pada bentuk tetapi tidak mencegah Microsoft Visio mengatur ulang nilai dalam keadaan lain. |
| [getPureText()](#getPureText--) | Dapatkan string teks |
| [getRootShape()](#getRootShape--) | Mengembalikan bentuk tingkat atas dari sebuah instance jika bentuk ini merupakan bagian dari instance master. |
| [getScratchs()](#getScratchs--) | Berisi kumpulan elemen Scratch. |
| [getShapes()](#getShapes--) | Berisi koleksi elemen Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Berisi kumpulan elemen SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Berisi koleksi elemen Tab. |
| [getText()](#getText--) | Berisi teks dari sebuah bentuk. |
| [getTextBlock()](#getTextBlock--) | Berisi elemen yang menentukan perataan, margin, dan posisi tab default pada teks dalam blok teks bentuk. |
| [getTextStyle()](#getTextStyle--) | StyleSheet dari mana bentuk ini mewarisi pemformatan teks. |
| [getTextXForm()](#getTextXForm--) | Berisi elemen yang menentukan informasi posisi tentang blok teks bentuk. |
| [getThreeDFormat()](#getThreeDFormat--) | Mengambil ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Menentukan apakah bentuk berperilaku sebagai objek dua dimensi (2-D). |
| [getType()](#getType--) | Tipe sebuah bentuk. |
| [getUniqueID()](#getUniqueID--) | GUID (identifikasi unik global) yang ditetapkan untuk bentuk. |
| [getUsers()](#getUsers--) | Berisi kumpulan elemen User. |
| [getXForm()](#getXForm--) | Berisi elemen yang menentukan informasi penempatan umum tentang sebuah bentuk. |
| [getXForm1D()](#getXForm1D--) | Berisi koordinat x dan y dari titik awal dan titik akhir sebuah bentuk 1-D. |
| [getZOrderIndex()](#getZOrderIndex--) | Mengembalikan indeks sebuah bentuk dalam urutan z kecuali bentuk panduan. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Mengembalikan array yang berisi pengidentifikasi bentuk-bentuk yang ditempelkan pada sebuah bentuk. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Menunjukkan apakah dua bentuk ini terhubung. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Menunjukkan apakah bentuk ini berisi bentuk lain. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Menunjukkan apakah dua bentuk ini ditempelkan. |
| [isInGroup()](#isInGroup--) | Menunjukkan apakah bentuk ini berada dalam grup bentuk. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Menunjukkan apakah bentuk ini berpotongan dengan bentuk lain. |
| [isTextEmpty()](#isTextEmpty--) | Menunjukkan apakah bentuk memiliki teks dan apakah teks tersebut kosong atau tidak. |
| [move(double dX, double dY)](#move-double-double-) | Memindahkan bentuk sebesar dX dan dY inci dari posisi saat ini. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Memindahkan bentuk ke posisi absolut baru pada halaman. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Menyegarkan posisi bentuk termasuk xform, koneksi, dan geom saat mengubah teks bentuk atau lainnya. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Mengganti string teks dari sebuah bentuk. |
| [sendBackward()](#sendBackward--) | Memindahkan bentuk satu posisi ke belakang dalam urutan z. |
| [sendToBack()](#sendToBack--) | Memindahkan bentuk ke bagian belakang urutan z. |
| [setAngle(double angle)](#setAngle-double-) | Mengatur sudut baru bentuk. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Atur tipe Penyambung |
| [setData1(String value)](#setData1-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Untuk deskripsi properti ini, silakan lihat [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Untuk deskripsi properti ini, silakan lihat [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Mengatur tinggi baru bentuk. |
| [setID(long value)](#setID-long-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Untuk deskripsi properti ini, silakan lihat [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Untuk deskripsi properti ini, silakan lihat [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Untuk deskripsi properti ini, silakan lihat [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Untuk deskripsi properti ini, silakan lihat [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Terapkan tema preset ke shape ini |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Terapkan varian tema preset quickstyle ke shape ini |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Terapkan varian tema preset quickstyle ke shape ini, seperti opsi gaya tema dalam daftar dropdown gaya shape |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Terapkan varian tema preset ke shape ini |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Untuk deskripsi properti ini, silakan lihat [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Untuk deskripsi properti ini, silakan lihat [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Untuk deskripsi properti ini, silakan lihat [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Untuk deskripsi properti ini, silakan lihat [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Untuk deskripsi properti ini, silakan lihat [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Menetapkan lebar baru shape. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Untuk deskripsi properti ini, silakan lihat [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Untuk deskripsi properti ini, silakan lihat [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Membuat html shape dan menyimpannya ke aliran dalam format yang ditentukan. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Membuat html shape dan menyimpannya ke aliran dalam format yang ditentukan. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Membuat html dan menyimpannya ke file. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Membuat gambar shape dan menyimpannya ke aliran dalam format yang ditentukan. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Membuat gambar shape dan menyimpannya ke aliran dalam format yang ditentukan. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Membuat gambar shape dan menyimpannya ke file. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Membuat pdf shape dan menyimpannya ke aliran. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Membuat pdf shape dan menyimpannya ke aliran. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Menyimpan shape ke file pdf. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Menyimpan shape ke file svg. |
| [ungroup()](#ungroup--) | Lepaskan grup Shape |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Konstruktor.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Membawa bentuk maju satu posisi dalam urutan z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Membawa bentuk ke depan urutan z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Pusatkan bentuk relatif terhadap ukuran halaman

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Mengembalikan array yang berisi pengidentifikasi (ID) dari bentuk yang terhubung ke bentuk tersebut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bendera | int | Menyaring array ID shape yang dikembalikan berdasarkan arah konektor. Lihat Remarks untuk nilai yang mungkin Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Menyaring array ID bentuk yang dikembalikan dengan membatasi ke ID bentuk yang cocok dengan categoryString yang ditentukan. |

**Returns:**
long[] - array ID.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Mengembalikan array yang berisi pengidentifikasi bentuk yang bergantung pada sebuah bentuk.

**Returns:**
long[] - array ID.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Mendapatkan kontrol ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Berisi kumpulan elemen Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Menunjukkan perataan sebuah bentuk terhadap panduan atau titik panduan tempat bentuk tersebut ditempelkan. Elemen Align muncul hanya untuk bentuk yang ditempelkan pada panduan atau titik panduan.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Berisi koleksi elemen Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Mengembalikan connectorRule yang berisi id bentuk dan koneksi yang terhubung ke bentuk tersebut.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Dapatkan tipe konektor

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Mendapatkan data kontrol.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Berisi koleksi elemen Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Berisi nilai string sewenang-wenang yang digunakan untuk menyediakan informasi tambahan tentang sebuah bentuk.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen dihapus secara lokal.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Elemen akar hierarki objek Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Dapatkan teks yang ditampilkan pada antarmuka

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Berisi elemen yang menentukan formula yang mengontrol peristiwa bentuk.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Berisi koleksi elemen Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Berisi nilai format pengisian saat ini untuk bentuk dan bayangan jatuh bentuk, termasuk pola, warna latar depan, dan warna latar belakang.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet dari mana bentuk ini mewarisi format pengisian.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Berisi koleksi elemen Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Berisi elemen yang mengontrol cara Anda menambahkan bentuk ke grup, memindahkan anggota grup, dan memilih grup.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Berisi elemen yang menentukan topik file Bantuan elemen Shape dan informasi hak cipta.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Berisi koleksi elemen Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Berisi nilai gamma, kecerahan, kontras, blur, penajaman, pengurangan noise, dan transparansi untuk bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Berisi nilai karakter untuk bentuk yang diwarisi oleh bentuk master.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Berisi nilai format pengisian untuk bentuk yang diwarisi oleh gaya induk dan bentuk master.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Berisi nilai Geoms untuk bentuk yang diwarisi oleh bentuk master.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Berisi nilai pemformatan garis untuk bentuk yang diwarisi oleh gaya induk dan bentuk master.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Berisi paras untuk bentuk yang diwarisi oleh gaya induk dan bentuk master.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Berisi properti untuk bentuk yang diwarisi oleh bentuk master.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Berisi nilai blok teks untuk bentuk yang diwarisi oleh gaya induk dan bentuk master.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Berisi pengguna untuk bentuk yang diwarisi oleh bentuk master.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Berisi elemen LayerMember, yang menentukan setiap lapisan yang ditugaskan ke bentuk.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Berisi elemen yang mengontrol penempatan bentuk dan pengaturan routing konektor.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Berisi elemen yang mengontrol atribut garis untuk sebuah bentuk, seperti pola, ketebalan, dan warna. Elemen-elemen ini menentukan apakah ujung garis diformat (misalnya, dengan kepala panah), ukuran format ujung garis, radius lingkaran pembulatan yang diterapkan pada garis, dan gaya tutup garis (bulat atau kotak).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet dari mana bentuk ini mewarisi pemformatan garis

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master dari mana bentuk mewarisi datanya.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Atribut ini hanya dapat hadir pada bentuk yang merupakan anggota dari bentuk grup, dan grup tersebut merupakan instance dari master. Atribut ini berisi ID yang merujuk ke sub-bentuk yang sesuai dalam master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Berisi elemen yang menentukan topik file Bantuan elemen Shape dan informasi hak cipta.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Nama elemen.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Nama universal elemen.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Menentukan apakah bentuk berperilaku sebagai objek satu dimensi (1-D). Hanya-baca.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Elemen akar hierarki objek Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Berisi koleksi elemen Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Induk bentuk.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Berisi koleksi elemen Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Penguncian membantu mencegah perubahan tidak sengaja pada bentuk tetapi tidak mencegah Microsoft Visio mengatur ulang nilai dalam keadaan lain. Ini juga tidak melindungi dari perubahan yang dibuat di jendela ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Dapatkan string teks

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Mengembalikan bentuk tingkat atas dari sebuah instance jika bentuk ini merupakan bagian dari instance master. Hanya-baca.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Berisi kumpulan elemen Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Berisi koleksi elemen Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Berisi kumpulan elemen SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Berisi koleksi elemen Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Berisi teks dari sebuah bentuk.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Berisi elemen yang menentukan perataan, margin, dan posisi tab default pada teks dalam blok teks bentuk.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet dari mana bentuk ini mewarisi pemformatan teks.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Berisi elemen yang menentukan informasi posisi tentang blok teks bentuk.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Mengambil ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Menentukan apakah bentuk berperilaku sebagai objek dua dimensi (2-D).

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Tipe sebuah bentuk. Bisa berupa salah satu nilai berikut: Group, Shape, Guide, atau Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID (identifikasi unik global) yang ditetapkan untuk bentuk.

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Berisi koordinat x dan y dari titik awal dan titik akhir sebuah bentuk 1-D. Elemen ini muncul hanya untuk bentuk 1-D.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Mengembalikan indeks sebuah bentuk dalam urutan z kecuali bentuk panduan.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Mengembalikan array yang berisi pengidentifikasi bentuk-bentuk yang ditempelkan pada sebuah bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bendera | int | Dimensionalitas dan arah titik koneksi bentuk yang akan dikembalikan. Lihat Remarks untuk nilai yang mungkin Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Menyaring array ID bentuk yang dikembalikan dengan membatasi ke ID bentuk yang cocok dengan categoryString yang ditentukan. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Opsional: bentuk tambahan yang juga harus ditempelkan oleh bentuk yang dikembalikan, dapat berupa [Shape](../../com.aspose.diagram/shape) atau null. |

**Returns:**
long[] - array ID.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Menunjukkan apakah dua bentuk ini terhubung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Menunjukkan apakah bentuk ini berisi bentuk lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Menunjukkan apakah dua bentuk ini ditempelkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Menunjukkan apakah bentuk ini berada dalam grup bentuk.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Menunjukkan apakah bentuk ini berpotongan dengan bentuk lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Menunjukkan apakah bentuk memiliki teks dan apakah teks tersebut kosong atau tidak.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Memindahkan bentuk sebesar dX dan dY inci dari posisi saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dX | double | Offset X double. |
| dY | double | Offset Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Memindahkan bentuk ke posisi absolut baru pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newPinX | double | Koordinat x baru dari pin bentuk (pusat rotasi) relatif terhadap asal induknya. double. |
| newPinY | double | Koordinat y baru dari pin bentuk (pusat rotasi) relatif terhadap asal induknya. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Menyegarkan posisi bentuk termasuk xform, koneksi, dan geom saat mengubah teks bentuk atau lainnya. Kami akan mengumpulkan data bentuk seperti teks bentuk kemudian menghitung posisi bentuk. Metode ini hanya digunakan untuk menyegarkan data bentuk.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Mengganti string teks dari sebuah bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Memindahkan bentuk satu posisi ke belakang dalam urutan z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Memindahkan bentuk ke bagian belakang urutan z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Mengatur sudut baru bentuk. Satuan sudut adalah radian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | double | Sudut baru dengan satuan radian, bukan derajat. double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Untuk deskripsi properti ini, silakan lihat [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Atur tipe Penyambung

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Untuk deskripsi properti ini, silakan lihat [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Untuk deskripsi properti ini, silakan lihat [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Untuk deskripsi properti ini, silakan lihat [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Untuk deskripsi properti ini, silakan lihat [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Untuk deskripsi properti ini, silakan lihat [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Mengatur tinggi baru bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Untuk deskripsi properti ini, silakan lihat [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Untuk deskripsi properti ini, silakan lihat [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Untuk deskripsi properti ini, silakan lihat [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Untuk deskripsi properti ini, silakan lihat [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Terapkan tema preset ke shape ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Terapkan varian tema preset quickstyle ke shape ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Terapkan varian tema preset quickstyle ke shape ini, seperti opsi gaya tema dalam daftar dropdown gaya shape

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Terapkan varian tema preset ke shape ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Untuk deskripsi properti ini, silakan lihat [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Untuk deskripsi properti ini, silakan lihat [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Untuk deskripsi properti ini, silakan lihat [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Untuk deskripsi properti ini, silakan lihat [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Menetapkan lebar baru shape.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Untuk deskripsi properti ini, silakan lihat [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Untuk deskripsi properti ini, silakan lihat [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Membuat html shape dan menyimpannya ke aliran dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Membuat html shape dan menyimpannya ke aliran dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Membuat html dan menyimpannya ke file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Membuat gambar shape dan menyimpannya ke aliran dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Membuat gambar shape dan menyimpannya ke aliran dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Membuat pdf shape dan menyimpannya ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Membuat pdf shape dan menyimpannya ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Menyimpan shape ke file pdf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Menyimpan shape ke file svg.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Lepaskan grup Shape

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

