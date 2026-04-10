---
title: IPageSavingCallback
second_title: Aspose.Diagram لـ Java API Reference
description: التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.
type: docs
weight: 456
url: /ar/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicate a page ends to be output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicate a page starts to be output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicate a page ends to be output.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | معلومات الصفحة تنهي عملية الحفظ. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicate a page starts to be output.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | معلومات بدء عملية حفظ الصفحة. |

