---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API 参考
description: 控制/指示页面保存过程的进度。
type: docs
weight: 456
url: /zh/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

控制/指示页面保存过程的进度。
## 方法

| 方法 | 描述 |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/指示页面结束输出。 |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/指示页面开始输出。 |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/指示页面结束输出。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | 页面结束保存过程的信息。 |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/指示页面开始输出。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | 页面开始保存过程的信息。 |

