---
title: Diagram
second_title: Справочник по Aspose.Diagram для .NET API
description: Корневой элемент иерархии объектов Visio.
type: docs
weight: 1170
url: /ru/net/aspose.diagram/diagram/
---
## Diagram class

Корневой элемент иерархии объектов Visio.

```csharp
public class Diagram : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Diagram](diagram/#constructor)() | Конструктор по умолчанию. |
| [Diagram](diagram/#constructor_1)(Stream) | Конструктор общедоступного класса, загружает диаграмму из потока. |
| [Diagram](diagram/#constructor_4)(string) | Конструктор общедоступного класса, загружает диаграмму из файла. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Конструктор общедоступного класса, загружает диаграмму из потока, используя предопределенный формат. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Конструктор общедоступного класса, загружает диаграмму из потока, используя предопределенные параметры файла загрузки. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Конструктор общедоступного класса, загружает диаграмму из файла, используя предопределенный формат. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Конструктор общедоступного класса, загружает диаграмму из файла, используя предопределенные параметры загрузки файла. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Указывает активную страницу |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Номер сборки экземпляра Visio, использованного для создания документа. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Содержит таблицу цветов документа. Каждый документ содержит одну таблицу цветов , в которой перечислены 24 стандартных цвета, доступных для применения к объектам , таким как фигуры, текст и слои в документе. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Содержит элементы DataConnection для документа. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Коллекция объектов DataRecordset, связанных с объектом Document. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | Уникальный идентификатор языка пользовательского интерфейса, который пользователь указал в языковых настройках Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Содержит элементы свойств документа, такие как название документа, автора и т. д. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Содержит элементы, определяющие параметры документа. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Указывает структуру документа ShapeSheet. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Содержит зашифрованную MIME (многоцелевые расширения почты Интернета) маршрутную накладную электронной почты MAPI для документа. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Содержит элемент EventItem для каждого события, на которое должен реагировать объект. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Указывает путь к папке со шрифтами |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Содержит коллекцию элементов шрифта |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Содержит элементы для верхнего и нижнего колонтитула документа. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Получает и устанавливает монитор прерываний. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Указывает, был ли документ изменен вне Visio. Если он присутствует, Visio полностью проверит содержимое файла. Не указывайте файлы, которые вы создаете вне Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Коллекция основных объектов. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Использовать ли метрические единицы на чертеже. Установите для этого атрибута значение True (1), чтобы использовать метрические единицы; установите значение False (0), чтобы использовать английские единицы измерения. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Объекты страницы коллекции. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | XML-строка ленты, которая передается в документ для настройки пользовательского интерфейса ленты. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | Значение XML. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Указывает, был ли документ изменен вне Visio. Если он присутствует, Visio полностью проверит содержимое файла. Не указывайте файлы, которые вы создаете вне Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Коллекция объектов таблицы стилей. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | XML-строка ленты, которая передается в документ для настройки панели быстрого доступа или ленты. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Сохраняет информацию о проверке диаграммы для документа. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Получает VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Содержит данные проекта Microsoft Visual Basic для приложений в закодированном формате MIME (многоцелевые расширения почты Интернета). |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Номер версии экземпляра Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Содержит элементы окна для документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Добавляет мастер к диаграмме из исходной диаграммы по имени мастера или NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Добавляет мастер на диаграмму из потока шаблона по ID мастера. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Добавляет мастер к диаграмме из потока шаблона по имени мастера или NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Добавляет мастер на диаграмму из файла шаблона по ID мастера. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Добавляет мастер на диаграмму из файла шаблона по имени мастера или NameU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Добавляет форму, созданную мастером, на определенную страницу. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Добавляет форму, созданную мастером на странице с определенными PinX и PinY. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Добавляет форму, созданную мастером на странице, с заданными PinX, PinY, шириной и высотой. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Объединяет другой объект диаграммы. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Копирует тему из исходника Diagram. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Получить путь к папке шрифтов по умолчанию |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Получить неиспользуемые стили |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Указывает, содержит ли эта диаграмма скрытую информацию. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Располагает формы и/или перенаправляет соединители для всех страниц схемы. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Печать всего документа на принтере по умолчанию. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Печать документа в соответствии с заданными настройками принтера с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Печать всего документа на принтере по умолчанию. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Печать всего документа на указанном принтере с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Печать документа в соответствии с заданными настройками принтера с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Печать документа в соответствии с указанными настройками принтера с использованием стандартного (без пользовательского интерфейса) контроллера печати и имени документа. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Печать всего документа на указанном принтере с использованием стандартного (без пользовательского интерфейса) контроллера печати. |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Печать документа с использованием стандартного (без пользовательского интерфейса) контроллера печати и имени документа. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Печать документа в соответствии с указанными настройками принтера с использованием стандартного (без пользовательского интерфейса) контроллера печати и имени документа. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Печать документа с использованием стандартного (без пользовательского интерфейса) контроллера печати и имени документа. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Вызывает метод обновления для всех DataRecordSet на диаграмме. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Удалить неиспользуемую информацию |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Удаляет VBA/макрос из этой диаграммы. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Сохраняет данные диаграммы в поток. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Сохраняет диаграмму в поток, используя указанные параметры сохранения. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Сохраняет данные диаграммы в файл. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Сохраняет документ в файл, используя указанные параметры сохранения. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Экспортирует диаграмму из потока vsd в формат потока vdw. Еще не реализовано. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Экспортирует диаграмму из потока vsd в файл формата *.vdw. Еще не реализовано. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Экспортирует диаграмму из файла vsd в потоковый формат vdw. Еще не реализовано. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Экспортирует диаграмму из формата vsd в формат vdw. Еще не реализовано. |

### Смотрите также

* пространство имен [Aspose.Diagram](../../aspose.diagram/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
