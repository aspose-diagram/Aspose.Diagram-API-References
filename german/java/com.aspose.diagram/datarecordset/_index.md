---
title: DataRecordSet
second_title: Aspose.Diagram for Java API-Referenz
description: Speichert Formate, Aktualisierungen und stellt Daten bereit, die aus einer Datenbank in Microsoft Visio abgefragt wurden.
type: docs
weight: 113
url: /de/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Speichert, formatiert, aktualisiert und stellt Daten bereit, die aus einer Datenbank in Microsoft Visio abgefragt wurden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Enthält XML, das dem klassischen ADO‑XML‑Schema für ein ADO‑Recordset entspricht und die Daten im Daten‑Recordset beschreibt. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Definiert eine Regel, die eine Spalte im übergeordneten DataRecordset‑Element mit einem Formulardaten‑Element aus der letzten erfolgreichen automatischen Verknüpfungsaktion vergleicht, die in der Benutzeroberfläche durchgeführt wurde. |
| [getChecksum()](#getChecksum--) | Ein Prüfsummenwert, von Visio erzeugt und basierend auf den Eigenschaften des Daten‑Recordsets. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Der Befehlszeichenfolge, die zum Abfragen von Daten aus der Datenquelle verwendet wird. |
| [getConnectionID()](#getConnectionID--) | Die Verbindungs‑ID für das zugehörige DataConnection‑Objekt. |
| [getDataColumns()](#getDataColumns--) | Enthält alle DataColumn‑Elemente in einem Daten‑Recordset. |
| [getID()](#getID--) | Die Daten‑Recordset‑ID, eindeutig innerhalb des Dokuments. |
| [getName()](#getName--) | Der Anzeigen‑ (oder „freundliche“) Name des Daten‑Recordsets. |
| [getNextRowID()](#getNextRowID--) | Die nächste verfügbare Visio‑Zeilen‑ID. |
| [getOptions()](#getOptions--) | Optionen, die auf das Daten‑Recordset angewendet werden. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identifiziert eine oder mehrere Primärschlüssel‑Spalten im Daten‑Recordset. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Zeigt eine Zeile im Daten‑Recordset an, die mit einer Form verknüpft ist, die nach dem Aktualisieren des Daten‑Recordsets im Konflikt steht. |
| [getRefreshInterval()](#getRefreshInterval--) | Wie oft (in Minuten) Visio das Daten‑Recordset automatisch aktualisiert. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Ob die Benutzeroberfläche zur Datenabstimmung deaktiviert werden soll. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Ob Benutzeränderungen an Formdaten‑Elementen in Formen, die mit Daten verknüpft sind, beim Aktualisieren des Daten‑Recordsets überschrieben werden sollen. |
| [getReplaceLinks()](#getReplaceLinks--) | Definiert, wie Form‑Daten‑Verknüpfungen behandelt werden, wenn Formen kopiert oder ausgeschnitten werden. 1, um vorhandene Verknüpfungen im Zielobjekt zu ersetzen. 0, um vorhandene Verknüpfungen im Zielobjekt beizubehalten. |
| [getRowMaps()](#getRowMaps--) | Ordnet eine Daten‑Recordset‑Zeile einer Form zu. |
| [getRowOrder()](#getRowOrder--) | Ob die Reihenfolge der Zeilen im Daten‑Recordset als Primärschlüssel verwendet werden soll. |
| [getTimeRefreshed()](#getTimeRefreshed--) | Datum und Uhrzeit, zu der das Daten‑Recordset zuletzt aktualisiert wurde. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Führt die mit dem verbundenen (nicht XML‑basierten) DataRecordset verknüpfte Abfragezeichenfolge aus und aktualisiert verknüpfte Formen mit neuen Daten aus der Datenquelle, die durch die Abfrage zurückgegeben werden. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


Konstruktor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Enthält XML, das dem klassischen ADO‑XML‑Schema für ein ADO‑Recordset entspricht und die Daten im Daten‑Recordset beschreibt.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Definiert eine Regel, die eine Spalte im übergeordneten DataRecordset‑Element mit einem Formulardaten‑Element aus der letzten erfolgreichen automatischen Verknüpfungsaktion vergleicht, die in der Benutzeroberfläche durchgeführt wurde.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Ein von Visio erzeugter Prüfsummenwert, basierend auf den Eigenschaften des Datenrecordsets. Setzen Sie dieses Attribut auf 0; Visio berechnet diesen Wert zur Laufzeit neu.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


Der Befehlszeichenfolge, die zum Abfragen von Daten aus der Datenquelle verwendet wird.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


Die Verbindungs-ID für das zugehörige DataConnection-Objekt. Existiert nicht für XML-Datenquellen.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Enthält alle DataColumn‑Elemente in einem Daten‑Recordset.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


Die Daten‑Recordset‑ID, eindeutig innerhalb des Dokuments.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Der Anzeigen‑ (oder „freundliche“) Name des Daten‑Recordsets.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


Die nächste verfügbare Visio‑Zeilen‑ID.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Optionen, die auf das Datenrecordset angewendet werden. Mögliche Werte können beliebige Kombinationen von einem oder mehreren der in der folgenden Tabelle gezeigten Werte sein.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identifiziert eine oder mehrere Primärschlüssel‑Spalten im Daten‑Recordset.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Zeigt eine Zeile im Datenrecordset an, die mit einer Form verknüpft ist, die nach dem Aktualisieren des Datenrecordsets in Konflikt steht. RowID – Zeigt eine Zeile im Datenrecordset an, die mit einer Form verknüpft ist, die nach dem Aktualisieren des Datenrecordsets in Konflikt steht. ShapeID – Shape-ID der an dem Konflikt beteiligten Form. PageID – Seiten-ID der an dem Konflikt beteiligten Form.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Wie oft (in Minuten) Visio das Datenrecordset automatisch aktualisiert. Dieser Wert muss mindestens 1 sein.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Ob die Datenabgleich-Benutzeroberfläche deaktiviert werden soll. True (1) zum Deaktivieren der Benutzeroberfläche (UI). False (0) zum Aktivieren der UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Ob Benutzeränderungen an Formdaten‑Elementen in Formen, die mit Daten verknüpft sind, beim Aktualisieren des Daten‑Recordsets überschrieben werden sollen.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Definiert, wie Shape‑Daten‑Links behandelt werden, wenn Formen kopiert oder ausgeschnitten werden. 1, um vorhandene Links in der Ziel‑Form zu ersetzen. 0, um vorhandene Links in der Ziel‑Form beizubehalten. Wenn dieses Attribut fehlt, fragt Visio den Benutzer, ob Links beim Kopieren oder Ausschneiden ersetzt werden sollen.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Ordnet eine Zeile des Datenrecordsets einer Form zu. RowID – Zeilen‑ID der Zeile, eindeutig innerhalb des Datenrecordsets. ShapeID – Shape‑ID der Form, die mit den Daten der durch RowID identifizierten Zeile des Datenrecordsets verknüpft ist. PageID – Seiten‑ID der Form, die mit den Daten der durch RowID identifizierten Zeile des Datenrecordsets verknüpft ist.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Ob die Reihenfolge der Zeilen im Datenrecordset als Primärschlüssel verwendet werden soll. True (1), wenn Zeilen‑IDs durch die Zeilenreihenfolge bestimmt werden. False (0), wenn Zeilen‑IDs durch Werte in den Primärschlüssel‑Spalten des Datenrecordsets bestimmt werden.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


Datum und Uhrzeit, zu der das Daten‑Recordset zuletzt aktualisiert wurde.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


Führt die mit dem verbundenen (nicht XML‑basierten) DataRecordset verknüpfte Abfragezeichenfolge aus und aktualisiert verknüpfte Formen mit neuen Daten aus der Datenquelle, die durch die Abfrage zurückgegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connectionType | int | Der Typ des Anbieters, der für connectionAspose.Diagram.Manipulation.DataConnectionType verwendet wird. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

