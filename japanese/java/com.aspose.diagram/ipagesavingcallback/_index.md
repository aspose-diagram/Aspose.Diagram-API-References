---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API リファレンス
description: ページ保存プロセスの進行状況を制御/表示します。
type: docs
weight: 456
url: /ja/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

ページ保存プロセスの進行状況を制御/表示します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicate a page ends to be output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicate a page starts to be output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicate a page ends to be output.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | ページの情報が保存プロセスを終了します。 |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicate a page starts to be output.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | ページの保存プロセス開始に関する情報です。 |

