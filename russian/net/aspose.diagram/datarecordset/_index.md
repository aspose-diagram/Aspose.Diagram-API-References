---
title: DataRecordSet
second_title: Справочник по Aspose.Diagram для .NET API
description: Сохраняет форматирует обновляет и предоставляет данные запрошенные из базы данных в Microsoft Visio.
type: docs
weight: 1140
url: /ru/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Сохраняет, форматирует, обновляет и предоставляет данные, запрошенные из базы данных в Microsoft Visio.

```csharp
public class DataRecordSet
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Конструктор. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Содержит XML, соответствующий классической XML-схеме ADO для набора записей ADO и описывающий данные в наборе записей данных. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Определяет правило, которое сравнивает столбец в родительском элементе DataRecordset с элементом данных формы из последнего успешного действия автоматического связывания, выполненного в пользовательском интерфейсе. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Значение контрольной суммы, созданное Visio на основе свойств набора записей данных. Установите для этого атрибута значение 0; Visio пересчитывает это значение во время выполнения. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | Командная строка, используемая для запроса данных из источника данных. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | Идентификатор соединения для связанного объекта DataConnection. Не существует для источников данных XML. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Содержит все элементы DataColumn в наборе записей данных. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | ID набора записей данных, уникальный в пределах документа. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Отображаемое (или понятное) имя набора записей данных. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | Идентификатор следующей доступной строки Visio. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Параметры для применения к набору записей данных. Возможные значения могут быть любой комбинацией одного или нескольких значений, показанных в следующей таблице. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Идентифицирует один или несколько столбцов первичного ключа в наборе записей данных. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Указывает строку в наборе записей данных, связанную с фигурой, которая находится в конфликте после обновления набора записей данных. RowID — указывает строку в наборе записей данных, связанную с фигурой, которая находится в конфликте после обновления набора записей данных. ShapeID - Идентификатор фигуры, участвующей в конфликте. PageID - Идентификатор страницы фигуры, участвующей в конфликте. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Как часто (в минутах) Visio автоматически обновляет набор записей данных. Это значение должно быть 1 или больше. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Должен ли быть отключен пользовательский интерфейс согласования данных. True (1), чтобы отключить пользовательский интерфейс (UI). False (0), чтобы включить пользовательский интерфейс. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Следует ли перезаписывать пользовательские изменения элементов данных формы в формах, связанных с данными, при обновлении набора записей данных. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Определяет, как обрабатываются ссылки на данные формы при копировании или вырезании фигур. 1, чтобы заменить существующие ссылки в целевой форме. 0, чтобы сохранить существующие ссылки в целевой форме. Если этот атрибут отсутствует, Visio спрашивает пользователя, заменять ли ссылки при копировании или вырезании. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Сопоставляет строку набора записей данных с фигурой. RowID — идентификатор строки строки, уникальный в наборе записей данных. Идентификатор страницы фигуры, связанной с данными в строке набора записей данных, определяемой RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Следует ли использовать порядок строк в наборе записей данных в качестве первичного ключа. Истинно (1), если идентификаторы строк определяются порядком строк. False (0), если идентификаторы строк определяются значениями в столбцах первичного ключа набора записей данных. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | Дата и время последнего обновления набора записей данных. |

## Методы

| Имя | Описание |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Выполняет строку запроса, связанную с подключенным (не основанным на XML) DataRecordset, и обновляет связанные фигуры новыми данными из источника данных, возвращенного запросом. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Выполняет строку запроса, связанную с подключенным (не основанным на XML) DataRecordset, и обновляет связанные фигуры новыми данными из источника данных, возвращенного запросом. |

### Смотрите также

* пространство имен [Aspose.Diagram](../../aspose.diagram/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
