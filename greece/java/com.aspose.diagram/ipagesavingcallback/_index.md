---
title: IPageSavingCallback
second_title: Αναφορά API του Aspose.Diagram για Java
description: Έλεγχος/Ένδειξη προόδου της διαδικασίας αποθήκευσης σελίδας.
type: docs
weight: 456
url: /el/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Έλεγχος/Ένδειξη προόδου της διαδικασίας αποθήκευσης σελίδας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Δείξτε ότι η σελίδα τελειώνει για έξοδο. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Δείξτε ότι η σελίδα αρχίζει για έξοδο. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Δείξτε ότι η σελίδα τελειώνει για έξοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Πληροφορίες για μια σελίδα ολοκληρώνουν τη διαδικασία αποθήκευσης. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Δείξτε ότι η σελίδα αρχίζει για έξοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Πληροφορίες για τη σελίδα ξεκινούν τη διαδικασία αποθήκευσης. |

