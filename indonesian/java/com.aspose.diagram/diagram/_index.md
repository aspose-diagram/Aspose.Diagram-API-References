---
title: Diagram
second_title: Referensi API Aspose.Diagram untuk Java
description: Elemen akar hierarki objek Visio.
type: docs
weight: 117
url: /id/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Elemen akar hierarki objek Visio.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Konstruktor kelas publik, memuat diagram dari file. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Konstruktor kelas publik, memuat diagram dari aliran. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Konstruktor kelas publik, memuat diagram dari aliran menggunakan format yang telah ditentukan. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Konstruktor kelas publik, memuat diagram dari aliran menggunakan opsi pemuatan file yang telah ditentukan. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Konstruktor kelas publik, memuat diagram dari file menggunakan format yang telah ditentukan. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Konstruktor kelas publik, memuat diagram dari file menggunakan opsi pemuatan file yang telah ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Menambahkan master ke diagram dari diagram sumber berdasarkan Name atau NameU master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Menambahkan master ke diagram dari aliran templat berdasarkan ID master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Menambahkan master ke diagram dari aliran templat berdasarkan Name atau NameU master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Menambahkan master ke diagram dari file templat berdasarkan ID master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Menambahkan master ke diagram dari file templat berdasarkan Name atau NameU master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Menambahkan shape yang dibuat oleh master ke halaman tertentu. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Menambahkan shape yang dibuat oleh master pada halaman dengan PinX,PinY,Width, dan Height yang ditentukan. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Menambahkan shape yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Menggabungkan objek Diagram lain. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Menyalin Tema dari Diagram sumber. |
| [dispose()](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Mengekspor diagram dari aliran vsd ke format aliran vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Mengekspor diagram dari aliran vsd ke format file \*.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Mengekspor diagram dari file vsd ke format aliran vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Mengekspor diagram dari vsd ke format vdw. |
| [getActivePage()](#getActivePage--) | Menentukan halaman aktif |
| [getBuildnum()](#getBuildnum--) | Nomor build dari instance Visio yang digunakan untuk membuat dokumen. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Berisi tabel warna dokumen. |
| [getDataConnections()](#getDataConnections--) | Berisi elemen DataConnection untuk dokumen. |
| [getDataRecordSets()](#getDataRecordSets--) | Koleksi objek DataRecordset yang terkait dengan objek Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Dapatkan jalur folder Font Default |
| [getDocLangID()](#getDocLangID--) | ID unik bahasa antarmuka pengguna yang telah ditentukan pengguna di Preferensi Bahasa Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Berisi elemen properti dokumen seperti judul dokumen, penulis, dan sebagainya. |
| [getDocumentSettings()](#getDocumentSettings--) | Berisi elemen yang menentukan pengaturan dokumen. |
| [getDocumentSheet()](#getDocumentSheet--) | Menentukan struktur ShapeSheet dokumen. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Berisi slip perutean email MAPI yang dienkode MIME (Multipurpose Internet Mail Extensions) untuk dokumen. |
| [getEventItems()](#getEventItems--) | Berisi elemen EventItem untuk setiap peristiwa yang harus ditanggapi oleh objek. |
| [getFonts()](#getFonts--) | Berisi kumpulan elemen Font |
| [getHeaderFooter()](#getHeaderFooter--) | Berisi elemen untuk header dan footer dokumen. |
| [getInterruptMonitor()](#getInterruptMonitor--) | monitor interupsi. |
| [getKey()](#getKey--) | Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. |
| [getMasters()](#getMasters--) | Koleksi objek Master. |
| [getMetric()](#getMetric--) | Apakah menggunakan satuan metrik dalam gambar. |
| [getPages()](#getPages--) | Koleksi objek Page. |
| [getRibbonX()](#getRibbonX--) | String Ribbon XML yang diteruskan ke dokumen untuk menyesuaikan antarmuka pengguna ribbon. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Nilai XML. |
| [getStart()](#getStart--) | Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. |
| [getStyleSheets()](#getStyleSheets--) | Koleksi objek StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Dapatkan Gaya yang tidak terpakai |
| [getUserCustomUI()](#getUserCustomUI--) | String Ribbon XML yang diteruskan ke dokumen untuk menyesuaikan toolbar Akses Cepat atau ribbon. |
| [getValidation()](#getValidation--) | Menyimpan informasi tentang validasi diagram untuk dokumen. |
| [getVbProjectData()](#getVbProjectData--) | Berisi data proyek Microsoft Visual Basic for Applications dalam format yang dienkode MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Mendapatkan VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Nomor versi dari instance Visio. |
| [getWindows()](#getWindows--) | Berisi elemen Window untuk sebuah dokumen. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Menunjukkan apakah diagram ini memiliki informasi tersembunyi. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Menata bentuk dan/atau mengarahkan ulang konektor untuk semua halaman diagram. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Cetak seluruh dokumen ke printer yang ditentukan, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna). |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Cetak seluruh dokumen ke printer yang ditentukan, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna). |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Mencetak dokumen, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Mencetak dokumen, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Hapus informasi yang tidak terpakai |
| [removeMacro()](#removeMacro--) | Menghapus VBA/makro dari diagram ini. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Simpan diagram ke aliran. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Simpan diagram ke aliran. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Menyimpan dokumen ke file menggunakan opsi penyimpanan yang ditentukan. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Menyimpan data diagram ke file. |
| [setBuildnum(long value)](#setBuildnum-long-) | Untuk deskripsi properti ini, silakan lihat [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Untuk deskripsi properti ini, silakan lihat [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Untuk deskripsi properti ini, silakan lihat [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Menunjukkan jalur folder Fonts |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Untuk deskripsi properti ini, silakan lihat [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Untuk deskripsi properti ini, silakan lihat [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Untuk deskripsi properti ini, silakan lihat [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Untuk deskripsi properti ini, silakan lihat [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Konstruktor kelas publik, memuat diagram dari file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Nama file. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Konstruktor kelas publik, memuat diagram dari aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Konstruktor kelas publik, memuat diagram dari aliran menggunakan format yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data. |
| format | int | Data Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Konstruktor kelas publik, memuat diagram dari aliran menggunakan opsi pemuatan file yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran data. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Konstruktor kelas publik, memuat diagram dari file menggunakan format yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Nama file. |
| format | int | Format file. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Konstruktor kelas publik, memuat diagram dari file menggunakan opsi pemuatan file yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Nama file. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Menambahkan master ke diagram dari diagram sumber berdasarkan Name atau NameU master.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | diagram sumber. |
| masterName | java.lang.String | Nama Master atau NameU. |

**Returns:**
int - ID unik master dalam koleksi master pada diagram ini.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Menambahkan master ke diagram dari aliran templat berdasarkan ID master.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templateStream | java.io.InputStream | aliran templat. |
| masterID | int | ID unik master dalam koleksi master pada templat. |

**Returns:**
int - ID unik master dalam koleksi master pada diagram ini.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Menambahkan master ke diagram dari aliran templat berdasarkan Name atau NameU master.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templateStream | java.io.InputStream | aliran templat. |
| masterName | java.lang.String | Nama Master atau NameU. |

**Returns:**
int - ID unik master dalam koleksi master pada diagram ini.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Menambahkan master ke diagram dari file templat berdasarkan ID master.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templateFilePath | java.lang.String | Jalur ke file templat (bisa format vdx, vst, atau vsd). |
| masterID | int | ID unik master dalam koleksi master pada templat. |

**Returns:**
int - ID unik master dalam koleksi master pada diagram ini.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Menambahkan master ke diagram dari file templat berdasarkan Name atau NameU master.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templateFilePath | java.lang.String | Jalur ke file templat (bisa format vdx, vst, atau vsd). |
| masterName | java.lang.String | Nama Master atau NameU. |

**Returns:**
int - ID unik master dalam koleksi master pada diagram ini.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Menambahkan shape yang dibuat oleh master ke halaman tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Objek bentuk baru[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nama master. |
| pageNumber | int | Indeks halaman. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
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
| pageNumber | int | Indeks halaman. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Menambahkan shape yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pinX | double | Menentukan koordinat x pin bentuk (pusat rotasi) relatif terhadap halaman. |
| pinY | double | Menentukan koordinat y pin bentuk (pusat rotasi) relatif terhadap halaman. |
| masterName | java.lang.String | Nama master. |
| pageNumber | int | Indeks halaman. |

**Returns:**
long - ID unik bentuk dalam koleksi bentuk pada halaman yang ditentukan.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Menggabungkan objek Diagram lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Objek Diagram lain. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Menyalin Tema dari Diagram sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | diagram sumber. |

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Mengekspor diagram dari aliran vsd ke format aliran vdw. Belum diimplementasikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputVsd | java.io.InputStream | aliran vsd. |
| outputVdw | java.io.InputStream | aliran vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Mengekspor diagram dari aliran vsd ke format file \*.vdw. Belum diimplementasikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Nama file \*.vsd. |
| outputVdw | java.lang.String | aliran vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Mengekspor diagram dari file vsd ke format aliran vdw. Belum diimplementasikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputVsd | java.lang.String | Nama file \*.vsd. |
| outputVdw | java.io.InputStream | aliran vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Mengekspor diagram dari vsd ke format vdw. Belum diimplementasikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputVsd | java.lang.String | Nama file \*.vsd. |
| outputVdw | java.lang.String | Nama file \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Menentukan halaman aktif

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Nomor build dari instance Visio yang digunakan untuk membuat dokumen.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Berisi tabel warna dokumen. Setiap dokumen memiliki satu tabel warna, yang mencantumkan 24 warna standar yang tersedia untuk diterapkan pada objek seperti shape, teks, dan lapisan dalam dokumen.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Berisi elemen DataConnection untuk dokumen.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Koleksi objek DataRecordset yang terkait dengan objek Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Dapatkan jalur folder Font Default

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


ID unik bahasa antarmuka pengguna yang telah ditentukan pengguna di Preferensi Bahasa Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Berisi elemen properti dokumen seperti judul dokumen, penulis, dan sebagainya.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Berisi elemen yang menentukan pengaturan dokumen.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Menentukan struktur ShapeSheet dokumen.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Berisi slip perutean email MAPI yang dienkode MIME (Multipurpose Internet Mail Extensions) untuk dokumen.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Berisi elemen EventItem untuk setiap peristiwa yang harus ditanggapi oleh objek.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Berisi kumpulan elemen Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Berisi elemen untuk header dan footer dokumen.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


monitor interupsi.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. Jika ada, Visio akan menguji sepenuhnya isi file. Abaikan untuk file yang Anda buat di luar Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Koleksi objek Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Apakah akan menggunakan satuan metrik dalam gambar. Atur atribut ini ke True (1) untuk menggunakan satuan metrik; atur ke False (0) untuk menggunakan satuan Inggris.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Koleksi objek Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


String Ribbon XML yang diteruskan ke dokumen untuk menyesuaikan antarmuka pengguna ribbon.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Nilai XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. Jika ada, Visio akan menguji sepenuhnya isi file. Abaikan untuk file yang Anda buat di luar Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Koleksi objek StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Dapatkan Gaya yang tidak terpakai

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


String Ribbon XML yang diteruskan ke dokumen untuk menyesuaikan toolbar Akses Cepat atau ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Menyimpan informasi tentang validasi diagram untuk dokumen.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Berisi data proyek Microsoft Visual Basic for Applications dalam format yang dienkode MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Mendapatkan VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Nomor versi dari instance Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Berisi elemen Window untuk sebuah dokumen.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Menunjukkan apakah diagram ini memiliki informasi tersembunyi.

**Returns:**
boolean
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


Menata bentuk dan/atau mengarahkan ulang konektor untuk semua halaman diagram.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Menggunakan [LayoutOptions](../../com.aspose.diagram/layoutoptions) untuk mengonfigurasi opsi tata letak. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Mencetak seluruh dokumen ke printer yang ditentukan, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna). Jika printerName bernilai Null atau kosong, printer default akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| printerName | java.lang.String | Nama printer. Bisa Null. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Mencetak seluruh dokumen ke printer yang ditentukan, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna). Jika printerName bernilai Null atau kosong, printer default akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| printerName | java.lang.String | Nama printer. Bisa Null. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Opsi pencetakan. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Mencetak dokumen, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna) dan nama dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| printerName | java.lang.String | Nama printer. Bisa Null. |
| documentName | java.lang.String | Nama dokumen yang ditampilkan (misalnya, dalam kotak dialog status pencetakan atau antrian printer) saat mencetak dokumen. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Mencetak dokumen, menggunakan kontrol pencetakan standar (tanpa Antarmuka Pengguna) dan nama dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| printerName | java.lang.String | Nama printer. Bisa Null. |
| documentName | java.lang.String | Nama dokumen yang ditampilkan (misalnya, dalam kotak dialog status pencetakan atau antrian printer) saat mencetak dokumen. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Opsi pencetakan. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Hapus informasi yang tidak terpakai

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Menghapus VBA/makro dari diagram ini.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Simpan diagram ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | The file stream. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | The save options. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Simpan diagram ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | The file stream. |
| format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Menyimpan dokumen ke file menggunakan opsi penyimpanan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Nama file. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) save diagram options. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Menyimpan data diagram ke file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | java.lang.String | Nama file. |
| format | int | Aspose.Diagram.SaveFileFormat save file format. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Untuk deskripsi properti ini, silakan lihat [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Menunjukkan jalur folder Fonts

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Untuk deskripsi properti ini, silakan lihat [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Untuk deskripsi properti ini, silakan lihat [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Untuk deskripsi properti ini, silakan lihat [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Untuk deskripsi properti ini, silakan lihat [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Untuk deskripsi properti ini, silakan lihat [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Untuk deskripsi properti ini, silakan lihat [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Untuk deskripsi properti ini, silakan lihat [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

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

