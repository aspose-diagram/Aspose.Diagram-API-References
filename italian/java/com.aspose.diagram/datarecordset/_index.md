---
title: DataRecordSet
second_title: Riferimento API di Aspose.Diagram per Java
description: Memorizza formati, aggiornamenti e espone i dati interrogati da un database in Microsoft Visio.
type: docs
weight: 113
url: /it/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Memorizza, formatta, aggiorna e espone i dati interrogati da un database in Microsoft Visio.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Contiene XML che conforma allo schema XML classico ADO per un recordset ADO e che descrive i dati nel recordset di dati. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Definisce una regola che confronta una colonna nell'elemento DataRecordset padre con un elemento dati di forma dell'ultima azione di collegamento automatico riuscita eseguita nell'interfaccia utente. |
| [getChecksum()](#getChecksum--) | Un valore di checksum, generato da Visio, basato sulle proprietà del recordset di dati. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | La stringa di comando utilizzata per interrogare i dati dalla fonte dati. |
| [getConnectionID()](#getConnectionID--) | L'ID di connessione per l'oggetto DataConnection associato. |
| [getDataColumns()](#getDataColumns--) | Contiene tutti gli elementi DataColumn in un recordset di dati. |
| [getID()](#getID--) | L'ID del recordset di dati, unico all'interno del documento. |
| [getName()](#getName--) | Il nome visualizzato (o "amichevole") del recordset di dati. |
| [getNextRowID()](#getNextRowID--) | Il prossimo ID di riga Visio disponibile. |
| [getOptions()](#getOptions--) | Opzioni da applicare al recordset di dati. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identifica una o più colonne chiave primaria nel recordset di dati. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Indica una riga nel recordset di dati collegata a una forma che è in conflitto dopo che il recordset di dati è stato aggiornato. |
| [getRefreshInterval()](#getRefreshInterval--) | Quanto spesso (in minuti) Visio aggiorna automaticamente il recordset di dati. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Se l'interfaccia utente di riconciliazione dei dati dovrebbe essere disabilitata. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Se sovrascrivere le modifiche dell'utente agli elementi dati della forma nelle forme collegate ai dati quando il recordset di dati è aggiornato. |
| [getReplaceLinks()](#getReplaceLinks--) | Definisce come i collegamenti forma-dati sono trattati quando le forme vengono copiate o tagliate. 1 per sostituire i collegamenti esistenti nella forma di destinazione. 0 per mantenere i collegamenti esistenti nella forma di destinazione. |
| [getRowMaps()](#getRowMaps--) | Mappa una riga del recordset di dati a una forma. |
| [getRowOrder()](#getRowOrder--) | Se utilizzare l'ordine delle righe nel recordset di dati come chiave primaria. |
| [getTimeRefreshed()](#getTimeRefreshed--) | La data e l'ora in cui il recordset di dati è stato aggiornato l'ultima volta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Esegue la stringa di query associata al DataRecordset connesso (non basato su XML) e aggiorna le forme collegate con nuovi dati dalla fonte dati restituiti dalla query. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | For the description of this property, please see \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | For the description of this property, please see [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | For the description of this property, please see \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | For the description of this property, please see [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | For the description of this property, please see [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | For the description of this property, please see [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | For the description of this property, please see [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


Costruttore.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Contiene XML che conforma allo schema XML classico ADO per un recordset ADO e che descrive i dati nel recordset di dati.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Definisce una regola che confronta una colonna nell'elemento DataRecordset padre con un elemento dati di forma dell'ultima azione di collegamento automatico riuscita eseguita nell'interfaccia utente.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


A checksum value, generated by Visio, and based on data-recordset properties. Set this attribute to 0; Visio recalculates this value at runtime.

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


La stringa di comando utilizzata per interrogare i dati dalla fonte dati.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


The connection ID for the associated DataConnection object. Does not exist for XML data sources.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Contiene tutti gli elementi DataColumn in un recordset di dati.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


L'ID del recordset di dati, unico all'interno del documento.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Il nome visualizzato (o "amichevole") del recordset di dati.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


Il prossimo ID di riga Visio disponibile.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identifica una o più colonne chiave primaria nel recordset di dati.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed. RowID - Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed. ShapeID - Shape ID of the shape involved in the conflict. PageID - Page ID of the shape involved in the conflict.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


How often (in minutes) Visio refreshes the data recordset automatically. This value must be 1 or larger.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Whether the data-reconciliation user interface should be disabled. True (1) to disable the user interface (UI). False (0) to enable the UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Se sovrascrivere le modifiche dell'utente agli elementi dati della forma nelle forme collegate ai dati quando il recordset di dati è aggiornato.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Defines how shape-data links are treated when shapes are copied or cut. 1 to replace existing links in the target shape. 0 to maintain existing links in the target shape. If this attribute is absent, Visio asks the user whether to replace links on copy or cut.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Maps a data-recordset row to a shape. RowID - Row ID of the row, unique within the data recordset. ShapeID - Shape ID of the shape linked to data in the data-recordset row identified by RowID. PageID - Page ID of the shape linked to data in the data-recordset row identified by RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Whether to use the order of the rows in the data recordset as the primary key. True (1) if row IDs are determined by row order. False (0) if row IDs are determined by values in the primary key column(s) of the data recordset.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


La data e l'ora in cui il recordset di dati è stato aggiornato l'ultima volta.

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


Esegue la stringa di query associata al DataRecordset connesso (non basato su XML) e aggiorna le forme collegate con nuovi dati dalla fonte dati restituiti dalla query.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connectionType | int | The type of provider which will be used for connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Per la descrizione di questa proprietà, vedere [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Per la descrizione di questa proprietà, vedere [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Per la descrizione di questa proprietà, vedere \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


For the description of this property, please see \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


For the description of this property, please see [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


For the description of this property, please see \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


For the description of this property, please see [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


For the description of this property, please see [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


For the description of this property, please see [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


For the description of this property, please see [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


For the description of this property, please see [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

