---
title: DataRecordSet
second_title: Aspose.Diagram voor Java API-referentie
description: Slaat formaten, vernieuwt en maakt gegevens die uit een database zijn opgehaald beschikbaar in Microsoft Visio.
type: docs
weight: 113
url: /nl/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Slaat gegevens op, formatteert, ververst en maakt gegevens die uit een database zijn opgehaald in Microsoft Visio beschikbaar.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Bevat XML die voldoet aan het klassieke ADO XML-schema voor een ADO-recordset en die de gegevens in de datarecordset beschrijft. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Definieert een regel die een kolom in het bovenliggende DataRecordset-element vergelijkt met een vormgegevensitem van de laatste succesvolle automatische koppelingsactie die in de gebruikersinterface is uitgevoerd. |
| [getChecksum()](#getChecksum--) | Een checksum‑waarde, gegenereerd door Visio, en gebaseerd op eigenschappen van de data‑recordset. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | De opdracht‑tekst die wordt gebruikt om gegevens uit de gegevensbron op te vragen. |
| [getConnectionID()](#getConnectionID--) | De verbindings‑ID voor het bijbehorende DataConnection‑object. |
| [getDataColumns()](#getDataColumns--) | Bevat alle DataColumn‑elementen in een data‑recordset. |
| [getID()](#getID--) | De data‑recordset‑ID, uniek binnen het document. |
| [getName()](#getName--) | De weergave‑ (of \"vriendelijke\") naam van de data‑recordset. |
| [getNextRowID()](#getNextRowID--) | De volgende beschikbare Visio‑rij‑ID. |
| [getOptions()](#getOptions--) | Opties die op de data‑recordset moeten worden toegepast. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identificeert een of meer primaire‑sleutelkolommen in de data‑recordset. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Geeft een rij in de data‑recordset aan die gekoppeld is aan een vorm die in conflict is nadat de data‑recordset is vernieuwd. |
| [getRefreshInterval()](#getRefreshInterval--) | Hoe vaak (in minuten) Visio de data‑recordset automatisch vernieuwt. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Of de gebruikersinterface voor data‑reconciliatie uitgeschakeld moet worden. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Of gebruikerswijzigingen aan vorm‑data‑items in vormen die aan data zijn gekoppeld moeten worden overschreven wanneer de data‑recordset wordt vernieuwd. |
| [getReplaceLinks()](#getReplaceLinks--) | Definieert hoe vorm‑data‑koppelingen worden behandeld wanneer vormen worden gekopieerd of geknipt. 1 om bestaande koppelingen in de doelvorm te vervangen. 0 om bestaande koppelingen in de doelvorm te behouden. |
| [getRowMaps()](#getRowMaps--) | Koppelt een rij van de data‑recordset aan een vorm. |
| [getRowOrder()](#getRowOrder--) | Of de volgorde van de rijen in de data‑recordset als primaire sleutel moet worden gebruikt. |
| [getTimeRefreshed()](#getTimeRefreshed--) | De datum en tijd waarop de data‑recordset voor het laatst is vernieuwd. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Voert de query‑tekst uit die is gekoppeld aan de verbonden (niet‑XML‑gebaseerde) DataRecordset en werkt gekoppelde vormen bij met nieuwe gegevens uit de gegevensbron die door de query worden geretourneerd. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Voor de beschrijving van deze eigenschap, zie [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Voor de beschrijving van deze eigenschap, zie [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Voor de beschrijving van deze eigenschap, zie [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Voor de beschrijving van deze eigenschap, zie [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Voor de beschrijving van deze eigenschap, zie [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Voor de beschrijving van deze eigenschap, zie [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


Constructor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Bevat XML die voldoet aan het klassieke ADO XML-schema voor een ADO-recordset en die de gegevens in de datarecordset beschrijft.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Definieert een regel die een kolom in het bovenliggende DataRecordset-element vergelijkt met een vormgegevensitem van de laatste succesvolle automatische koppelingsactie die in de gebruikersinterface is uitgevoerd.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Een checksumwaarde, gegenereerd door Visio, en gebaseerd op eigenschappen van de data-recordset. Stel dit attribuut in op 0; Visio berekent deze waarde opnieuw tijdens runtime.

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


De opdracht‑tekst die wordt gebruikt om gegevens uit de gegevensbron op te vragen.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


De verbindings-ID voor het bijbehorende DataConnection-object. Bestaat niet voor XML-gegevensbronnen.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Bevat alle DataColumn‑elementen in een data‑recordset.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


De data‑recordset‑ID, uniek binnen het document.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


De weergave‑ (of \"vriendelijke\") naam van de data‑recordset.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


De volgende beschikbare Visio‑rij‑ID.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Opties die op de data-recordset moeten worden toegepast. Mogelijke waarden kunnen elke combinatie zijn van één of meer van de waarden die in de volgende tabel worden weergegeven.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identificeert een of meer primaire‑sleutelkolommen in de data‑recordset.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Geeft een rij in de data-recordset aan die is gekoppeld aan een vorm die in conflict is nadat de data-recordset is vernieuwd. RowID - Geeft een rij in de data-recordset aan die is gekoppeld aan een vorm die in conflict is nadat de data-recordset is vernieuwd. ShapeID - Vorm-ID van de betrokken vorm. PageID - Pagina-ID van de betrokken vorm.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Hoe vaak (in minuten) Visio de data-recordset automatisch vernieuwt. Deze waarde moet 1 of groter zijn.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Of de data-reconciliation gebruikersinterface moet worden uitgeschakeld. True (1) om de gebruikersinterface (UI) uit te schakelen. False (0) om de UI in te schakelen.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Of gebruikerswijzigingen aan vorm‑data‑items in vormen die aan data zijn gekoppeld moeten worden overschreven wanneer de data‑recordset wordt vernieuwd.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Definieert hoe shape-data koppelingen worden behandeld wanneer vormen worden gekopieerd of geknipt. 1 om bestaande koppelingen in de doelvorm te vervangen. 0 om bestaande koppelingen in de doelvorm te behouden. Als dit attribuut afwezig is, vraagt Visio de gebruiker of koppelingen moeten worden vervangen bij kopiëren of knippen.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Koppelt een data-recordset rij aan een vorm. RowID - Rij-ID van de rij, uniek binnen de data-recordset. ShapeID - Vorm-ID van de vorm die is gekoppeld aan gegevens in de data-recordset rij geïdentificeerd door RowID. PageID - Pagina-ID van de vorm die is gekoppeld aan gegevens in de data-recordset rij geïdentificeerd door RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Of de volgorde van de rijen in de data-recordset moet worden gebruikt als primaire sleutel. True (1) als rij‑ID's worden bepaald door de rijvolgorde. False (0) als rij‑ID's worden bepaald door waarden in de primaire‑sleutelkolom(men) van de data-recordset.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


De datum en tijd waarop de data‑recordset voor het laatst is vernieuwd.

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


Voert de query‑tekst uit die is gekoppeld aan de verbonden (niet‑XML‑gebaseerde) DataRecordset en werkt gekoppelde vormen bij met nieuwe gegevens uit de gegevensbron die door de query worden geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| connectionType | int | Het type provider dat zal worden gebruikt voor connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Voor de beschrijving van deze eigenschap, zie [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Voor de beschrijving van deze eigenschap, zie [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Voor de beschrijving van deze eigenschap, zie [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Voor de beschrijving van deze eigenschap, zie \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Voor de beschrijving van deze eigenschap, zie [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Voor de beschrijving van deze eigenschap, zie [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Voor de beschrijving van deze eigenschap, zie [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Voor de beschrijving van deze eigenschap, zie [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Voor de beschrijving van deze eigenschap, zie [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

