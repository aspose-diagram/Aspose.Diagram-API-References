---
title: XPSSaveOptions
second_title: Aspose.Diagram untuk Referensi .NET API
description: Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke XPS.
type: docs
weight: 3520
url: /id/net/aspose.diagram.saving/xpssaveoptions/
---
## XPSSaveOptions class

Memungkinkan untuk menentukan opsi tambahan saat merender halaman diagram ke XPS.

```csharp
public class XPSSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XPSSaveOptions](xpssaveoptions/)() | Menginisialisasi instance baru dari kelas ini yang dapat digunakan untuk menyimpan dokumen di[`XPS`](../../aspose.diagram/savefileformat/) format. |

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Ketika karakter dalam diagram adalah unicode dan tidak diatur dengan nilai font yang benar atau font tidak diinstal secara lokal, mereka mungkin muncul sebagai blok di pdf, gambar atau XPS. Atur DefaultFont seperti MingLiu atau MS Gothic untuk menampilkannya karakter. |
| [ExportHiddenPage](../../aspose.diagram.saving/xpssaveoptions/exporthiddenpage/) { get; set; } | Mendefinisikan apakah perlu mengekspor halaman tersembunyi atau tidak. |
| [PageCount](../../aspose.diagram.saving/xpssaveoptions/pagecount/) { get; set; } | Mendapat atau menetapkan jumlah halaman yang akan dirender di XPS. Defaultnya adalah MaxValue yang berarti semua halaman diagram akan dirender. |
| [PageIndex](../../aspose.diagram.saving/xpssaveoptions/pageindex/) { get; set; } | Mendapat atau menyetel indeks berbasis 0 dari halaman pertama yang akan dirender. Standarnya adalah 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/xpssaveoptions/saveforegroundpagesonly/) { get; set; } | Menentukan apakah semua halaman akan disimpan dalam gambar atau hanya latar depan. |
| override [SaveFormat](../../aspose.diagram.saving/xpssaveoptions/saveformat/) { get; set; } | Menentukan format di mana halaman diagram yang dirender akan disimpan jika objek opsi penyimpanan ini digunakan. Bisa jadi[`XPS`](../../aspose.diagram/savefileformat/) hanya. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Mendapat atau menyetel callback peringatan. |

### Lihat juga

* class [SaveOptions](../saveoptions/)
* ruang nama [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
