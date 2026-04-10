---
title: DataRecordSet
second_title: Aspose.Diagram för Java API-referens
description: Lagrar format, uppdateringar och exponerar data som hämtas från en databas i Microsoft Visio.
type: docs
weight: 113
url: /sv/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Lagrar, formaterar, uppdaterar och exponerar data som hämtats från en databas i Microsoft Visio.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Innehåller XML som följer ADO:s klassiska XML-schema för ett ADO‑recordset och som beskriver data i data‑recordsetet. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Definierar en regel som jämför en kolumn i det överordnade DataRecordset-elementet med ett formdataobjekt från den senaste lyckade automatiska länkningsåtgärden som utförts i användargränssnittet. |
| [getChecksum()](#getChecksum--) | Ett kontrollsummavärde, genererat av Visio, och baserat på egenskaper för data‑recordsetet. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Kommandosträngen som används för att fråga data från datakällan. |
| [getConnectionID()](#getConnectionID--) | Anslutnings‑ID för det associerade DataConnection‑objektet. |
| [getDataColumns()](#getDataColumns--) | Innehåller alla DataColumn‑element i ett data‑recordset. |
| [getID()](#getID--) | Data‑recordset‑ID, unikt inom dokumentet. |
| [getName()](#getName--) | Visningsnamnet (eller "vänliga" namnet) för data‑recordsetet. |
| [getNextRowID()](#getNextRowID--) | Nästa tillgängliga Visio‑rad‑ID. |
| [getOptions()](#getOptions--) | Alternativ att tillämpa på data‑recordsetet. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identifierar en eller flera primärnyckelkolumner i data‑recordsetet. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Anger en rad i data‑recordsetet som är länkad till en form som är i konflikt efter att data‑recordsetet har uppdaterats. |
| [getRefreshInterval()](#getRefreshInterval--) | Hur ofta (i minuter) Visio automatiskt uppdaterar data‑recordsetet. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Om användargränssnittet för dataåterställning ska inaktiveras. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Om användarändringar av formdataobjekt i former som är länkade till data ska skrivas över när data‑recordsetet uppdateras. |
| [getReplaceLinks()](#getReplaceLinks--) | Definierar hur länkar mellan former och data behandlas när former kopieras eller klipps. 1 för att ersätta befintliga länkar i målformen. 0 för att behålla befintliga länkar i målformen. |
| [getRowMaps()](#getRowMaps--) | Mappar en rad i data‑recordsetet till en form. |
| [getRowOrder()](#getRowOrder--) | Om ordningen på raderna i data‑recordsetet ska användas som primärnyckel. |
| [getTimeRefreshed()](#getTimeRefreshed--) | Datum och tid då data‑recordsetet senast uppdaterades. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Kör frågesträngen som är associerad med den anslutna (icke‑XML‑baserade) DataRecordset och uppdaterar länkade former med ny data från datakällan som returneras av frågan. |
| [setADOData(String value)](#setADOData-java.lang.String-) | För beskrivningen av denna egenskap, se [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | För beskrivningen av denna egenskap, se [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | För beskrivningen av denna egenskap, se [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | För beskrivningen av denna egenskap, se [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | För beskrivningen av denna egenskap, se [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | För beskrivningen av denna egenskap, se [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | För beskrivningen av denna egenskap, se [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | För beskrivningen av denna egenskap, se [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Innehåller XML som följer ADO:s klassiska XML-schema för ett ADO‑recordset och som beskriver data i data‑recordsetet.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Definierar en regel som jämför en kolumn i det överordnade DataRecordset-elementet med ett formdataobjekt från den senaste lyckade automatiska länkningsåtgärden som utförts i användargränssnittet.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Ett kontrollsummevärde, genererat av Visio, och baserat på data-recordset-egenskaper. Sätt detta attribut till 0; Visio beräknar om detta värde vid körning.

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


Kommandosträngen som används för att fråga data från datakällan.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


Anslutnings-ID för det associerade DataConnection-objektet. Finns inte för XML-datakällor.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Innehåller alla DataColumn‑element i ett data‑recordset.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


Data‑recordset‑ID, unikt inom dokumentet.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Visningsnamnet (eller "vänliga" namnet) för data‑recordsetet.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


Nästa tillgängliga Visio‑rad‑ID.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Alternativ att tillämpa på datarecordsetet. Möjliga värden kan vara en kombination av en eller flera av de som visas i följande tabell.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identifierar en eller flera primärnyckelkolumner i data‑recordsetet.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Anger en rad i datarecordsetet som är länkad till en form som är i konflikt efter att datarecordsetet har uppdaterats. RowID - Anger en rad i datarecordsetet som är länkad till en form som är i konflikt efter att datarecordsetet har uppdaterats. ShapeID - Formens ID för den form som är inblandad i konflikten. PageID - Sidans ID för den form som är inblandad i konflikten.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Hur ofta (i minuter) Visio uppdaterar datarecordsetet automatiskt. Detta värde måste vara 1 eller större.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Om dataåterställnings-användargränssnittet ska vara inaktiverat. True (1) för att inaktivera användargränssnittet (UI). False (0) för att aktivera UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Om användarändringar av formdataobjekt i former som är länkade till data ska skrivas över när data‑recordsetet uppdateras.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Definierar hur shape-data-länkar behandlas när former kopieras eller klipps. 1 för att ersätta befintliga länkar i målformen. 0 för att behålla befintliga länkar i målformen. Om detta attribut saknas frågar Visio användaren om länkar ska ersättas vid kopiering eller klippning.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Mappar en data-recordset-rad till en form. RowID - Radens ID, unik inom datarecordsetet. ShapeID - Formens ID för den form som är länkad till data i data-recordset-raden identifierad av RowID. PageID - Sidans ID för den form som är länkad till data i data-recordset-raden identifierad av RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Om ordningen på raderna i datarecordsetet ska användas som primärnyckel. True (1) om rad-ID:n bestäms av radordning. False (0) om rad-ID:n bestäms av värden i primärnyckelkolumnen/kolumnerna i datarecordsetet.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


Datum och tid då data‑recordsetet senast uppdaterades.

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


Kör frågesträngen som är associerad med den anslutna (icke‑XML‑baserade) DataRecordset och uppdaterar länkade former med ny data från datakällan som returneras av frågan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connectionType | int | Typen av leverantör som kommer att användas för connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


För beskrivningen av denna egenskap, se [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


För beskrivningen av denna egenskap, se [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


För beskrivningen av denna egenskap, se [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


För beskrivningen av denna egenskap, se \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


För beskrivningen av denna egenskap, se [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


För beskrivningen av denna egenskap, se [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


För beskrivningen av denna egenskap, se [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


För beskrivningen av denna egenskap, se [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


För beskrivningen av denna egenskap, se [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

