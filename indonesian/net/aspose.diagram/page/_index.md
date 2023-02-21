---
title: Page
second_title: Aspose.Diagram untuk Referensi .NET API
description: Berisi elemen yang menentukan halaman dalam dokumen.
type: docs
weight: 2490
url: /id/net/aspose.diagram/page/
---
## Page class

Berisi elemen yang menentukan halaman dalam dokumen.

```csharp
public class Page : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Page](page/#constructor)() | Pembuat. |
| [Page](page/#constructor_1)(int) | Pembuat. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | ID halaman gambar asli yang ditandai pada overlay markup terpisah oleh peninjau gambar. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Bendera yang menunjukkan apakah halaman tersebut adalah halaman latar belakang. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | Halaman latar belakang halaman. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Berisi elemen Connect untuk setiap koneksi antara dua bentuk dalam sebuah gambar. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | ID unik elemen di dalam elemen induknya. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Nama elemen. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Nama universal elemen. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Koleksi halaman. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Berisi elemen yang menentukan lembar halaman untuk elemen Halaman atau Master. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Terapkan tema preset ke halaman ini |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Terapkan gaya cepat varian tema preset ke halaman ini |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Terapkan varian tema preset ke halaman ini |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | ID peninjau yang terkait dengan overlay markup. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Koleksi bentuk. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat dibuka pada awalnya. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX dan ViewCenterY menentukan titik pusat pada halaman yang diasumsikan oleh tampilan (jendela) baru saat dibuka pada awalnya. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Faktor pembesaran default untuk digunakan saat tampilan baru (jendela) halaman dibuka. Misalnya, 1 = 100%; 1,5 = 150%, dan seterusnya. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Membuat Kontrol Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Menambahkan komentar ke bentuk dengan id bentuk. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Menambahkan komentar ke bentuk. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Menambahkan komentar dengan PinX dan PinY yang ditentukan. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Menambahkan bentuk yang dibuat oleh master ke halaman tertentu. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Menambahkan bentuk yang dibuat oleh master pada halaman dengan PinX dan PinY yang ditentukan. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Menambahkan bentuk yang dibuat oleh master pada halaman dengan PinX, PinY, Lebar, dan Tinggi yang ditentukan. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Menambahkan Teks dengan PinX dan PinY yang ditentukan. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Menambahkan Teks dengan PinX dan PinY yang ditentukan. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Menerapkan gaya untuk halaman penuh. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Bentuk ruang otomatis |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Membawa bentuk, ditentukan oleh ID, maju satu posisi dalam z-order. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Membawa bentuk, ditentukan oleh ID, ke depan z-order. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Memusatkan bentuk halaman sehubungan dengan luas halaman. Memusatkan bentuk tidak mengubah posisinya relatif satu sama lain. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Hubungkan bentuk melalui konektor. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Hubungkan bentuk melalui konektor. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Hubungkan bentuk melalui konektor. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Hubungkan bentuk melalui indeks konektor. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Hubungkan bentuk melalui indeks konektor. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Proses menggambar bezier. Panjang titik harus sama atau lebih besar dari 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Proses menggambar Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Proses menggambar satu garis. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Proses menggambar garis. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Proses menggambar garis. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Proses Menggambar Polyline. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Proses menggambar polyline. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Proses menggambar persegi panjang. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Proses menggambar spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Bentuk lem |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Bentuk lem. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Bentuk lem dalam wadah |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Rekatkan bentuk dalam wadah menggunakan nama koneksi |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Rekatkan bentuk dengan id koneksi di container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Rekatkan bentuk ke BeginX Connector |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Rekatkan bentuk ke Ujung KonektorX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Menampilkan bentuk dan/atau mengubah rute konektor untuk halaman. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Memindahkan halaman ke lokasi lain di halaman. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Memindahkan bentuk, ditentukan oleh ID, mundur satu posisi dalam urutan-z. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Memindahkan bentuk, ditentukan oleh ID, ke belakang z-order. |

### Lihat juga

* ruang nama [Aspose.Diagram](../../aspose.diagram/)
* perakitan [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
