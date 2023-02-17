---
title: DataRecordSet
second_title: Aspose.Diagram for .NET API Referansı
description: Microsoft Visioda bir veritabanından sorgulanan verileri depolar biçimlendirir yeniler ve kullanıma sunar.
type: docs
weight: 1140
url: /tr/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Microsoft Visio'da bir veritabanından sorgulanan verileri depolar, biçimlendirir, yeniler ve kullanıma sunar.

```csharp
public class DataRecordSet
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Yapıcı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Bir ADO kayıt kümesi için ADO klasik XML şemasına uyan ve veri kayıt kümesindeki verileri açıklayan XML içerir. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Üst DataRecordset öğesindeki bir sütunu, kullanıcı arabiriminde gerçekleştirilen son başarılı otomatik bağlama eylemindeki şekil veri öğesiyle karşılaştıran bir kural tanımlar. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Visio tarafından oluşturulan ve veri kayıt kümesi özelliklerine dayalı bir sağlama toplamı değeri. Bu özniteliği 0 olarak ayarlayın; Visio bu değeri çalışma zamanında yeniden hesaplar. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | Veri kaynağından veri sorgulamak için kullanılan komut dizisi. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | İlişkili DataConnection nesnesi için bağlantı kimliği. XML veri kaynakları için mevcut değil. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Bir veri kayıt kümesindeki tüm DataColumn öğelerini içerir. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | Belge içinde benzersiz olan veri kayıt kümesi kimliği. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Veri kayıt kümesinin görünen (veya "dost") adı. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | Bir sonraki kullanılabilir Visio satır kimliği. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Veri kayıt kümesine uygulanacak seçenekler. Olası değerler, aşağıdaki tabloda gösterilenlerden bir veya daha fazlasının herhangi bir kombinasyonu olabilir. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Veri kayıt kümesindeki bir veya daha fazla birincil anahtar sütunu tanımlar. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Veri kayıt kümesinde, veri kayıt kümesi yenilendikten sonra çakışan bir şekle bağlı bir satırı gösterir. RowID - Veri kayıt kümesi yenilendikten sonra çakışan bir şekle bağlı veri kayıt kümesindeki bir satırı gösterir. ShapeID - Çakışmaya dahil olan şeklin Şekil Kimliği. Sayfa Kimliği - Çakışmaya dahil olan şeklin Sayfa Kimliği. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Visio'nun veri kayıt kümesini ne sıklıkta (dakika olarak) otomatik olarak yenilediği. Bu değer 1 veya daha büyük olmalıdır. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Veri mutabakatı kullanıcı arabiriminin devre dışı bırakılıp bırakılmayacağı. Kullanıcı arabirimini (UI) devre dışı bırakmak için True (1). UI. 'yi etkinleştirmek için yanlış (0) |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Veri kayıt kümesi yenilendiğinde, verilere bağlı şekillerdeki veri öğelerini şekillendirmek için kullanıcı değişikliklerinin üzerine yazıp yazmayacağı. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Şekiller kopyalandığında veya kesildiğinde şekil verisi bağlantılarının nasıl ele alınacağını tanımlar. 1 hedef şeklinde mevcut bağlantıları değiştirmek için. 0 hedef şeklinde mevcut bağlantıları korumak için. Bu öznitelik yoksa, Visio kullanıcıya bağlantıların kopyada mı yoksa kesmede mi değiştirileceğini sorar. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Bir veri kayıt kümesi satırını bir şekle eşler. RowID - Veri kayıt kümesi içinde benzersiz olan satırın satır kimliği. ShapeID - RowID tarafından tanımlanan veri kayıt kümesi satırındaki verilere bağlı şeklin Şekil Kimliği. Sayfa Kimliği - RowID. tarafından tanımlanan veri kayıt kümesi satırındaki verilere bağlı şeklin sayfa kimliği |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Veri kayıt kümesindeki satırların sırasının birincil anahtar olarak kullanılıp kullanılmayacağı. Doğru (1), satır kimlikleri satır sırasına göre belirleniyorsa. Satır kimlikleri, veri kayıt kümesinin birincil anahtar sütunlarındaki değerler tarafından belirleniyorsa yanlış (0). |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | Veri kayıt kümesinin en son yenilendiği tarih ve saat. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Bağlı (XML tabanlı olmayan) DataRecordset ile ilişkili sorgu dizesini yürütür ve bağlantılı şekilleri, sorgu tarafından döndürülen veri kaynağından yeni verilerle günceller. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Bağlı (XML tabanlı olmayan) DataRecordset ile ilişkili sorgu dizesini yürütür ve bağlantılı şekilleri, sorgu tarafından döndürülen veri kaynağından yeni verilerle günceller. |

### Ayrıca bakınız

* ad alanı [Aspose.Diagram](../../aspose.diagram/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
