---
title: IPageSavingCallback
second_title: Справочник API Aspose.Diagram for Java
description: Управление/индикация прогресса процесса сохранения страницы.
type: docs
weight: 456
url: /ru/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Управление/индикация прогресса процесса сохранения страницы.
## Методы

| Метод | Описание |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Указывает, что страница заканчивается для вывода. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Указывает, что страница начинается для вывода. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Указывает, что страница заканчивается для вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Информация о странице завершает процесс сохранения. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Указывает, что страница начинается для вывода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Информация о странице начинает процесс сохранения. |

