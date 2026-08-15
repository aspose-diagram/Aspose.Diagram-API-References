---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API Reference
description: पृष्ठ सहेजने की प्रक्रिया की प्रगति को नियंत्रित/संकेत करता है।
type: docs
weight: 456
url: /hi/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

पृष्ठ सहेजने की प्रक्रिया की प्रगति को नियंत्रित/संकेत करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicate a page ends to be output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicate a page starts to be output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicate a page ends to be output.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | पृष्ठ के लिए जानकारी सहेजने की प्रक्रिया समाप्त करती है। |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicate a page starts to be output.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | पृष्ठ के लिए जानकारी सहेजने की प्रक्रिया शुरू करती है। |

