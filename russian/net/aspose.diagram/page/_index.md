---
title: Page
second_title: Справочник по Aspose.Diagram для .NET API
description: Содержит элементы определяющие страницу в документе.
type: docs
weight: 2490
url: /ru/net/aspose.diagram/page/
---
## Page class

Содержит элементы, определяющие страницу в документе.

```csharp
public class Page : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Page](page/#constructor)() | Конструктор. |
| [Page](page/#constructor_1)(int) | Конструктор. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | Идентификатор исходной страницы чертежа, которая была размечена на отдельных наложениях разметки рецензентами чертежа. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Флаг, указывающий, является ли страница фоновой страницей. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | Фоновая страница страницы. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Содержит элемент Connect для каждого соединения между двумя фигурами на чертеже. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | Уникальный идентификатор элемента в его родительском элементе. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Имя элемента. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Универсальное имя элемента. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Коллекция страниц. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Содержит элементы, определяющие лист страницы для элемента Page или Master. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Применить предустановленную тему к этой странице |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Применить быстрый стиль предустановленной темы к этой странице |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Применить предустановленный вариант темы к этой странице |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | Идентификатор рецензента, связанного с наложением разметки. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Коллекция форм. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX и ViewCenterY определяют центральную точку на странице, которую новый вид (окно) принимает при первоначальном открытии. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX и ViewCenterY определяют центральную точку на странице, которую новый вид (окно) принимает при первоначальном открытии. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Коэффициент увеличения по умолчанию, используемый при открытии нового представления (окна) страницы. Например, 1 = 100%; 1,5 = 150% и т. д. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Создает элемент управления Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Добавляет комментарий к фигуре с идентификатором фигуры. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Добавляет комментарий к фигуре. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Добавляет комментарий с определенными PinX и PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Добавляет форму, созданную мастером, на определенную страницу. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Добавляет форму, созданную мастером на странице с определенными PinX и PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Добавляет форму, созданную мастером на странице, с заданными PinX, PinY, шириной и высотой. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Добавляет текст с определенными PinX и PinY. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Добавляет текст с определенными PinX и PinY. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Применяет стиль ко всей странице. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Формы автоматического пространства |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Переносит фигуру, определенную ID, на одну позицию вперед в z-порядке. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Помещает фигуру, определенную идентификатором, в начало z-порядка. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Центрирует фигуры страницы относительно экстента страницы. Центрирование фигур не меняет их положение относительно друг друга. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Соедините фигуры через коннектор. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Соедините фигуры через коннектор. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Соедините фигуры через коннектор. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Соедините фигуры через индекс соединителя. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Соедините фигуры через индекс соединителя. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Процесс рисования Безье. Длина точек должна быть равна или больше 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Процесс рисования Эллипса. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Процесс рисования одной линии. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Процесс рисования линии. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Процесс рисования линии. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Процесс рисования полилинии. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Процесс рисования полилинии. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Процесс рисования прямоугольника. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Процесс рисования сплайна. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Склейте формы |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Склейте формы. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Склеить фигуры в контейнере |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Склеить фигуры в контейнере, используя имя соединения |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Склеить фигуры по идентификатору соединения в container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Приклеить фигуру к BeginX соединителя |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Приклеить фигуру к EndX соединителя |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Размещает фигуры и/или перенаправляет соединители для страницы. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Перемещает страницу в другое место на страницах. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Перемещает фигуру, определенную ID, на одну позицию назад в z-порядке. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Перемещает фигуру, определенную идентификатором, в конец z-порядка. |

### Смотрите также

* пространство имен [Aspose.Diagram](../../aspose.diagram/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
