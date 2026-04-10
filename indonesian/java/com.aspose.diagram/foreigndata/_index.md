---
title: ForeignData
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi BLOB data gambar yang dikodekan dengan MIME Multipurpose Internet Mail Extensions, seperti bitmap metafile Windows atau data OLE.
type: docs
weight: 164
url: /id/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Atribut ini hanya bermakna jika data asing adalah objek asing berbasis raster, seperti file DIB, JPG, PNG, TIFF, atau GIF. |
| [getCompressionType()](#getCompressionType--) | Atribut ini hanya bermakna jika data asing adalah objek asing berbasis raster, seperti file DIB, JPG, PNG, TIFF, atau GIF. |
| [getExtentX()](#getExtentX--) | Atribut ini hanya bermakna jika data asing adalah metafile. |
| [getExtentY()](#getExtentY--) | Atribut ini hanya bermakna jika data asing adalah metafile. |
| [getForeignType()](#getForeignType--) | Tipe data. |
| [getImageData()](#getImageData--) | Mewakili gambar objek ole sebagai array byte. |
| [getMappingMode()](#getMappingMode--) | Atribut ini hanya bermakna jika data asing adalah metafile. |
| [getObjectData()](#getObjectData--) | Mewakili data objek ole yang tertanam sebagai array byte. |
| [getObjectHeight()](#getObjectHeight--) | Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Mengembalikan nama lengkap sumber dari file sumber untuk objek OLE yang ditautkan. |
| [getObjectType()](#getObjectType--) | Jika atribut ForeignType adalah "Object", elemen ForeignData juga harus memiliki atribut ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2. |
| [getShowAsIcon()](#getShowAsIcon--) | Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2. |
| [getValue()](#getValue--) | Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Untuk deskripsi properti ini, silakan lihat [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Untuk deskripsi properti ini, silakan lihat [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Untuk deskripsi properti ini, silakan lihat [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Untuk deskripsi properti ini, silakan lihat [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Untuk deskripsi properti ini, silakan lihat [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Untuk deskripsi properti ini, silakan lihat [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Untuk deskripsi properti ini, silakan lihat [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Untuk deskripsi properti ini, silakan lihat [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Untuk deskripsi properti ini, silakan lihat [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Untuk deskripsi properti ini, silakan lihat [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Untuk deskripsi properti ini, silakan lihat [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Untuk deskripsi properti ini, silakan lihat [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Untuk deskripsi properti ini, silakan lihat [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
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
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


Atribut ini hanya bermakna jika data asing adalah objek asing berbasis raster, seperti file DIB, JPG, PNG, TIFF, atau GIF. Nilai menunjukkan tingkat kompresi yang diterapkan pada file. Tingkat kompresi diukur dalam ratusan persen.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Atribut ini hanya bermakna jika data asing adalah objek asing berbasis raster, seperti file DIB, JPG, PNG, TIFF, atau GIF. Nilai menunjukkan jenis kompresi yang diterapkan pada file.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Atribut ini hanya bermakna jika data asing adalah metafile. Nilai menunjukkan ukuran horizontal metafile.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Atribut ini hanya bermakna jika data asing adalah metafile. Nilai menunjukkan ukuran vertikal metafile.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Tipe data.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Mewakili gambar objek ole sebagai array byte.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Atribut ini hanya bermakna jika data asing adalah metafile. Nilai menunjukkan mode pemetaan metafile.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Mewakili data objek ole yang tertanam sebagai array byte.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2. Nilai menyatakan tinggi objek dalam satuan halaman.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Mengembalikan nama lengkap sumber dari file sumber untuk objek OLE yang ditautkan. Hanya mendukung penetapan nama lengkap sumber ketika tipe file adalah OleFileType.Unknown. Misalnya file wav, file avi, dll.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Jika atribut ForeignType adalah "Object", elemen ForeignData juga harus memiliki atribut ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2. Nilai menyatakan lebar objek dalam satuan halaman.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Atribut ini hanya bermakna jika data asing adalah objek tertanam OLE2.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Berisi BLOB data gambar yang dikodekan MIME (Multipurpose Internet Mail Extensions), seperti metafile Windows, bitmap, atau data OLE.

**Returns:**
byte[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


Untuk deskripsi properti ini, silakan lihat [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Untuk deskripsi properti ini, silakan lihat [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Untuk deskripsi properti ini, silakan lihat [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Untuk deskripsi properti ini, silakan lihat [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Untuk deskripsi properti ini, silakan lihat [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Untuk deskripsi properti ini, silakan lihat [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Untuk deskripsi properti ini, silakan lihat [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Untuk deskripsi properti ini, silakan lihat [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Untuk deskripsi properti ini, silakan lihat [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

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

