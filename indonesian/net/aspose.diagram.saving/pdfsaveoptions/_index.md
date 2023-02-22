---
title: PdfSaveOptions
second_title: Aspose.Diagram untuk Referensi .NET API
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke PDF.
type: docs
weight: 3410
url: /id/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen di[`Pdf`](../../aspose.diagram/savefileformat/) format. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Mendapat atau mengatur luas bentuk yang akan disimpan . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Tingkat kesesuaian yang diinginkan untuk dokumen PDF yang dihasilkan. Standarnya adalahPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Ketika karakter dalam diagram adalah unicode dan tidak diatur dengan nilai font yang benar atau font tidak diinstal secara lokal, mereka mungkin muncul sebagai blok di pdf, gambar atau XPS. Atur DefaultFont seperti MingLiu atau MS Gothic untuk menampilkannya karakter. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Mendapat atau menyetel detail tanda tangan digital. Jika tidak disetel, penandatanganan tidak akan dilakukan. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Pengaturan untuk merender metafile Emf. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Mendapat atau menyetel detail enkripsi. Jika tidak disetel, enkripsi tidak akan dilakukan. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Menentukan apakah memperbesar halaman . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Menentukan apakah perlu mengekspor bentuk panduan atau tidak. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Mendefinisikan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Mendapat atau mengatur resolusi horizontal untuk gambar yang dihasilkan, dalam titik per inci. Menerapkan metode pembuatan gambar kecuali gambar format Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Mendefinisikan apakah perlu mengekspor komentar atau tidak. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Menentukan kualitas kompresi JPEG untuk gambar (jika kompresi JPEG digunakan). Standarnya adalah 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Mendapat atau mengatur jumlah halaman yang akan dirender dalam PDF. Defaultnya adalah MaxValue yang berarti semua halaman diagram akan dirender. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Mendapat atau menyetel indeks berbasis 0 dari halaman pertama yang akan dirender. Standarnya adalah 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Mengontrol/Menunjukkan kemajuan proses penyimpanan halaman. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Mendapat atau mengatur ukuran halaman untuk gambar yang dihasilkan. Bisa jadi[`PageSize`](../pagesize/) atau null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. Bisa jadi[`PDF`](../../aspose.diagram/savefileformat/) hanya. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Mendapat atau mengatur bentuk untuk dirender. Hitungan default adalah 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Menentukan apakah membagi diagram menjadi beberapa halaman sesuai dengan pengaturan halaman. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Menentukan jenis kompresi yang akan digunakan untuk semua aliran konten kecuali gambar. Standarnya adalahFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Mendapat atau menyetel resolusi vertikal untuk gambar yang dihasilkan, dalam titik per inci. Menerapkan metode pembuatan gambar kecuali gambar format Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Mendapat atau menyetel callback peringatan. |

### Lihat juga

* class [RenderingSaveOptions](../renderingsaveoptions/)
* ruang nama [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
