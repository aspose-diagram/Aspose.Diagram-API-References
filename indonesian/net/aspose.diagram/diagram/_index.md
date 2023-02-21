---
title: Diagram
second_title: Aspose.Diagram untuk Referensi .NET API
description: Elemen root dari hierarki objek Visio.
type: docs
weight: 1170
url: /id/net/aspose.diagram/diagram/
---
## Diagram class

Elemen root dari hierarki objek Visio.

```csharp
public class Diagram : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Diagram](diagram/#constructor)() | Konstruktor default. |
| [Diagram](diagram/#constructor_1)(Stream) | Konstruktor kelas publik, memuat diagram dari aliran. |
| [Diagram](diagram/#constructor_4)(string) | Konstruktor kelas publik, memuat diagram dari file. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Konstruktor kelas publik, memuat diagram dari aliran menggunakan format yang telah ditentukan. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Konstruktor kelas publik, memuat diagram dari aliran menggunakan opsi file muat yang telah ditentukan. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Konstruktor kelas publik, memuat diagram dari file menggunakan format yang telah ditentukan. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Konstruktor kelas publik, memuat diagram dari file menggunakan opsi file muat yang telah ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Menentukan halaman aktif |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Nomor build dari instance Visio yang digunakan untuk membuat dokumen. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Berisi tabel warna dokumen. Setiap dokumen berisi satu tabel warna, yang mencantumkan 24 warna standar yang tersedia untuk aplikasi ke objek seperti bentuk, teks, dan lapisan dalam dokumen. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Berisi elemen DataConnection untuk dokumen. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Kumpulan objek DataRecordset yang terkait dengan objek Dokumen. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | ID unik bahasa antarmuka pengguna yang ditentukan pengguna di Preferensi Bahasa Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Berisi elemen properti dokumen seperti judul dokumen, pengarang, dan sebagainya. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Berisi elemen yang menentukan pengaturan dokumen. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Menentukan struktur ShapeSheet dokumen. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Berisi slip perutean email MAPI yang disandikan MIME (Multipurpose Internet Mail Extensions) untuk dokumen. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Berisi elemen EventItem untuk setiap kejadian yang harus ditanggapi oleh objek. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Menunjukkan jalur folder Font |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Berisi kumpulan elemen Font |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Berisi elemen untuk header dan footer dokumen. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Mendapat dan menyetel monitor interupsi. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. Jika ada, Visio akan sepenuhnya menguji konten file. Abaikan untuk file yang Anda buat di luar Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Objek Master Pengumpulan. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Apakah akan menggunakan satuan metrik dalam gambar. Setel atribut ini ke True (1) untuk menggunakan satuan metrik; atur ke False (0) untuk menggunakan satuan bahasa Inggris. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | objek Halaman Koleksi. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | Pita XML string yang diteruskan ke dokumen untuk menyesuaikan antarmuka pengguna pita. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | nilai XML. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Menunjukkan apakah dokumen telah dimodifikasi di luar Visio. Jika ada, Visio akan sepenuhnya menguji konten file. Abaikan untuk file yang Anda buat di luar Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Koleksi objek StyleSheet. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | Pita XML string yang diteruskan ke dokumen untuk mengkustomisasi bilah alat Akses Cepat atau pita. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Menyimpan informasi tentang validasi diagram untuk dokumen. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Mendapat VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Berisi data proyek Microsoft Visual Basic for Applications dalam format MIME (Multipurpose Internet Mail Extensions) yang disandikan. |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Nomor versi instans Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Berisi elemen Window untuk sebuah dokumen. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Menambahkan master ke diagram dari diagram sumber dengan Nama master atau NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Menambahkan master ke diagram dari aliran template dengan ID master. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Menambahkan master ke diagram dari aliran template dengan Nama master atau NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Menambahkan master ke diagram dari file template dengan ID master. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Menambahkan master ke diagram dari file template dengan Nama master atau NameU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Menambahkan bentuk yang dibuat oleh master ke halaman tertentu. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Menambahkan bentuk yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Menambahkan bentuk yang dibuat oleh master pada halaman dengan PinX, PinY, Lebar, dan Tinggi yang ditentukan. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Menggabungkan objek Diagram lainnya. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Menyalin Tema dari Diagram sumber. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Dapatkan jalur folder Font Default |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Dapatkan Gaya yang tidak terpakai |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Menunjukkan apakah diagram ini memiliki informasi tersembunyi. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Menampilkan bentuk dan/atau mengubah rute konektor untuk semua halaman diagram. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Mencetak seluruh dokumen ke printer default. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Mencetak dokumen sesuai dengan pengaturan printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna). |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Mencetak seluruh dokumen ke printer default. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Cetak seluruh dokumen ke printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna). |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Mencetak dokumen sesuai dengan pengaturan printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna). |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Mencetak dokumen sesuai dengan pengaturan printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Cetak seluruh dokumen ke printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna). |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Mencetak dokumen, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Mencetak dokumen sesuai dengan pengaturan printer yang ditentukan, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Mencetak dokumen, menggunakan pengontrol cetak standar (tanpa Antarmuka Pengguna) dan nama dokumen. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Memanggil metode Refresh untuk semua DataRecordSet di Diagram. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Hapus informasi yang tidak terpakai |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Menghapus VBA/makro dari diagram ini. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Menyimpan data diagram ke aliran. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Menyimpan diagram ke aliran menggunakan opsi penyimpanan yang ditentukan. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Menyimpan data diagram ke file. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Menyimpan dokumen ke file menggunakan opsi penyimpanan yang ditentukan. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Mengekspor diagram dari aliran vsd ke format aliran vdw. Belum diterapkan. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Mengekspor diagram dari aliran vsd ke format file *.vdw. Belum diterapkan. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Mengekspor diagram dari file vsd ke format aliran vdw. Belum diterapkan. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Mengekspor diagram dari format vsd ke vdw. Belum diterapkan. |

### Lihat juga

* ruang nama [Aspose.Diagram](../../aspose.diagram/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
