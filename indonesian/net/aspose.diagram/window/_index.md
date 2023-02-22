---
title: Window
second_title: Aspose.Diagram untuk Referensi .NET API
description: Mewakili jendela yang terbuka dalam contoh Microsoft Visio. Elemen ini berisi informasi yang diperlukan untuk secara tepat membuat ulang jendela antarmuka pengguna di ruang kerja aplikasi saat file DatadiagramML awalnya dibuka oleh Visio.
type: docs
weight: 4390
url: /id/net/aspose.diagram/window/
---
## Window class

Mewakili jendela yang terbuka dalam contoh Microsoft Visio. Elemen ini berisi informasi yang diperlukan untuk secara tepat membuat ulang jendela antarmuka pengguna di ruang kerja aplikasi saat file DatadiagramML awalnya dibuka oleh Visio.

```csharp
public class Window
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Window](window/)() | Pembuat. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | ID penampung: Halaman, Lembar, atau Master. Hanya relevan dan diperlukan jika ContainerType ditentukan. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Mungkin salah satu dari nilai berikut: Dokumen, Halaman, atau Master. Hanya relevan ketika WindowType ditetapkan sebagai Drawing atau Sheet. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Jalur file dari dokumen yang ditampilkan di jendela ini. Atribut ini relevan untuk jendela yang WindowType-nya ditetapkan sebagai Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Menentukan apakah fitur kisi dinamis diaktifkan untuk dokumen atau jendela. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Menentukan objek yang membentuk lem ketika lem diaktifkan di dokumen. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | ID unik elemen di dalam elemen induknya. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | ID Master jika jendela ini menampilkan master. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | ID Halaman jika jendela ini menampilkan halaman. Relevan hanya jika WindowType ditentukan sebagai Drawing dan ContainerType ditentukan sebagai Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID jendela tempat jendela stensil ini berada. Relevan hanya jika WindowType ditetapkan sebagai Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Bendera hanya-baca jika stensil ini bukan stensil dokumen. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID lembar dalam wadah. Relevan hanya jika Container ditentukan sebagai Sheet. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Menentukan apakah titik koneksi ditampilkan di jendela. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Menentukan apakah kisi ditampilkan di jendela gambar. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Menentukan apakah panduan ditampilkan di jendela gambar. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Menentukan apakah jeda halaman ditampilkan di jendela. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Menentukan apakah penggaris ditampilkan di jendela gambar. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Berisi kumpulan elemen SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Menentukan apakah pengaturan ekstensi snap tertentu diaktifkan atau dinonaktifkan untuk jendela aktif. Nilai dapat berupa penjumlahan dari nilai pada tabel berikut. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Menentukan objek yang membentuk snap ketika snap aktif di jendela. Nilai tersebut mungkin merupakan jumlah dari nilai dalam tabel berikut. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Menentukan grup jendela stensil yang digabungkan di mana jendela tersebut menjadi anggotanya. Atribut ini hanya relevan untuk elemen Window yang atribut WindowType-nya adalah Stencil, dan hanya jika jendela stensil merupakan bagian dari grup gabungan jendela stensil. Semua jendela stensil yang merupakan bagian dari grup gabungan yang sama memiliki nilai elemen StensilGroup yang sama. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Berisi bilangan bulat yang menentukan posisi relatif stensil dalam grup di jendela. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Menentukan lebar kontrol tab halaman dari jendela gambar (sebagai bagian dari total lebar jendela gambar). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Ganda opsional. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Ganda opsional. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Ganda opsional. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Tinggi persegi panjang jendela. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Koordinat kiri kotak jendela. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Atribut ini dapat berupa penjumlahan dari nilai berikut. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Koordinat atas persegi panjang jendela. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Nilai enumerasi yang mungkin salah satu dari yang berikut: Gambar, Lembaran, Stensil, atau Ikon. Elemen Jendela dari WindowType='Stencil' harus muncul setelah jendela gambar induknya (WindowType='Drawing') dan sebelum jendela gambar lainnya elemen. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Lebar persegi panjang jendela. |

### Lihat juga

* ruang nama [Aspose.Diagram](../../aspose.diagram/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
