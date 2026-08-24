---
title: Master
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen yang mendefinisikan master untuk dokumen.
type: docs
weight: 240
url: /id/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Berisi elemen yang mendefinisikan master untuk dokumen. Master adalah bentuk pada stensil yang Anda gunakan berulang kali untuk membuat gambar. Ketika Anda menyeret bentuk dari stensil ke halaman gambar, bentuk tersebut menjadi instance dari master itu, dan salinan lokal master disertakan dalam dokumen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Master()](#Master--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Menentukan apakah teks master dalam jendela stensil disejajarkan kiri, kanan, atau tengah. |
| [getBaseID()](#getBaseID--) | GUID (pengidentifikasi unik global) yang mengidentifikasi master di seluruh dokumen. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Berisi elemen Connect untuk setiap koneksi antara dua bentuk dalam gambar. |
| [getHidden()](#getHidden--) | Menentukan apakah master disembunyikan dalam antarmuka pengguna. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getIcon()](#getIcon--) | Menentukan ikon biner yang dikodekan MIME (Multipurpose Internet Mail Extensions) (dalam format .ico) untuk elemen Master atau MasterShortcut dalam dokumen. |
| [getIconSize()](#getIconSize--) | Ukuran ikon elemen. |
| [getIconUpdate()](#getIconUpdate--) | Menentukan apakah ikon dihasilkan secara otomatis dari master itu sendiri. |
| [getMatchByName()](#getMatchByName--) | Atribut MatchByName menentukan bagaimana Microsoft Visio memutuskan apakah master dokumen sudah ada ketika sebuah instance master dijatuhkan pada halaman gambar. |
| [getName()](#getName--) | Nama elemen. |
| [getNameU()](#getNameU--) | Nama universal elemen. |
| [getPageSheet()](#getPageSheet--) | Berisi elemen yang mendefinisikan lembar halaman untuk elemen Page atau Master. |
| [getPatternFlags()](#getPatternFlags--) | Atribut PatternFlags menentukan apakah master berperilaku sebagai pola khusus. |
| [getPrompt()](#getPrompt--) | Bar status dan petunjuk tooltip untuk elemen. |
| [getShapes()](#getShapes--) | Koleksi objek Shape. |
| [getUniqueID()](#getUniqueID--) | GUID yang mengidentifikasi master dalam dokumen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Untuk deskripsi properti ini, silakan lihat [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Untuk deskripsi properti ini, silakan lihat [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Untuk deskripsi properti ini, silakan lihat [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Untuk deskripsi properti ini, silakan lihat [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Untuk deskripsi properti ini, silakan lihat [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Untuk deskripsi properti ini, silakan lihat [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Untuk deskripsi properti ini, silakan lihat [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Untuk deskripsi properti ini, silakan lihat [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan mendalam dari instance ini.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Menentukan apakah teks master dalam jendela stensil disejajarkan kiri, kanan, atau tengah.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


GUID (pengidentifikasi unik global) yang mengidentifikasi master di seluruh dokumen.

**Returns:**
java.util.UUID
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
### getHidden() {#getHidden--}
```
public int getHidden()
```


Menentukan apakah master disembunyikan dalam antarmuka pengguna.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Menentukan ikon biner yang dikodekan MIME (Multipurpose Internet Mail Extensions) (dalam format .ico) untuk elemen Master atau MasterShortcut dalam dokumen.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


Ukuran ikon elemen.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Menentukan apakah ikon dihasilkan secara otomatis dari master itu sendiri.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


Atribut MatchByName menentukan bagaimana Microsoft Visio memutuskan apakah master dokumen sudah ada ketika sebuah instance master dijatuhkan pada halaman gambar. Ini memungkinkan perubahan yang dibuat pada master dokumen diterapkan pada instance baru master, bahkan jika instance tersebut diseret dari file stensil mandiri.

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
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


Atribut PatternFlags menentukan apakah master berperilaku sebagai pola khusus.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


Bar status dan petunjuk tooltip untuk elemen.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Koleksi objek Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID yang mengidentifikasi master dalam dokumen.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Untuk deskripsi properti ini, silakan lihat [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Untuk deskripsi properti ini, silakan lihat [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Untuk deskripsi properti ini, silakan lihat [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Untuk deskripsi properti ini, silakan lihat [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Untuk deskripsi properti ini, silakan lihat [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Untuk deskripsi properti ini, silakan lihat [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

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

