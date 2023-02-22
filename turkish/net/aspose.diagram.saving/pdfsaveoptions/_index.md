---
title: PdfSaveOptions
second_title: Aspose.Diagram for .NET API Referansı
description: Diyagram sayfalarını PDFye işlerken ek seçenekler belirlemeye izin verir.
type: docs
weight: 3410
url: /tr/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Diyagram sayfalarını PDF'ye işlerken ek seçenekler belirlemeye izin verir.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Bir belgeyi kaydetmek için kullanılabilecek bu sınıfın yeni bir örneğini başlatır.[`Pdf`](../../aspose.diagram/savefileformat/) biçim. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Kaydedilecek şekillerin alanını alır veya ayarlar . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk düzeyi. Varsayılan değer:Pdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Diyagramdaki karakterler unicode olduğunda ve doğru yazı tipi değeriyle ayarlanmadığında veya yazı tipi yerel olarak yüklenmediğinde, pdf, resim veya XPS'de blok olarak görünebilirler. Bunları göstermek için MingLiu veya MS Gothic gibi Varsayılan Yazı Tipini ayarlayın karakterler. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Dijital imza ayrıntılarını alır veya ayarlar. Ayarlanmazsa, imzalama gerçekleştirilmez. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Emf meta dosyası oluşturma ayarı. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Bir şifreleme ayrıntısı alır veya ayarlar. Ayarlanmazsa şifreleme gerçekleştirilmez. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Sayfanın büyütülüp büyütülmediğini belirtir . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Kılavuz şekillerin dışa aktarılmasının gerekip gerekmediğini tanımlar. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Gizli sayfayı dışa aktarmanın gerekip gerekmediğini tanımlar. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | İnç başına nokta cinsinden oluşturulan görüntüler için yatay çözünürlüğü alır veya ayarlar. Emf biçimli görüntüler dışında görüntü oluşturma yöntemini uygular. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Yorumların dışa aktarılması gerekip gerekmediğini tanımlar. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Görüntüler için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa). Varsayılan değer 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | PDF'de işlenecek sayfa sayısını alır veya ayarlar. Varsayılan, MaxValue'dur, bu, diyagramın tüm sayfalarının işleneceği anlamına gelir. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | İşlenecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar. Varsayılan 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Sayfa kaydetme işleminin ilerlemesini kontrol edin/gösterin. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Oluşturulan görüntüler için sayfa boyutunu alır veya ayarlar. Olabilir[`PageSize`](../pagesize/) veya null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Tüm sayfaların görüntüde mi yoksa sadece ön planda mı kaydedileceğini belirtir. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Bu kaydetme seçenekleri nesnesi kullanılırsa, işlenen diyagram sayfalarının kaydedileceği biçimi belirtir. Olabilir[`PDF`](../../aspose.diagram/savefileformat/) sadece. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | İşlenecek şekilleri alır veya ayarlar. Varsayılan sayı 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Sayfanın ayarına göre diyagramın çoklu sayfalara ayrılıp ayrılmayacağını tanımlar. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Resimler dışındaki tüm içerik akışları için kullanılacak sıkıştırma türünü belirtir. Varsayılan değer:Flate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | İnç başına nokta cinsinden oluşturulan görüntüler için dikey çözünürlüğü alır veya ayarlar. Emf biçimli görüntü dışında görüntü oluşturma yöntemini uygular. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Uyarı geri aramasını alır veya ayarlar. |

### Ayrıca bakınız

* class [RenderingSaveOptions](../renderingsaveoptions/)
* ad alanı [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
