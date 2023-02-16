---
title: Window
second_title: Справочник по Aspose.Diagram для .NET API
description: Представляет открытое окно в экземпляре Microsoft Visio. Этот элемент содержит информацию необходимую для точного воссоздания окна пользовательского интерфейса в рабочей области приложения при первоначальном открытии файла DatadiagramML в Visio.
type: docs
weight: 4390
url: /ru/net/aspose.diagram/window/
---
## Window class

Представляет открытое окно в экземпляре Microsoft Visio. Этот элемент содержит информацию, необходимую для точного воссоздания окна пользовательского интерфейса в рабочей области приложения при первоначальном открытии файла DatadiagramML в Visio.

```csharp
public class Window
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Window](window/)() | Конструктор. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | Идентификатор контейнера: Страница, Лист или Мастер. Уместно и необходимо только в том случае, если указан ContainerType. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Может быть одним из следующих значений: Document, Page или Master. Имеет значение только в том случае, если WindowType указан как Drawing или Sheet. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Путь к файлу документа, отображаемого в этом окне. Этот атрибут актуален для окон, для которых WindowType указан как Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Указывает, включена ли функция динамической сетки для документа или окна. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Определяет объекты, которые формируют склеивание, когда склеивание включено в документе. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | Уникальный идентификатор элемента в его родительском элементе. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Идентификатор мастера, если в этом окне отображается мастер. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | Идентификатор страницы, если в этом окне отображается страница. Имеет значение, только если WindowType указан как Drawing, а ContainerType указан как Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID окна, в котором содержится это окно трафарета. Имеет значение, только если WindowType указан как Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Флаг только для чтения, если этот шаблон не является шаблоном документа. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID листа в контейнере. Актуально, только если Контейнер указан как Sheet. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Указывает, отображаются ли точки соединения в окне. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Указывает, отображается ли сетка в окне чертежа. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Указывает, отображаются ли направляющие в окне чертежа. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Указывает, отображаются ли разрывы страниц в окне. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Указывает, отображаются ли линейки в окне чертежа. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Содержит набор элементов SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Указывает, включена или отключена конкретная настройка расширения Snap для активного окна. Значение может быть суммой значений в следующей таблице. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Определяет объекты, к которым привязываются фигуры, когда привязка активна в окне. Значение может быть суммой значений в следующей таблице. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Указывает группу объединенных окон трафарета, членом которой является окно. Этот атрибут актуален только для элементов Window, чей атрибут WindowType имеет значение Stencil, и только в том случае, если окно шаблона является частью объединенной группы окон шаблона. Все окна шаблонов, входящие в состав одной объединенной группы, имеют одинаковое значение элемента StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Содержит целое число, указывающее относительное положение набора элементов в группе в окне. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Определяет ширину элемента управления вкладкой страницы окна чертежа (как часть общей ширины окна чертежа). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Дополнительный двойной. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Дополнительный двойной. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Дополнительный двойной. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Высота прямоугольника окна. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Левая координата прямоугольника окна. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Этот атрибут может быть суммой следующих значений. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Верхняя координата прямоугольника окна. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Пронумерованное значение, которое может быть одним из следующих: Drawing, Sheet, Stencil или Icon. Элемент Window WindowType='Stencil' должен появиться после своего родительского окна рисования (WindowType='Drawing') и перед любым другим окном рисования. элементы. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Ширина прямоугольника окна. |

### Смотрите также

* пространство имен [Aspose.Diagram](../../aspose.diagram/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
