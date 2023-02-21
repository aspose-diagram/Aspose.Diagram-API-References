---
title: ImageSaveOptions
second_title: Aspose.Diagram untuk Referensi .NET API
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram menjadi gambar.
type: docs
weight: 3280
url: /id/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram menjadi gambar.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan gambar yang dirender di[`Bertengkar`](../../aspose.diagram/savefileformat/) , [`png`](../../aspose.diagram/savefileformat/) ,[`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) atau[`Jpeg`](../../aspose.diagram/savefileformat/) format. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Mendapat atau mengatur luas bentuk yang akan disimpan . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Menentukan tingkat kualitas untuk digunakan selama pengomposisian. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Parameter ini mirip dengan skala, tetapi tidak mempengaruhi ukuran gambar yang dihasilkan. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Ketika karakter dalam diagram adalah unicode dan tidak diatur dengan nilai font yang benar atau font tidak diinstal secara lokal, mereka mungkin muncul sebagai blok di pdf, gambar atau XPS. Atur DefaultFont seperti MingLiu atau MS Gothic untuk menampilkannya karakter. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Pengaturan untuk merender metafile Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Menentukan apakah memperbesar halaman . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Menentukan apakah perlu mengekspor bentuk panduan atau tidak. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Mendefinisikan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Mendapat atau mengatur kecerahan untuk gambar yang dihasilkan. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Mendapat atau menyetel mode warna untuk gambar yang dihasilkan. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Mendapat atau menyetel kontras untuk gambar yang dihasilkan. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Menentukan algoritme yang digunakan saat gambar diskalakan atau diputar. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Mendefinisikan apakah perlu mengekspor komentar atau tidak. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Mendapat atau menetapkan nilai yang menentukan kualitas gambar JPEG yang dihasilkan. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Mendapat atau mengatur jumlah halaman yang akan dirender saat menyimpan ke file TIFF multi halaman. Defaultnya adalah MaxValue yang berarti semua halaman diagram akan dirender. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Mendapat atau menyetel indeks berbasis 0 dari halaman pertama yang akan dirender. Standarnya adalah 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Mendapat atau mengatur ukuran halaman untuk gambar yang dihasilkan. Bisa jadi[`PageSize`](../pagesize/) atau null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Mendapat atau menyetel nilai yang menentukan bagaimana piksel diimbangi selama rendering. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Mendapat atau menyetel resolusi untuk gambar yang dihasilkan, dalam titik per inci. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Menentukan apakah area penyimpanan sama dengan pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. Bisa jadi[`Bertengkar`](../../aspose.diagram/savefileformat/) ,[`png`](../../aspose.diagram/savefileformat/) , [`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) atau[`Jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Mendapat atau menyetel faktor zoom untuk gambar yang dihasilkan. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Mendapat atau mengatur bentuk untuk dirender. Hitungan default adalah 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Menentukan apakah penghalusan (antialiasing) diterapkan pada garis dan kurva serta tepi area yang terisi. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Mendapat atau menyetel jenis kompresi yang diterapkan saat menyimpan gambar yang dihasilkan ke format TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Mendapat atau menyetel callback peringatan. |

### Lihat juga

* class [RenderingSaveOptions](../renderingsaveoptions/)
* ruang nama [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
