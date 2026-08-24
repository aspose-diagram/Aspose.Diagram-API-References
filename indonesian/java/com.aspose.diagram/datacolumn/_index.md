---
title: DataColumn
second_title: Referensi API Aspose.Diagram untuk Java
description: Mendefinisikan cara kolom data muncul di jendela External Data pada antarmuka pengguna Visio dan mengkualifikasi data dalam kolom dengan menentukan tipe data serta pemformatannya.
type: docs
weight: 108
url: /id/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Mendefinisikan cara kolom data muncul di jendela External Data pada antarmuka pengguna Visio dan mengkualifikasi data dalam kolom dengan menentukan tipe data serta pemformatannya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DataColumn()](#DataColumn--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | ID Kalender dari kolom data. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | Nama eksternal dari kolom data. |
| [getCurrency()](#getCurrency--) | ID Mata uang dari kolom data. |
| [getDataType()](#getDataType--) | Tipe data dalam kolom data. |
| [getDegree()](#getDegree--) | Menentukan derajat (pangkat) satuan, misalnya kuadrat, atau kubik. |
| [getDisplayOrder()](#getDisplayOrder--) | Mendefinisikan posisi tampilan kolom data di jendela Data Eksternal, dari kolom paling kiri (0) hingga kolom paling kanan (nilai terbesar). |
| [getDisplayWidth()](#getDisplayWidth--) | Lebar kolom data di jendela Data Eksternal. |
| [getHyperlink()](#getHyperlink--) | Apakah kolom data membuat hyperlink dalam bentuk ketika bentuk tersebut terhubung ke data. |
| [getLabel()](#getLabel--) | Label kolom data. |
| [getLangID()](#getLangID--) | ID bahasa kolom data |
| [getMapped()](#getMapped--) | Menentukan apakah kolom terlihat di jendela Data Eksternal. |
| [getName()](#getName--) | Nama internal kolom data. |
| [getOrigLabel()](#getOrigLabel--) | Label kolom yang dikembalikan ke Visio oleh antarmuka ADO yang mendasarinya. |
| [getUnitType()](#getUnitType--) | Jenis unit data dalam kolom data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--) |
| [setCurrency(int value)](#setCurrency-int-) | Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getCurrency() & 0xFFFF)\} |
| [setDataType(int value)](#setDataType-int-) | Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getDataType() & 0xFFFF)\} |
| [setDegree(long value)](#setDegree-long-) | Untuk deskripsi properti ini, silakan lihat [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--) |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | Untuk deskripsi properti ini, silakan lihat [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--) |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | Untuk deskripsi properti ini, silakan lihat [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--) |
| [setHyperlink(int value)](#setHyperlink-int-) | Untuk deskripsi properti ini, silakan lihat [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--) |
| [setLabel(String value)](#setLabel-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--) |
| [setLangID(long value)](#setLangID-long-) | Untuk deskripsi properti ini, silakan lihat [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--) |
| [setMapped(int value)](#setMapped-int-) | Untuk deskripsi properti ini, silakan lihat [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--) |
| [setName(String value)](#setName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/datacolumn\#getName--) |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--) |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


ID Kalender dari kolom data.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


Nama eksternal kolom data. Muncul di judul pada jendela Data Eksternal dan pada label dalam grafik data.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


ID Mata uang dari kolom data.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


Tipe data dalam kolom data.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


Menentukan derajat (pangkat) unit, misalnya kuadrat, atau kubik. Nilai default (atribut tidak ada) adalah 1.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


Mendefinisikan posisi tampilan kolom data di jendela Data Eksternal, dari kolom paling kiri (0) hingga kolom paling kanan (nilai terbesar).

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


Lebar kolom data di jendela Data Eksternal.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


Apakah kolom data membuat hyperlink dalam bentuk ketika bentuk tersebut terhubung ke data.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


Label kolom data.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


ID bahasa kolom data

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


Menentukan apakah kolom terlihat di jendela Data Eksternal. True (1) agar kolom terlihat; false (0) agar kolom tidak terlihat. Nilai default (atribut tidak ada) adalah kolom terlihat.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Nama internal kolom data. Digunakan sebagai nama baris untuk item shape-data (properti khusus) yang ditambahkan ke bentuk ketika bentuk tersebut terhubung ke baris data.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


Label kolom yang dikembalikan ke Visio oleh antarmuka ADO yang mendasarinya.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


Jenis unit data dalam kolom data.

**Returns:**
java.lang.String
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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


Untuk deskripsi properti ini, silakan lihat [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getCurrency() & 0xFFFF)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataColumn\#(getDataType() & 0xFFFF)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


Untuk deskripsi properti ini, silakan lihat [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


Untuk deskripsi properti ini, silakan lihat [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


Untuk deskripsi properti ini, silakan lihat [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


Untuk deskripsi properti ini, silakan lihat [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


Untuk deskripsi properti ini, silakan lihat [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


Untuk deskripsi properti ini, silakan lihat [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


Untuk deskripsi properti ini, silakan lihat [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getName()](../../com.aspose.diagram/datacolumn\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


Untuk deskripsi properti ini, silakan lihat [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


Untuk deskripsi properti ini, silakan lihat [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)

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

