---
title: Page
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang mendefinisikan halaman dalam dokumen.
type: docs
weight: 260
url: /id/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Berisi elemen yang mendefinisikan halaman dalam dokumen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Page()](#Page--) | Konstruktor. |
| [Page(int ID)](#Page-int-) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Membuat sebuah Kontrol Activex. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Menambahkan komentar ke sebuah shape. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Menambahkan komentar dengan PinX dan PinY yang ditentukan. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Menambahkan komentar ke sebuah shape dengan id shape. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Menambahkan shape yang dibuat oleh master ke halaman tertentu. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Menambahkan shape yang dibuat oleh master pada halaman dengan PinX,PinY,Width, dan Height yang ditentukan. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Menambahkan shape yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Menambahkan Teks dengan PinX dan PinY yang ditentukan. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Menambahkan Teks dengan PinX dan PinY yang ditentukan. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Menerapkan gaya untuk seluruh halaman. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Atur spasi otomatis shape. |
| [bringForward(long shapeId)](#bringForward-long-) | Memindahkan shape, yang didefinisikan oleh ID, maju satu posisi dalam urutan z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Memindahkan shape, yang didefinisikan oleh ID, ke depan urutan z. |
| [centerDrawing()](#centerDrawing--) | Menengahkan shape halaman relatif terhadap batas halaman. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Menghubungkan shape via connector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Menghubungkan shape via connector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Menghubungkan shape via connector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Menghubungkan shape via indeks connector. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Menghubungkan shape via indeks connector. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Proses menggambar Ellipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Proses menggambar satu garis. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Proses menggambar garis. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Proses menggambar Polyline. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Proses menggambar persegi panjang. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | ID halaman gambar asli yang ditandai pada overlay markup terpisah oleh peninjau gambar. |
| [getBackPage()](#getBackPage--) | Halaman latar belakang halaman. |
| [getBackground()](#getBackground--) | Bendera yang menunjukkan apakah halaman tersebut adalah halaman latar belakang. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Berisi elemen Connect untuk setiap koneksi antara dua bentuk dalam gambar. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getName()](#getName--) | Nama elemen. |
| [getNameU()](#getNameU--) | Nama universal elemen. |
| [getPageSheet()](#getPageSheet--) | Berisi elemen yang mendefinisikan lembar halaman untuk elemen Page atau Master. |
| [getPages()](#getPages--) | Koleksi halaman. |
| [getReviewerID()](#getReviewerID--) | ID peninjau yang terkait dengan overlay markup. |
| [getShapes()](#getShapes--) | Koleksi bentuk. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat pertama kali dibuka. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat pertama kali dibuka. |
| [getViewScale()](#getViewScale--) | Faktor pembesaran default yang digunakan saat tampilan (jendela) baru halaman dibuka. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Tempelkan bentuk ke Connector's BeginX |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Tempelkan bentuk ke Connector's EndX |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Tempelkan bentuk. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Tempelkan bentuk |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Tempelkan bentuk dalam kontainer |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Tempelkan bentuk dalam kontainer menggunakan nama koneksi |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Tempelkan bentuk berdasarkan id koneksi dalam kontainer |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Menyusun bentuk dan/atau mengarahkan ulang konektor untuk halaman. |
| [moveTo(int index)](#moveTo-int-) | Memindahkan halaman ke lokasi lain dalam halaman. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Memindahkan bentuk, yang didefinisikan oleh ID, satu posisi ke belakang dalam urutan z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Memindahkan bentuk, yang didefinisikan oleh ID, ke belakang urutan z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Untuk deskripsi properti ini, silakan lihat [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Untuk deskripsi properti ini, silakan lihat [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Untuk deskripsi properti ini, silakan lihat [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Untuk deskripsi properti ini, silakan lihat [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Terapkan tema preset ke halaman ini |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Terapkan varian tema preset quickstyle ke halaman ini |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Terapkan varian tema preset ke halaman ini |
| [setReviewerID(int value)](#setReviewerID-int-) | Untuk deskripsi properti ini, silakan lihat [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Untuk deskripsi properti ini, silakan lihat [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Untuk deskripsi properti ini, silakan lihat [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Untuk deskripsi properti ini, silakan lihat [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Konstruktor.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Membuat sebuah Kontrol Activex.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | int | Tipe kontrol. |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk dalam inci. |
| height | double | Menentukan tinggi bentuk dalam inci. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Menambahkan komentar ke sebuah shape.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Menentukan bentuk yang menambahkan komentar. |
| comment | java.lang.String | String komentar. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Menambahkan komentar dengan PinX dan PinY yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin komentar (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin komentar (pusat rotasi) relatif terhadap halaman. |
| comment | java.lang.String | String komentar. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Menambahkan komentar ke sebuah shape dengan id shape.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | String komentar. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Menambahkan shape yang dibuat oleh master ke halaman tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Objek bentuk baru[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nama master. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| aliran | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Menambahkan shape yang dibuat oleh master pada halaman dengan PinX,PinY,Width, dan Height yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk dalam inci. |
| height | double | Menentukan tinggi bentuk dalam inci. |
| masterName | java.lang.String | Nama master. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Menambahkan shape yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| masterName | java.lang.String | Nama master. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Menambahkan Teks dengan PinX dan PinY yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x dari pin teks (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y dari pin teks (pusat rotasi) relatif terhadap halaman. |
| width | double |  |
| height | double |  |
| text | java.lang.String | string teks. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Menambahkan Teks dengan PinX dan PinY yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x dari pin teks (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y dari pin teks (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar teks. |
| height | double | Menentukan tinggi teks. |
| text | java.lang.String | string teks. |
| fontName | java.lang.String | nama font teks. |
| fontColor | java.lang.String | warna font teks. |
| size | double | ukuran font teks. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Menerapkan gaya untuk seluruh halaman. Nilai default adalah -1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textStyle | int | ID Gaya teks. |
| lineStyle | int | ID Gaya garis. |
| fillStyle | int | ID Gaya isi. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Atur spasi otomatis shape.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Menentukan bentuk-bentuk diberi jarak otomatis. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Memindahkan shape, yang didefinisikan oleh ID, maju satu posisi dalam urutan z.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeId | long | ID bentuk.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Memindahkan shape, yang didefinisikan oleh ID, ke depan urutan z.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeId | long | ID bentuk.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Menyelaraskan bentuk-bentuk halaman dengan batas halaman. Menyelaraskan bentuk tidak mengubah posisi mereka relatif satu sama lain.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Menghubungkan shape via connector.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Bentuk tempat konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Lokasi pada bentuk pertama di mana konektor akan terhubung Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Lokasi pada bentuk kedua di mana konektor akan terhubung Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Menghubungkan shape via connector.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk di mana konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Lokasi pada bentuk pertama di mana konektor akan terhubung Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | ID bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Lokasi pada bentuk kedua di mana konektor akan terhubung Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | ID bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Menghubungkan shape via connector.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk di mana konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Nama koneksi pada bentuk pertama di mana konektor akan terhubung. |
| shapeToId | long | ID bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Nama koneksi pada bentuk kedua di mana konektor akan terhubung. |
| connectorId | long | ID bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Menghubungkan shape via indeks connector.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Bentuk tempat konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Indeks koneksi pada bentuk pertama |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Indeks koneksi pada bentuk kedua |
| connector | [Shape](../../com.aspose.diagram/shape) | Bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Menghubungkan shape via indeks connector.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk di mana konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Indeks koneksi pada bentuk pertama |
| shapeToId | long | ID bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Indeks koneksi pada bentuk kedua |
| connectorId | long | ID bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Proses menggambar Ellipse.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk |
| height | double | Menentukan tinggi bentuk |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Proses menggambar satu garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginX | double | Menentukan koordinat x awal posisi bentuk relatif terhadap halaman. |
| beginY | double | Menentukan koordinat y awal posisi bentuk relatif terhadap halaman. |
| endX | double | Menentukan koordinat x akhir posisi bentuk relatif terhadap halaman. |
| endY | double | Menentukan koordinat y akhir dari posisi bentuk relatif terhadap halaman. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Proses menggambar garis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk |
| height | double | Menentukan tinggi bentuk |
| xyArray | double[] | Array yang berisi nilai x dan y secara bergantian yang mendefinisikan titik-titik pada bentuk baru |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Proses menggambar Polyline.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk |
| height | double | Menentukan tinggi bentuk |
| xyArray | double[] | Array yang berisi nilai x dan y secara bergantian yang mendefinisikan titik-titik pada bentuk baru |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Proses menggambar persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| width | double | Menentukan lebar bentuk |
| height | double | Menentukan tinggi bentuk |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


ID halaman gambar asli yang ditandai pada overlay markup terpisah oleh peninjau gambar.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


Halaman latar belakang halaman.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Bendera yang menunjukkan apakah halaman tersebut adalah halaman latar belakang.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Berisi elemen Connect untuk setiap koneksi antara dua bentuk dalam gambar.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Berisi elemen yang mendefinisikan lembar halaman untuk elemen Page atau Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Koleksi halaman.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


ID peninjau yang terkait dengan overlay markup.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Koleksi bentuk.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat pertama kali dibuka.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat pertama kali dibuka.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Faktor pembesaran default yang digunakan saat tampilan (jendela) baru halaman dibuka. Misalnya, 1 = 100%; 1.5 = 150%, dan seterusnya.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Tempelkan bentuk ke Connector's BeginX

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk di mana konektor dimulai [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Nama koneksi pada bentuk tempat konektor akan terhubung. |
| connectorId | long | ID bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Tempelkan bentuk ke Connector's EndX

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeToId | long | ID bentuk di mana konektor berakhir [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Nama koneksi pada bentuk kedua di mana konektor akan terhubung. |
| connectorId | long | ID bentuk dengan tipe Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Tempelkan bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Bentuk yang dilekatkan dari [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Lokasi pada bentuk pertama tempat menempel Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Bentuk tempat menempel ke [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Tempelkan bentuk

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk yang dilekatkan dari [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Lokasi pada bentuk pertama tempat menempel Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | ID bentuk tempat menempel ke [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Tempelkan bentuk dalam kontainer

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk yang dilekatkan dari [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | Lokasi pada indeks koneksi pertama tempat menempel. |
| shapeToEndConnectionIndex | int | Lokasi pada indeks koneksi akhir tempat menempel. |
| shapeToId | long | ID bentuk tempat menempel ke [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Tempelkan bentuk dalam kontainer menggunakan nama koneksi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk yang dilekatkan dari [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | Lokasi pada nama koneksi pertama tempat menempel. |
| shapeToEndConnectionName | java.lang.String | Lokasi pada nama koneksi akhir tempat menempel. |
| shapeToId | long | ID bentuk tempat menempel ke [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Tempelkan bentuk berdasarkan id koneksi dalam kontainer

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeFromId | long | ID bentuk yang dilekatkan dari [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | Lokasi pada ID koneksi pertama tempat menempel. |
| shapeToEndConnectionID | int | Lokasi pada ID koneksi akhir tempat menempel. |
| shapeToId | long | ID bentuk tempat menempel ke [Shape](../../com.aspose.diagram/shape). |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Menyusun bentuk dan/atau mengarahkan ulang konektor untuk halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Menggunakan [LayoutOptions](../../com.aspose.diagram/layoutoptions) untuk mengonfigurasi opsi tata letak. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Memindahkan halaman ke lokasi lain dalam halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks halaman tujuan. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


Memindahkan bentuk, yang didefinisikan oleh ID, satu posisi ke belakang dalam urutan z.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeId | long | ID bentuk.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Memindahkan bentuk, yang didefinisikan oleh ID, ke belakang urutan z.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeId | long | ID bentuk.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Untuk deskripsi properti ini, silakan lihat [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Untuk deskripsi properti ini, silakan lihat [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Untuk deskripsi properti ini, silakan lihat [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Untuk deskripsi properti ini, silakan lihat [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Terapkan tema preset ke halaman ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Terapkan varian tema preset quickstyle ke halaman ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Terapkan varian tema preset ke halaman ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Untuk deskripsi properti ini, silakan lihat [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

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

