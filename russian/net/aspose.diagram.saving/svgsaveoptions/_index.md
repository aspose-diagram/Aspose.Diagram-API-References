---
title: SVGSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Позволяет указать дополнительные параметры при отображении страниц диаграммы в SVG.
type: docs
weight: 3460
url: /ru/net/aspose.diagram.saving/svgsaveoptions/
---
## SVGSaveOptions class

Позволяет указать дополнительные параметры при отображении страниц диаграммы в SVG.

```csharp
public class SVGSaveOptions : RenderingSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGSaveOptions](svgsaveoptions/)() | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения документа в[`XPS`](../../aspose.diagram/savefileformat/) формат. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Получает или задает площадь сохраняемых фигур . |
| [CustomImagePath](../../aspose.diagram.saving/svgsaveoptions/customimagepath/) { get; set; } | Пользовательский пользовательский путь (URL), сохраненный в сгенерированном файле svg для изображения. Если это не определено пользователем, будет использоваться текущий каталог. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Если символы на диаграмме имеют формат Unicode и для них не задано правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блоки в pdf, изображениях или XPS. Установите шрифт по умолчанию, например MingLiu или MS Gothic, чтобы отобразить эти символов. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Настройка для рендеринга метафайла EMF. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Указывает, следует ли увеличивать страницу . |
| [ExportElementAsRectTag](../../aspose.diagram.saving/svgsaveoptions/exportelementasrecttag/) { get; set; } | Определяет, нужно ли экспортировать прямоугольные элементы в виде тега rect или нет. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Определяет, нужно ли экспортировать направляющие формы или нет. |
| [ExportHiddenPage](../../aspose.diagram.saving/svgsaveoptions/exporthiddenpage/) { get; set; } | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Определяет, нужно ли экспортировать комментарии или нет. |
| [IsExportScaleInMatrix](../../aspose.diagram.saving/svgsaveoptions/isexportscaleinmatrix/) { get; set; } | Определяет, нужно ли экспортировать масштаб в матрицу или нет. |
| [IsSavingCustomLinePattern](../../aspose.diagram.saving/svgsaveoptions/issavingcustomlinepattern/) { get; set; } | Определяет, будет ли сохраняться пользовательский шаблон линии. |
| [IsSavingImageSeparately](../../aspose.diagram.saving/svgsaveoptions/issavingimageseparately/) { get; set; } | Определяет сохранение изображения отдельно. |
| [PageIndex](../../aspose.diagram.saving/svgsaveoptions/pageindex/) { get; set; } | Получает или задает отсчитываемый от 0 индекс отображаемой страницы. По умолчанию 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Получает или задает размер страницы для сгенерированных изображений. Может быть[`PageSize`](../pagesize/) или ноль. |
| [Quality](../../aspose.diagram.saving/svgsaveoptions/quality/) { get; set; } | Получает или задает значение, определяющее качество сгенерированных изображений для применения только при сохранении страниц в`JPEG` формат. Значение по умолчанию: 100 . |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat/) { get; set; } | Указывает формат, в котором документ будет сохранен, если используется этот объект параметров сохранения. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Получает или задает фигуры для визуализации. Счетчик по умолчанию: 0. |
| [SVGFitToViewPort](../../aspose.diagram.saving/svgsaveoptions/svgfittoviewport/) { get; set; } | если это свойство истинно, сгенерированный svg будет соответствовать порту просмотра. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Получает или задает обратный вызов предупреждения. |

### Смотрите также

* class [RenderingSaveOptions](../renderingsaveoptions/)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
