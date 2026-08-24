---
title: DataRecordSet
second_title: Referensi API Aspose.Diagram untuk Java
description: Menyimpan format, menyegarkan, dan menampilkan data yang diquery dari basis data di Microsoft Visio.
type: docs
weight: 113
url: /id/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Menyimpan, memformat, menyegarkan, dan menampilkan data yang diambil dari basis data di Microsoft Visio.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Berisi XML yang sesuai dengan skema XML klasik ADO untuk recordset ADO dan yang menggambarkan data dalam recordset data. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Mendefinisikan aturan yang membandingkan kolom dalam elemen DataRecordset induk dengan item data bentuk dari tindakan penautan otomatis terakhir yang berhasil dilakukan di antarmuka pengguna. |
| [getChecksum()](#getChecksum--) | Nilai checksum, dihasilkan oleh Visio, dan berdasarkan properti data-recordset. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | String perintah yang digunakan untuk mengquery data dari sumber data. |
| [getConnectionID()](#getConnectionID--) | ID koneksi untuk objek DataConnection yang terkait. |
| [getDataColumns()](#getDataColumns--) | Berisi semua elemen DataColumn dalam recordset data. |
| [getID()](#getID--) | ID recordset data, unik dalam dokumen. |
| [getName()](#getName--) | Nama tampilan (atau "friendly") dari recordset data. |
| [getNextRowID()](#getNextRowID--) | ID baris Visio berikutnya yang tersedia. |
| [getOptions()](#getOptions--) | Opsi yang diterapkan pada recordset data. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Mengidentifikasi satu atau lebih kolom primary-key dalam recordset data. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Menunjukkan baris dalam recordset data yang terhubung ke bentuk yang mengalami konflik setelah recordset data disegarkan. |
| [getRefreshInterval()](#getRefreshInterval--) | Seberapa sering (dalam menit) Visio menyegarkan recordset data secara otomatis. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Apakah antarmuka pengguna data-reconciliation harus dinonaktifkan. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Apakah menimpa perubahan pengguna pada item data bentuk dalam bentuk yang terhubung ke data ketika recordset data disegarkan. |
| [getReplaceLinks()](#getReplaceLinks--) | Mendefinisikan bagaimana tautan shape-data diperlakukan ketika bentuk disalin atau dipotong. 1 untuk mengganti tautan yang ada pada bentuk target. 0 untuk mempertahankan tautan yang ada pada bentuk target. |
| [getRowMaps()](#getRowMaps--) | Memetakan baris data-recordset ke sebuah bentuk. |
| [getRowOrder()](#getRowOrder--) | Apakah menggunakan urutan baris dalam recordset data sebagai primary key. |
| [getTimeRefreshed()](#getTimeRefreshed--) | Tanggal dan waktu recordset data terakhir disegarkan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Menjalankan string query yang terkait dengan DataRecordset yang terhubung (bukan berbasis XML) dan memperbarui bentuk yang terhubung dengan data baru dari sumber data yang dikembalikan oleh query. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | For the description of this property, please see \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | For the description of this property, please see [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | For the description of this property, please see \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | For the description of this property, please see [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | For the description of this property, please see [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | For the description of this property, please see [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | For the description of this property, please see [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
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
### getADOData() {#getADOData--}
```
public String getADOData()
```


Berisi XML yang sesuai dengan skema XML klasik ADO untuk recordset ADO dan yang menggambarkan data dalam recordset data.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Mendefinisikan aturan yang membandingkan kolom dalam elemen DataRecordset induk dengan item data bentuk dari tindakan penautan otomatis terakhir yang berhasil dilakukan di antarmuka pengguna.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


A checksum value, generated by Visio, and based on data-recordset properties. Set this attribute to 0; Visio recalculates this value at runtime.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


String perintah yang digunakan untuk mengquery data dari sumber data.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


The connection ID for the associated DataConnection object. Does not exist for XML data sources.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Berisi semua elemen DataColumn dalam recordset data.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


ID recordset data, unik dalam dokumen.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Nama tampilan (atau "friendly") dari recordset data.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


ID baris Visio berikutnya yang tersedia.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Mengidentifikasi satu atau lebih kolom primary-key dalam recordset data.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed. RowID - Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed. ShapeID - Shape ID of the shape involved in the conflict. PageID - Page ID of the shape involved in the conflict.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


How often (in minutes) Visio refreshes the data recordset automatically. This value must be 1 or larger.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Whether the data-reconciliation user interface should be disabled. True (1) to disable the user interface (UI). False (0) to enable the UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Apakah menimpa perubahan pengguna pada item data bentuk dalam bentuk yang terhubung ke data ketika recordset data disegarkan.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Defines how shape-data links are treated when shapes are copied or cut. 1 to replace existing links in the target shape. 0 to maintain existing links in the target shape. If this attribute is absent, Visio asks the user whether to replace links on copy or cut.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Maps a data-recordset row to a shape. RowID - Row ID of the row, unique within the data recordset. ShapeID - Shape ID of the shape linked to data in the data-recordset row identified by RowID. PageID - Page ID of the shape linked to data in the data-recordset row identified by RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Whether to use the order of the rows in the data recordset as the primary key. True (1) if row IDs are determined by row order. False (0) if row IDs are determined by values in the primary key column(s) of the data recordset.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


Tanggal dan waktu recordset data terakhir disegarkan.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


Menjalankan string query yang terkait dengan DataRecordset yang terhubung (bukan berbasis XML) dan memperbarui bentuk yang terhubung dengan data baru dari sumber data yang dikembalikan oleh query.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| connectionType | int | The type of provider which will be used for connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Untuk deskripsi properti ini, silakan lihat [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Untuk deskripsi properti ini, silakan lihat [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Untuk deskripsi properti ini, silakan lihat \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


For the description of this property, please see \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


For the description of this property, please see [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


For the description of this property, please see \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


For the description of this property, please see [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


For the description of this property, please see [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


For the description of this property, please see [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


For the description of this property, please see [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


For the description of this property, please see [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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

