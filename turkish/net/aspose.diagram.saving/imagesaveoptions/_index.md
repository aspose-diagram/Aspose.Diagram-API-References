---
title: ImageSaveOptions
second_title: Aspose.Diagram for .NET API Referansı
description: Diyagram sayfalarını görüntülere dönüştürürken ek seçenekler belirlemeye izin verir.
type: docs
weight: 3280
url: /tr/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Diyagram sayfalarını görüntülere dönüştürürken ek seçenekler belirlemeye izin verir.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | İşlenmiş görüntüleri kaydetmek için kullanılabilecek bu sınıfın yeni bir örneğini başlatır.[`tiff`](../../aspose.diagram/savefileformat/) , [`png`](../../aspose.diagram/savefileformat/) ,[`bmp`](../../aspose.diagram/savefileformat/) ,[`EMF`](../../aspose.diagram/savefileformat/) veya[`jpeg`](../../aspose.diagram/savefileformat/) biçim. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Kaydedilecek şekillerin alanını alır veya ayarlar . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Birleştirme sırasında kullanılacak kalite seviyesini belirtir. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Bu parametre ölçeğe benzer, ancak oluşturulan görüntü boyutunu etkilemez. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Diyagramdaki karakterler unicode olduğunda ve doğru yazı tipi değeriyle ayarlanmadığında veya yazı tipi yerel olarak yüklenmediğinde, pdf, resim veya XPS'de blok olarak görünebilirler. Bunları göstermek için MingLiu veya MS Gothic gibi Varsayılan Yazı Tipini ayarlayın karakterler. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Emf meta dosyası oluşturma ayarı. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Sayfanın büyütülüp büyütülmediğini belirtir . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Kılavuz şekillerin dışa aktarılmasının gerekip gerekmediğini tanımlar. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Gizli sayfayı dışa aktarmanın gerekip gerekmediğini tanımlar. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Oluşturulan görüntüler için parlaklığı alır veya ayarlar. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Oluşturulan görüntüler için renk modunu alır veya ayarlar. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Oluşturulan görüntüler için kontrastı alır veya ayarlar. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Görüntüler ölçeklendiğinde veya döndürüldüğünde kullanılan algoritmayı belirtir. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Yorumların dışa aktarılması gerekip gerekmediğini tanımlar. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Oluşturulan JPEG görüntülerinin kalitesini belirleyen bir değer alır veya ayarlar. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Çok sayfalı bir TIFF dosyasına kaydederken işlenecek sayfa sayısını alır veya ayarlar. Varsayılan, MaxValue'dur, bu, diyagramın tüm sayfalarının işleneceği anlamına gelir. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | İşlenecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar. Varsayılan 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Oluşturulan görüntüler için sayfa boyutunu alır veya ayarlar. Olabilir[`PageSize`](../pagesize/) veya null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Oluşturma sırasında piksellerin nasıl kaydırılacağını belirten bir değer alır veya ayarlar. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Oluşturulan görüntülerin çözünürlüğünü inç başına nokta cinsinden alır veya ayarlar. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Kayıt alanının pdf . ile aynı olup olmadığını belirtir. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Tüm sayfaların görüntüde mi yoksa sadece ön planda mı kaydedileceğini belirtir. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Bu kaydetme seçenekleri nesnesi kullanılırsa, işlenen diyagram sayfalarının kaydedileceği biçimi belirtir. Olabilir[`tiff`](../../aspose.diagram/savefileformat/) ,[`png`](../../aspose.diagram/savefileformat/) , [`bmp`](../../aspose.diagram/savefileformat/) ,[`EMF`](../../aspose.diagram/savefileformat/) veya[`jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Oluşturulan görüntüler için yakınlaştırma faktörünü alır veya ayarlar. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | İşlenecek şekilleri alır veya ayarlar. Varsayılan sayı 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Çizgilere, eğrilere ve doldurulmuş alanların kenarlarına yumuşatma (kenar yumuşatma) uygulanıp uygulanmayacağını belirtir. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Oluşturulan görüntüleri TIFF biçiminde kaydederken uygulanacak sıkıştırma türünü alır veya ayarlar. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Uyarı geri aramasını alır veya ayarlar. |

### Ayrıca bakınız

* class [RenderingSaveOptions](../renderingsaveoptions/)
* ad alanı [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
