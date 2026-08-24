---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API-Referenz
description: Steuert/zeigt den Fortschritt des Seiten‑Speichervorgangs an.
type: docs
weight: 456
url: /de/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Steuert/zeigt den Fortschritt des Seiten‑Speichervorgangs an.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicate a page ends to be output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicate a page starts to be output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicate a page ends to be output.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Informationen für eine Seite beenden den Speicherungsprozess. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicate a page starts to be output.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Informationen für eine Seite starten den Speicherungsprozess. |

