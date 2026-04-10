---
title: IPageSavingCallback
second_title: Aspose.Diagram för Java API-referens
description: Styr/indikera framsteg för sidlagringsprocessen.
type: docs
weight: 456
url: /sv/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Styr/indikera framsteg för sidlagringsprocessen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Kontroll/Indikera att en sida avslutas för utskrift. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Kontroll/Indikera att en sida påbörjas för utskrift. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Kontroll/Indikera att en sida avslutas för utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Information för en sida avslutar sparningsprocessen. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Kontroll/Indikera att en sida påbörjas för utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Information för en sida påbörjar sparningsprocessen. |

