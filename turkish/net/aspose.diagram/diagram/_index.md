---
title: Diagram
second_title: Aspose.Diagram for .NET API Referansı
description: Visio nesneleri hiyerarşisinin kök öğesi.
type: docs
weight: 1170
url: /tr/net/aspose.diagram/diagram/
---
## Diagram class

Visio nesneleri hiyerarşisinin kök öğesi.

```csharp
public class Diagram : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Diagram](diagram/#constructor)() | Default_Constructor |
| [Diagram](diagram/#constructor_1)(Stream) | Genel sınıf yapıcısı, diyagramı akıştan yükler. |
| [Diagram](diagram/#constructor_4)(string) | Genel sınıf yapıcısı, diyagramı dosyadan yükler. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Genel sınıf yapıcısı, önceden tanımlanmış biçimi kullanarak diyagramı akıştan yükler. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Genel sınıf oluşturucu, önceden tanımlanmış yükleme dosyası seçeneklerini kullanarak diyagramı akıştan yükler. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Genel sınıf oluşturucu, önceden tanımlanmış biçimi kullanarak diyagramı dosyadan yükler. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Genel sınıf oluşturucu, önceden tanımlanmış yükleme dosyası seçeneklerini kullanarak diyagramı dosyadan yükler. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Etkin sayfayı belirtir |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Belgeyi oluşturmak için kullanılan Visio örneğinin yapı numarası. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Belgenin renk tablosunu içerir. Her belge, belgedeki şekiller, metin ve katmanlar gibi nesnelerine uygulanabilen 24 standart rengi listeleyen tek bir renk tablosu içerir. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Belge için DataConnection öğelerini içerir. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Bir Belge nesnesiyle ilişkili DataRecordset nesnelerinin koleksiyonu. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | Kullanıcının Microsoft Office 2010 Dil Tercihlerinde belirttiği kullanıcı arabirimi dilinin benzersiz kimliği. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Belgenin başlığı, yazarı vb. gibi belge özellik öğelerini içerir. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Belge ayarlarını belirten öğeleri içerir. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Bir belgenin ShapeSheet yapısını belirtir. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Belge için bir MIME (Çok Amaçlı İnternet Posta Uzantıları) kodlu MAPI e-posta yönlendirme fişi içerir. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Bir nesnenin yanıt vermesi gereken her olay için bir EventItem öğesi içerir. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Yazı Tipleri klasör yolunu gösterir |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Yazı Tipi öğelerinin bir koleksiyonunu içerir |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Bir belgenin üstbilgisi ve altbilgisi için öğeler içerir. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Kesme monitörünü alır ve ayarlar. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Belgenin Visio dışında değiştirilip değiştirilmediğini gösterir. Varsa, Visio dosyanın içeriğini tam olarak test eder. Visio. dışında oluşturduğunuz dosyaları atlayın |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Koleksiyon Ana nesneleri. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Çizimde metrik birimlerin kullanılıp kullanılmayacağı. Metrik birimleri kullanmak için bu özelliği True (1) olarak ayarlayın; İngiliz birimlerini kullanmak için Yanlış (0) olarak ayarlayın. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Koleksiyon Sayfası nesneleri. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | Şerit kullanıcı arabirimini özelleştirmek için belgeye iletilen Şerit XML dizesi. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML değeri. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Belgenin Visio dışında değiştirilip değiştirilmediğini gösterir. Varsa, Visio dosyanın içeriğini tam olarak test eder. Visio. dışında oluşturduğunuz dosyaları atlayın |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Koleksiyon StyleSheet nesneleri. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | Hızlı Erişim araç çubuğunu veya şeridi özelleştirmek için belgeye iletilen Şerit XML dizesi. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Belge için şema doğrulaması hakkında bilgi saklar. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | VbaProject'i alır[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Microsoft Visual Basic for Applications proje verilerini MIME (Çok Amaçlı İnternet Posta Uzantıları) kodlu biçimde içerir. |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio örneğinin sürüm numarası. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Bir belge için Pencere öğelerini içerir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Master'ın Adına veya NameU. 'ye göre kaynak diyagramdan diyagrama master ekler |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Ana kimliğine göre şablon akışından diyagrama ana öğe ekler. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Master'ın Adına veya NameU. 'ye göre şablon akışından diyagrama master ekler |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Ana kimliğine göre şablon dosyasından diyagrama ana bilgisayar ekler. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Master'ın Adı veya NameU. ile şablon dosyasından diyagrama master ekler |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Kalıp tarafından oluşturulan şekli belirli sayfaya ekler. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Tanımlı PinX ve PinY. ile sayfada master tarafından oluşturulan şekli ekler. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Tanımlı PinX,PinY,Genişlik ve Yükseklik ile sayfada master tarafından oluşturulan şekli ekler. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Başka bir Diyagram nesnesini birleştirir. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Temayı bir kaynak Diyagramdan kopyalar. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Varsayılan Yazı Tipleri klasör yolunu alın |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Kullanılmayan Stilleri Alın |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Bu diyagramda gizli bilgi olup olmadığını gösterir. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Diyagramın tüm sayfaları için şekilleri düzenler ve/veya bağlayıcıları yeniden yönlendirir. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Belgenin tamamını varsayılan yazıcıya yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Belgenin tamamını varsayılan yazıcıya yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak tüm belgeyi belirtilen yazıcıda yazdırın. |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak tüm belgeyi belirtilen yazıcıda yazdırın. |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Standart (Kullanıcı Arayüzü olmayan) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Standart (Kullanıcı Arayüzü olmayan) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi yazdırır. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Diagram. içindeki tüm DataRecordSet için Yenileme yöntemini çağırır |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Kullanılmayan bilgileri kaldırın |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | VBA/makroyu bu şemadan kaldırır. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Diyagram verilerini akışa kaydeder. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Belirtilen kaydetme seçeneklerini kullanarak diyagramı bir akışa kaydeder. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Diyagram verilerini dosyaya kaydeder. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Belirtilen kaydetme seçeneklerini kullanarak belgeyi bir dosyaya kaydeder. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Diyagramı vsd akışından vdw akışı formatına aktarır. Henüz uygulanmadı. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Diyagramı vsd akışından *.vdw dosya biçimine aktarır. Henüz uygulanmadı. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Diyagramı vsd dosyasından vdw akış biçimine aktarır. Henüz uygulanmadı. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Diyagramı vsd'den vdw formatına aktarır. Henüz uygulanmadı. |

### Ayrıca bakınız

* ad alanı [Aspose.Diagram](../../aspose.diagram/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
