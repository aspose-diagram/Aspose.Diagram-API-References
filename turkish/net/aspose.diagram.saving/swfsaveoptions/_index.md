---
title: SWFSaveOptions
second_title: Aspose.Diagram for .NET API Referansı
description: Diyagram sayfalarını SWF. olarak işlerken ek seçenekler belirlemeye izin verir.
type: docs
weight: 3470
url: /tr/net/aspose.diagram.saving/swfsaveoptions/
---
## SWFSaveOptions class

Diyagram sayfalarını SWF. olarak işlerken ek seçenekler belirlemeye izin verir.

```csharp
public class SWFSaveOptions : SaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SWFSaveOptions](swfsaveoptions/)() | Bir belgeyi kaydetmek için kullanılabilecek bu sınıfın yeni bir örneğini başlatır.[`XPS`](../../aspose.diagram/savefileformat/) biçim. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Diyagramdaki karakterler unicode olduğunda ve doğru yazı tipi değeriyle ayarlanmadığında veya yazı tipi yerel olarak yüklenmediğinde, pdf, resim veya XPS'de blok olarak görünebilirler. Bunları göstermek için MingLiu veya MS Gothic gibi Varsayılan Yazı Tipini ayarlayın karakterler. |
| [PageCount](../../aspose.diagram.saving/swfsaveoptions/pagecount/) { get; set; } | XPS'de işlenecek sayfa sayısını alır veya ayarlar. Varsayılan, MaxValue'dur, bu, diyagramın tüm sayfalarının işleneceği anlamına gelir. |
| [PageIndex](../../aspose.diagram.saving/swfsaveoptions/pageindex/) { get; set; } | İşlenecek ilk sayfanın 0 tabanlı dizinini alır veya ayarlar. Varsayılan 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/swfsaveoptions/saveforegroundpagesonly/) { get; set; } | Tüm sayfaların görüntüde mi yoksa sadece ön planda mı kaydedileceğini belirtir. |
| override [SaveFormat](../../aspose.diagram.saving/swfsaveoptions/saveformat/) { get; set; } | Bu kaydetme seçenekleri nesnesi kullanılırsa, işlenen diyagram sayfalarının kaydedileceği biçimi belirtir. Olabilir[`XPS`](../../aspose.diagram/savefileformat/) sadece. |
| [ViewerIncluded](../../aspose.diagram.saving/swfsaveoptions/viewerincluded/) { get; set; } | Oluşturulan SWF belgesinin entegre belge görüntüleyiciyi içerip içermeyeceğini belirtir. Varsayılan değer:`doğru` . |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Uyarı geri aramasını alır veya ayarlar. |

### Ayrıca bakınız

* class [SaveOptions](../saveoptions/)
* ad alanı [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->