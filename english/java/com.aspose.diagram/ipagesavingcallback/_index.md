---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API Reference
description: Control/Indicate progress of page saving process.
type: docs
weight: 458
url: /java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Control/Indicate progress of page saving process.
## Methods

| Method | Description |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicate a page ends to be output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicate a page starts to be output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicate a page ends to be output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Info for a page ends saving process. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicate a page starts to be output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Info for a page starts saving process. |

