---
title: IPageSavingCallback
second_title: Aspose.Diagram voor Java API-referentie
description: Beheer/Geef de voortgang van het opslaan van pagina's aan.
type: docs
weight: 456
url: /nl/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Beheer/Geef de voortgang van het opslaan van pagina's aan.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Geef aan dat een pagina eindigt om te worden uitgevoerd. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Geef aan dat een pagina begint te worden uitgevoerd. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Geef aan dat een pagina eindigt om te worden uitgevoerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Info voor een pagina beëindigt het opslaan. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Geef aan dat een pagina begint te worden uitgevoerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Info voor een pagina start opslaan proces. |

