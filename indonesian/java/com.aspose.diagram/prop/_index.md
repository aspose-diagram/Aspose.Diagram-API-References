---
title: Properti
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen untuk mendefinisikan properti khusus dan elemen untuk mengaitkan data dengan sebuah bentuk.
type: docs
weight: 309
url: /id/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Berisi elemen untuk mendefinisikan properti khusus dan elemen untuk mengaitkan data dengan sebuah bentuk.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Prop()](#Prop--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Menentukan kalender yang digunakan untuk properti khusus, bidang teks, dan rumus elemen. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getFormat()](#getFormat--) | Elemen format menentukan pemformatan properti khusus yang berupa string, daftar tetap, angka, daftar variabel, tanggal atau waktu, durasi, atau mata uang. |
| [getID()](#getID--) | ID unik elemen dalam elemen induknya. |
| [getIX()](#getIX--) | Indeks berbasis nol dari elemen dalam elemen induknya. |
| [getInvisible()](#getInvisible--) | Elemen tidak terlihat menentukan apakah properti khusus terlihat di kotak dialog Properti Khusus di Microsoft Visio. |
| [getLabel()](#getLabel--) | Menentukan label yang muncul kepada pengguna di kotak dialog Properti Khusus. |
| [getLangID()](#getLangID--) | Menunjukkan ID lokal (LCID) bahasa di mana formula sel, teks, properti khusus, atau komentar dimasukkan. |
| [getName()](#getName--) | Nama elemen. |
| [getNameU()](#getNameU--) | Nama universal elemen. |
| [getPrompt()](#getPrompt--) | Elemen prompt menentukan teks deskriptif atau instruksional yang muncul kepada pengguna di kotak dialog Properti Khusus ketika properti dipilih. |
| [getSortKey()](#getSortKey--) | Ini menentukan kunci yang menentukan urutan properti khusus ditampilkan dalam antarmuka pengguna aplikasi. |
| [getType()](#getType--) | Tipe menentukan jenis data untuk nilai properti khusus. |
| [getValue()](#getValue--) | Berisi data XML yang baik terbentuk khusus solusi, yang memiliki prefiks dalam namespace eksplisit dan disimpan bersama dokumen. |
| [getVerify()](#getVerify--) | Menentukan apakah pengguna diminta memasukkan informasi properti khusus untuk sebuah bentuk ketika sebuah instance dibuat atau bentuk tersebut digandakan atau disalin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Membuat salinan mendalam dari instance ini.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Menentukan kalender yang digunakan untuk properti khusus, bidang teks, dan rumus elemen.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Elemen Format menentukan pemformatan properti khusus yang berupa string, daftar tetap, angka, daftar variabel, tanggal atau waktu, durasi, atau mata uang. Jenis properti khusus ditentukan dalam elemen Type yang bersangkutan.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


ID unik elemen dalam elemen induknya.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Indeks berbasis nol dari elemen dalam elemen induknya.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Elemen tidak terlihat menentukan apakah properti khusus terlihat di kotak dialog Properti Khusus di Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Menentukan label yang muncul kepada pengguna di kotak dialog Properti Khusus.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Menunjukkan ID lokal (LCID) bahasa di mana formula sel, teks, properti khusus, atau komentar dimasukkan.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Elemen Prompt menentukan teks deskriptif atau instruksional yang muncul kepada pengguna dalam kotak dialog Properti Kustom ketika properti dipilih. Teks ini juga muncul sebagai tip alat ketika penunjuk mouse berhenti di atas properti dalam jendela Properti Kustom.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Ini menentukan kunci yang menentukan urutan properti khusus ditampilkan dalam antarmuka pengguna aplikasi.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Tipe menentukan jenis data untuk nilai properti khusus.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Berisi data XML yang baik terbentuk khusus solusi, yang memiliki prefiks dalam namespace eksplisit dan disimpan bersama dokumen.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Menentukan apakah pengguna diminta memasukkan informasi properti khusus untuk sebuah bentuk ketika sebuah instance dibuat atau bentuk tersebut digandakan atau disalin.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Untuk deskripsi properti ini, silakan lihat [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

