---
title: SWFSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Позволяет указать дополнительные параметры при отображении страниц диаграммы в SWF.
type: docs
weight: 3460
url: /ru/net/aspose.diagram.saving/swfsaveoptions/
---
## SWFSaveOptions class

Позволяет указать дополнительные параметры при отображении страниц диаграммы в SWF.

```csharp
public class SWFSaveOptions : SaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SWFSaveOptions](swfsaveoptions)() | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения документа в формате[`XPS`](../../aspose.diagram/savefileformat)Формат . |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Когда символы на диаграмме имеют формат Unicode и для них не установлено правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блочные в формате pdf, изображения или XPS. Установите DefaultFont, например MingLiu или MS Gothic, для отображения этих символов. |
| [PageCount](../../aspose.diagram.saving/swfsaveoptions/pagecount) { get; set; } | Получает или задает количество страниц для отображения в XPS. По умолчанию установлено значение MaxValue, что означает, что будут отображены все страницы диаграммы. |
| [PageIndex](../../aspose.diagram.saving/swfsaveoptions/pageindex) { get; set; } | Получает или задает отсчитываемый от 0 индекс первой отображаемой страницы. По умолчанию 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/swfsaveoptions/saveforegroundpagesonly) { get; set; } | Указывает, будут ли все страницы сохранены в изображении или только передний план. |
| override [SaveFormat](../../aspose.diagram.saving/swfsaveoptions/saveformat) { get; set; } | Задает формат, в котором будут сохранены визуализированные страницы схемы, если используется этот объект параметров сохранения. Может быть[`XPS`](../../aspose.diagram/savefileformat)Только . |
| [ViewerIncluded](../../aspose.diagram.saving/swfsaveoptions/viewerincluded) { get; set; } | Указывает, должен ли сгенерированный SWF-документ включать интегрированное средство просмотра документов или нет. Значение по умолчанию:` true` . |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Получает или устанавливает обратный вызов предупреждения. |

### Смотрите также

* class [SaveOptions](../saveoptions)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->