---
title: Page
second_title: Aspose.Diagram for .NET API Referansı
description: Belgedeki bir sayfayı tanımlayan öğeleri içerir.
type: docs
weight: 2490
url: /tr/net/aspose.diagram/page/
---
## Page class

Belgedeki bir sayfayı tanımlayan öğeleri içerir.

```csharp
public class Page : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Page](page/#constructor)() | Yapıcı. |
| [Page](page/#constructor_1)(int) | Yapıcı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | Çizimi inceleyenler tarafından ayrı işaretleme yer paylaşımlarında işaretlenen orijinal çizim sayfasının kimliği. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Sayfanın arka plan sayfası olup olmadığını gösteren bir bayrak. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | Sayfanın arka plan sayfası. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Bir çizimdeki iki şekil arasındaki her bağlantı için bir Bağlantı öğesi içerir. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | Üst öğe içindeki öğenin benzersiz kimliği. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Öğenin adı. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Öğenin evrensel adı. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Sayfa koleksiyonu. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Sayfa veya Ana öğe için sayfa sayfasını tanımlayan öğeleri içerir. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Bu sayfaya hazır bir tema uygulayın |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Bu sayfaya önceden ayarlanmış bir tema varyantı hızlı stili uygulayın |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Bu sayfaya önceden ayarlanmış bir tema varyantı uygulayın |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | İşaretleme katmanıyla ilişkili gözden geçirenin kimliği. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Şekil koleksiyonu. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX ve ViewCenterY, başlangıçta açıldığında yeni bir görünümün (pencerenin) varsaydığı sayfada bir merkez noktası belirtir. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX ve ViewCenterY, başlangıçta açıldığında yeni bir görünümün (pencerenin) varsaydığı sayfada bir merkez noktası belirtir. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Sayfanın yeni bir görünümü (penceresi) açıldığında kullanılacak varsayılan büyütme faktörü. Örneğin, 1 = %100; 1,5 = %150 vb. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Bir Activex Kontrolü oluşturur. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Şeklin kimliğine sahip bir şekle yorum ekler. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Bir şekle yorum ekler. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Tanımlı PinX ve PinY ile yorum ekler. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Kalıp tarafından oluşturulan şekli belirli sayfaya ekler. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Tanımlı PinX ve PinY. ile sayfada master tarafından oluşturulan şekli ekler. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Tanımlı PinX,PinY,Genişlik ve Yükseklik ile sayfada master tarafından oluşturulan şekli ekler. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Tanımlı PinX ve PinY ile Metin Ekler. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Tanımlı PinX ve PinY ile Metin Ekler. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Stili tam sayfaya uygular. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Otomatik alan şekilleri |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Kimlik tarafından tanımlanan bir şekli z-sırasında bir konum ileri getirir. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Kimlik tarafından tanımlanan bir şekli z sırasının önüne getirir. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Bir sayfanın şekillerini sayfanın boyutuna göre ortalar. Şekillerin merkezlenmesi birbirlerine göre konumlarını değiştirmez. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Şekilleri bağlayıcı aracılığıyla bağlayın. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Şekilleri bağlayıcı aracılığıyla bağlayın. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Şekilleri bağlayıcı aracılığıyla bağlayın. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Şekilleri bağlayıcı dizini aracılığıyla bağlayın. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Şekilleri bağlayıcı dizini aracılığıyla bağlayın. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Bezier çizme işlemi. Noktaların uzunluğu 3. 'ye eşit veya daha büyük olmalıdır. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Elips çizme süreci. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Tek bir çizgi çizme işlemi. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Çizgi çizme işlemi. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Çizgi çizme işlemi. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Polyline. çizim süreci |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Sürekli çizgi çizme süreci. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Dikdörtgen çizme işlemi. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Spline çizme işlemi. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Şekilleri yapıştırın |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Şekilleri yapıştırın. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Container içindeki şekilleri yapıştırın |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Bağlantı adını kullanarak kaptaki şekilleri yapıştırın |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Container içindeki bağlantı kimliğine göre şekilleri yapıştırın |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Şekli Bağlayıcının Başlangıcına yapıştırınX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Şekli Konektörün EndX'ine yapıştırın |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Şekilleri düzenler ve/veya sayfa için bağlayıcıları yeniden yönlendirir. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Sayfayı sayfalarda başka bir konuma taşır. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Kimlik tarafından tanımlanan bir şekli z-sırasında bir konum geriye taşır. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Kimlik tarafından tanımlanan bir şekli z sırasının arkasına taşır. |

### Ayrıca bakınız

* ad alanı [Aspose.Diagram](../../aspose.diagram/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
