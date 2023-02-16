---
title: DataRecordSet
second_title: Aspose.Diagram für .NET-API-Referenz
description: Speichert formatiert aktualisiert und stellt Daten bereit die von einer Datenbank in Microsoft Visio abgefragt werden.
type: docs
weight: 1140
url: /de/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Speichert, formatiert, aktualisiert und stellt Daten bereit, die von einer Datenbank in Microsoft Visio abgefragt werden.

```csharp
public class DataRecordSet
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Enthält XML, das dem klassischen ADO-XML-Schema für ein ADO-Recordset entspricht und die Daten im Datensatz beschreibt. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Definiert eine Regel, die eine Spalte im übergeordneten DataRecordset-Element mit einem Shape-Datenelement aus der letzten erfolgreichen automatischen Verknüpfungsaktion vergleicht, die in der Benutzeroberfläche ausgeführt wurde. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Ein Prüfsummenwert, der von Visio generiert wird und auf Daten-Recordset-Eigenschaften basiert. Setzen Sie dieses Attribut auf 0; Visio berechnet diesen Wert zur Laufzeit neu. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | Die Befehlszeichenfolge, die zum Abfragen von Daten aus der Datenquelle verwendet wird. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | Die Verbindungs-ID für das zugeordnete DataConnection-Objekt. Existiert nicht für XML-Datenquellen. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Enthält alle DataColumn-Elemente in einem Datensatz. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | Die innerhalb des Dokuments eindeutige Datensatz-ID. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Der angezeigte (oder "freundliche") Name des Datensatzes. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | Die nächste verfügbare Visio-Zeilen-ID. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Optionen, die auf den Datensatz angewendet werden sollen. Mögliche Werte können eine beliebige Kombination aus einem oder mehreren der in der folgenden Tabelle gezeigten sein. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Identifiziert eine oder mehrere Primärschlüsselspalten im Datensatz. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Zeigt eine Zeile im Datensatz an, die mit einer Form verknüpft ist, die nach der Aktualisierung des Datensatzes in Konflikt steht. RowID – Zeigt eine Zeile im Datensatz an, die mit einer Form verknüpft ist, die nach der Aktualisierung des Datensatzes in Konflikt steht. ShapeID - Form-ID der Form, die in den Konflikt verwickelt ist. Seiten-ID - Seiten-ID der Form, die in den Konflikt verwickelt ist. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Wie oft (in Minuten) Visio den Datensatz automatisch aktualisiert. Dieser Wert muss 1 oder größer sein. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Ob die Benutzeroberfläche für den Datenabgleich deaktiviert werden soll. True (1), um die Benutzeroberfläche (UI) zu deaktivieren. Falsch (0), um die Benutzeroberfläche zu aktivieren. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Ob Benutzeränderungen an Shape-Datenelementen in Shapes, die mit Daten verknüpft sind, überschrieben werden sollen, wenn der Datensatz aktualisiert wird. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Definiert, wie Shape-Daten-Links behandelt werden, wenn Shapes kopiert oder ausgeschnitten werden. 1, um vorhandene Verknüpfungen in der Zielform zu ersetzen. 0, um vorhandene Verknüpfungen in der Zielform beizubehalten. Fehlt dieses Attribut, fragt Visio den Benutzer, ob Links beim Kopieren oder Ausschneiden ersetzt werden sollen. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Ordnet eine Zeile eines Datensatzsatzes einer Form zu. RowID - Zeilen-ID der Zeile, die innerhalb des Datensatzes eindeutig ist. ShapeID - Shape-ID der Form, die mit Daten in der durch RowID identifizierten Zeile des Datensatzsatzes verknüpft ist. PageID - Seiten-ID der Form, die mit Daten in der durch RowID. identifizierten Datensatzzeile verknüpft ist |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Ob die Reihenfolge der Zeilen im Datensatz als Primärschlüssel verwendet werden soll. True (1), wenn Zeilen-IDs durch die Zeilenreihenfolge bestimmt werden. Falsch (0), wenn Zeilen-IDs durch Werte in der/den Primärschlüsselspalte(n) des Datensatzes bestimmt werden. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | Datum und Uhrzeit der letzten Aktualisierung des Datensatzes. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Führt die dem verbundenen (nicht XML-basierten) DataRecordset zugeordnete Abfragezeichenfolge aus und aktualisiert verknüpfte Shapes mit neuen Daten aus der von der Abfrage zurückgegebenen Datenquelle. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Führt die dem verbundenen (nicht XML-basierten) DataRecordset zugeordnete Abfragezeichenfolge aus und aktualisiert verknüpfte Shapes mit neuen Daten aus der von der Abfrage zurückgegebenen Datenquelle. |

### Siehe auch

* namensraum [Aspose.Diagram](../../aspose.diagram/)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
