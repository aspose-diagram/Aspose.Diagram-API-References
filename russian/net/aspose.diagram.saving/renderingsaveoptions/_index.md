---
title: RenderingSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Это абстрактный базовый класс для классов которые позволяют пользователю указывать дополнительные параметры при сохранении диаграммы в определенном формате.
type: docs
weight: 3450
url: /ru/net/aspose.diagram.saving/renderingsaveoptions/
---
## RenderingSaveOptions class

Это абстрактный базовый класс для классов, которые позволяют пользователю указывать дополнительные параметры при сохранении диаграммы в определенном формате.

```csharp
public abstract class RenderingSaveOptions : SaveOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Получает или задает площадь сохраняемых фигур . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Если символы на диаграмме имеют формат Unicode и для них не задано правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блоки в pdf, изображениях или XPS. Установите шрифт по умолчанию, например MingLiu или MS Gothic, чтобы отобразить эти символов. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Настройка для рендеринга метафайла EMF. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Указывает, следует ли увеличивать страницу . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Определяет, нужно ли экспортировать направляющие формы или нет. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Определяет, нужно ли экспортировать комментарии или нет. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Получает или задает размер страницы для сгенерированных изображений. Может быть[`PageSize`](../pagesize/) или ноль. |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat/) { get; set; } | Указывает формат, в котором документ будет сохранен, если используется этот объект параметров сохранения. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Получает или задает фигуры для визуализации. Счетчик по умолчанию: 0. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Получает или задает обратный вызов предупреждения. |

### Смотрите также

* class [SaveOptions](../saveoptions/)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
