---
title: IPageSavingCallback
second_title: Referensi API Aspose.Diagram untuk Java
description: Mengontrol/menunjukkan kemajuan proses penyimpanan halaman.
type: docs
weight: 456
url: /id/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Mengontrol/menunjukkan kemajuan proses penyimpanan halaman.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Kontrol/Indikasikan halaman berakhir untuk output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Kontrol/Indikasikan halaman dimulai untuk output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Kontrol/Indikasikan halaman berakhir untuk output.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Info untuk halaman mengakhiri proses penyimpanan. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Kontrol/Indikasikan halaman dimulai untuk output.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Info untuk halaman memulai proses penyimpanan. |

