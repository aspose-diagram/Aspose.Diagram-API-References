---
title: DataRecordSet
second_title: Aspose.Diagram untuk Referensi .NET API
description: Menyimpan memformat menyegarkan dan memaparkan data yang diminta dari database di Microsoft Visio.
type: docs
weight: 1140
url: /id/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Menyimpan, memformat, menyegarkan, dan memaparkan data yang diminta dari database di Microsoft Visio.

```csharp
public class DataRecordSet
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Pembuat. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Berisi XML yang sesuai dengan skema XML klasik ADO untuk kumpulan rekaman ADO dan yang mendeskripsikan data dalam kumpulan rekaman data. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Menentukan aturan yang membandingkan kolom dalam elemen DataRecordset induk dengan item data bentuk dari tindakan penautan otomatis terakhir yang berhasil dilakukan di antarmuka pengguna. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Nilai checksum, dihasilkan oleh Visio, dan berdasarkan properti data-recordset. Tetapkan atribut ini ke 0; Visio menghitung ulang nilai ini saat runtime. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | String perintah yang digunakan untuk mengkueri data dari sumber data. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | ID koneksi untuk objek DataConnection terkait. Tidak ada untuk sumber data XML. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Berisi semua elemen DataColumn dalam recordset data. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | Data recordset ID, unik di dalam dokumen. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Tampilan (atau "ramah") nama recordset data. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | ID baris Visio berikutnya yang tersedia. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Opsi untuk diterapkan ke kumpulan data. Nilai yang mungkin dapat berupa kombinasi apa pun dari satu atau lebih nilai yang ditampilkan dalam tabel berikut. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Mengidentifikasi satu atau lebih kolom primary-key di recordset data. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Menunjukkan baris dalam kumpulan rekaman data yang ditautkan ke bentuk yang berkonflik setelah kumpulan rekaman data disegarkan. RowID - Menunjukkan baris di kumpulan rekaman data yang ditautkan ke bentuk yang bertentangan setelah kumpulan rekaman data disegarkan. ShapeID - ID Bentuk dari bentuk yang terlibat dalam konflik. PageID - ID Halaman dari bentuk yang terlibat dalam konflik. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Seberapa sering (dalam menit) Visio menyegarkan kumpulan data secara otomatis. Nilai ini harus 1 atau lebih besar. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Apakah antarmuka pengguna rekonsiliasi data harus dinonaktifkan. Benar (1) untuk menonaktifkan antarmuka pengguna (UI). Salah (0) untuk mengaktifkan UI. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Apakah akan menimpa perubahan pengguna untuk membentuk item data dalam bentuk yang ditautkan ke data saat kumpulan data disegarkan. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Menentukan bagaimana tautan bentuk-data diperlakukan saat bentuk disalin atau dipotong. 1 untuk mengganti tautan yang ada dalam bentuk target. 0 untuk mempertahankan tautan yang ada dalam bentuk target. Jika atribut ini tidak ada, Visio akan menanyakan kepada pengguna apakah akan mengganti tautan yang disalin atau dipotong. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Memetakan baris kumpulan data ke bentuk. RowID - ID Baris dari baris, unik di dalam kumpulan catatan data. ShapeID - ID Bentuk dari bentuk yang ditautkan ke data di baris kumpulan data yang diidentifikasi oleh RowID. PageID - ID halaman bentuk yang ditautkan ke data di baris data-recordset yang diidentifikasi oleh RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Apakah akan menggunakan urutan baris dalam kumpulan data sebagai kunci utama. Benar (1) jika ID baris ditentukan oleh urutan baris. Salah (0) jika ID baris ditentukan oleh nilai dalam kolom primary key dari kumpulan data. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | Tanggal dan waktu kumpulan data terakhir disegarkan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Menjalankan string kueri yang terkait dengan DataRecordset yang terhubung (berbasis XML) dan memperbarui bentuk yang ditautkan dengan data baru dari sumber data yang dikembalikan oleh kueri. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Menjalankan string kueri yang terkait dengan DataRecordset yang terhubung (berbasis XML) dan memperbarui bentuk yang ditautkan dengan data baru dari sumber data yang dikembalikan oleh kueri. |

### Lihat juga

* ruang nama [Aspose.Diagram](../../aspose.diagram/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
