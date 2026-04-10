---
title: DataColumn
second_title: Riferimento API di Aspose.Diagram per Java
description: Definisce come una colonna dati appare nella finestra Dati esterni nell'interfaccia utente di Visio e qualifica i dati nella colonna definendo il suo tipo di dato e la formattazione.
type: docs
weight: 108
url: /it/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Definisce come una colonna dati appare nella finestra Dati esterni nell'interfaccia utente di Visio e qualifica i dati nella colonna definendo il suo tipo di dato e la formattazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DataColumn()](#DataColumn--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | ID del calendario della colonna dati. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | Nome esterno della colonna dati. |
| [getCurrency()](#getCurrency--) | ID della valuta della colonna dati. |
| [getDataType()](#getDataType--) | Tipo dei dati nella colonna dati. |
| [getDegree()](#getDegree--) | Specifica il grado (potenza) delle unità, ad esempio quadrato o cubico. |
| [getDisplayOrder()](#getDisplayOrder--) | Definisce la posizione di visualizzazione della colonna dati nella finestra Dati esterni, dalla colonna più a sinistra (0) alla colonna più a destra (valore più grande). |
| [getDisplayWidth()](#getDisplayWidth--) | Larghezza della colonna dati nella finestra Dati esterni. |
| [getHyperlink()](#getHyperlink--) | Indica se la colonna dati crea un collegamento ipertestuale in una forma quando la forma è collegata ai dati. |
| [getLabel()](#getLabel--) | Etichetta della colonna dati. |
| [getLangID()](#getLangID--) | L'ID della lingua della colonna dati |
| [getMapped()](#getMapped--) | Specifica se la colonna è visibile nella finestra Dati esterni. |
| [getName()](#getName--) | Nome interno della colonna dati. |
| [getOrigLabel()](#getOrigLabel--) | Etichetta della colonna restituita a Visio dall'interfaccia ADO sottostante. |
| [getUnitType()](#getUnitType--) | Tipo di unità dei dati nella colonna dati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--) |
| [setCurrency(int value)](#setCurrency-int-) | Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getCurrency() & 0xFFFF)\} |
| [setDataType(int value)](#setDataType-int-) | Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getDataType() & 0xFFFF)\} |
| [setDegree(long value)](#setDegree-long-) | Per la descrizione di questa proprietà, vedere [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--) |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | Per la descrizione di questa proprietà, vedere [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--) |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | Per la descrizione di questa proprietà, vedere [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--) |
| [setHyperlink(int value)](#setHyperlink-int-) | Per la descrizione di questa proprietà, vedere [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--) |
| [setLabel(String value)](#setLabel-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--) |
| [setLangID(long value)](#setLangID-long-) | Per la descrizione di questa proprietà, vedere [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--) |
| [setMapped(int value)](#setMapped-int-) | Per la descrizione di questa proprietà, vedere [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/datacolumn\#getName--) |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--) |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


ID del calendario della colonna dati.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


Nome esterno della colonna dati. Compare nelle intestazioni nella finestra Dati esterni e nelle etichette nei grafici dati.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


ID della valuta della colonna dati.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


Tipo dei dati nella colonna dati.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


Specifica il grado (potenza) delle unità, ad esempio quadrato o cubico. Il valore predefinito (attributo assente) è 1.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


Definisce la posizione di visualizzazione della colonna dati nella finestra Dati esterni, dalla colonna più a sinistra (0) alla colonna più a destra (valore più grande).

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


Larghezza della colonna dati nella finestra Dati esterni.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


Indica se la colonna dati crea un collegamento ipertestuale in una forma quando la forma è collegata ai dati.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


Etichetta della colonna dati.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


L'ID della lingua della colonna dati

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


Specifica se la colonna è visibile nella finestra Dati esterni. True (1) per rendere la colonna visibile; false (0) per renderla non visibile. Il valore predefinito (attributo assente) è che la colonna sia visibile.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Nome interno della colonna dati. Utilizzato come nome della riga per l'elemento dati forma (proprietà personalizzata) aggiunto a una forma quando la forma è collegata a una riga dati.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


Etichetta della colonna restituita a Visio dall'interfaccia ADO sottostante.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


Tipo di unità dei dati nella colonna dati.

**Returns:**
java.lang.String
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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


Per la descrizione di questa proprietà, vedere [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getCurrency() & 0xFFFF)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


Per la descrizione di questa proprietà, vedere \{@link DataColumn\#(getDataType() & 0xFFFF)\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


Per la descrizione di questa proprietà, vedere [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


Per la descrizione di questa proprietà, vedere [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


Per la descrizione di questa proprietà, vedere [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


Per la descrizione di questa proprietà, vedere [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


Per la descrizione di questa proprietà, vedere [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


Per la descrizione di questa proprietà, vedere [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


Per la descrizione di questa proprietà, vedere [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/datacolumn\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


Per la descrizione di questa proprietà, vedere [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


Per la descrizione di questa proprietà, vedere [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

