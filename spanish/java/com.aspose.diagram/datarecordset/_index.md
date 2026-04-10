---
title: DataRecordSet
second_title: Referencia de API de Aspose.Diagram para Java
description: Almacena formatos, actualizaciones y expone los datos consultados de una base de datos en Microsoft Visio.
type: docs
weight: 113
url: /es/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Almacena, formatea, actualiza y expone datos consultados de una base de datos en Microsoft Visio.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Contiene XML que se ajusta al esquema XML clásico de ADO para un conjunto de registros ADO y que describe los datos en el conjunto de registros de datos. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Define una regla que compara una columna en el elemento DataRecordset padre con un elemento de datos de forma de la última acción de enlace automático exitosa realizada en la interfaz de usuario. |
| [getChecksum()](#getChecksum--) | Un valor de suma de verificación, generado por Visio, y basado en las propiedades del conjunto de registros de datos. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | La cadena de comando utilizada para consultar datos de la fuente de datos. |
| [getConnectionID()](#getConnectionID--) | El ID de conexión para el objeto DataConnection asociado. |
| [getDataColumns()](#getDataColumns--) | Contiene todos los elementos DataColumn en un conjunto de registros de datos. |
| [getID()](#getID--) | El ID del conjunto de registros de datos, único dentro del documento. |
| [getName()](#getName--) | El nombre de visualización (o "amigable") del conjunto de registros de datos. |
| [getNextRowID()](#getNextRowID--) | El siguiente ID de fila de Visio disponible. |
| [getOptions()](#getOptions--) | Opciones para aplicar al conjunto de registros de datos. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identifica una o más columnas de clave primaria en el conjunto de registros de datos. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Indica una fila en el conjunto de registros de datos vinculada a una forma que está en conflicto después de que el conjunto de registros de datos se actualiza. |
| [getRefreshInterval()](#getRefreshInterval--) | Con qué frecuencia (en minutos) Visio actualiza automáticamente el conjunto de registros de datos. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Si la interfaz de usuario de conciliación de datos debe estar deshabilitada. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Si se deben sobrescribir los cambios del usuario en los elementos de datos de forma en las formas vinculadas a datos cuando el conjunto de registros de datos se actualiza. |
| [getReplaceLinks()](#getReplaceLinks--) | Define cómo se tratan los enlaces de datos de forma cuando las formas se copian o recortan. 1 para reemplazar los enlaces existentes en la forma de destino. 0 para mantener los enlaces existentes en la forma de destino. |
| [getRowMaps()](#getRowMaps--) | Mapea una fila del conjunto de registros de datos a una forma. |
| [getRowOrder()](#getRowOrder--) | Si se debe usar el orden de las filas en el conjunto de registros de datos como clave primaria. |
| [getTimeRefreshed()](#getTimeRefreshed--) | La fecha y hora en que el conjunto de registros de datos se actualizó por última vez. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Ejecuta la cadena de consulta asociada con el DataRecordset conectado (no basado en XML) y actualiza las formas vinculadas con nuevos datos de la fuente de datos devueltos por la consulta. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Para la descripción de esta propiedad, por favor vea [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Para la descripción de esta propiedad, por favor vea [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Para la descripción de esta propiedad, consulte \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Para la descripción de esta propiedad, consulte [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Para la descripción de esta propiedad, consulte \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Para la descripción de esta propiedad, consulte [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Para la descripción de esta propiedad, consulte [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Para la descripción de esta propiedad, consulte [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Para la descripción de esta propiedad, consulte [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Para la descripción de esta propiedad, consulte [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Contiene XML que se ajusta al esquema XML clásico de ADO para un conjunto de registros ADO y que describe los datos en el conjunto de registros de datos.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Define una regla que compara una columna en el elemento DataRecordset padre con un elemento de datos de forma de la última acción de enlace automático exitosa realizada en la interfaz de usuario.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Un valor de suma de verificación, generado por Visio, y basado en las propiedades del conjunto de datos. Establezca este atributo en 0; Visio recalcula este valor en tiempo de ejecución.

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


La cadena de comando utilizada para consultar datos de la fuente de datos.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


El ID de conexión para el objeto DataConnection asociado. No existe para fuentes de datos XML.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Contiene todos los elementos DataColumn en un conjunto de registros de datos.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


El ID del conjunto de registros de datos, único dentro del documento.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


El nombre de visualización (o "amigable") del conjunto de registros de datos.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


El siguiente ID de fila de Visio disponible.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Opciones para aplicar al conjunto de datos. Los valores posibles pueden ser cualquier combinación de uno o más de los mostrados en la tabla siguiente.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identifica una o más columnas de clave primaria en el conjunto de registros de datos.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Indica una fila en el conjunto de datos vinculada a una forma que está en conflicto después de que el conjunto de datos se actualiza. RowID - Indica una fila en el conjunto de datos vinculada a una forma que está en conflicto después de que el conjunto de datos se actualiza. ShapeID - ID de la forma involucrada en el conflicto. PageID - ID de la página de la forma involucrada en el conflicto.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Con qué frecuencia (en minutos) Visio actualiza automáticamente el conjunto de datos. Este valor debe ser 1 o mayor.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Si la interfaz de usuario de reconciliación de datos debe estar deshabilitada. Verdadero (1) para deshabilitar la interfaz de usuario (UI). Falso (0) para habilitar la UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Si se deben sobrescribir los cambios del usuario en los elementos de datos de forma en las formas vinculadas a datos cuando el conjunto de registros de datos se actualiza.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Define cómo se tratan los enlaces de datos de forma cuando las formas se copian o recortan. 1 para reemplazar los enlaces existentes en la forma de destino. 0 para mantener los enlaces existentes en la forma de destino. Si este atributo está ausente, Visio pregunta al usuario si desea reemplazar los enlaces al copiar o recortar.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Mapea una fila del conjunto de datos a una forma. RowID - ID de fila de la fila, único dentro del conjunto de datos. ShapeID - ID de la forma vinculada a los datos en la fila del conjunto de datos identificada por RowID. PageID - ID de la página de la forma vinculada a los datos en la fila del conjunto de datos identificada por RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Si se debe usar el orden de las filas en el conjunto de datos como clave primaria. Verdadero (1) si los IDs de fila se determinan por el orden de las filas. Falso (0) si los IDs de fila se determinan por los valores en la(s) columna(s) de clave primaria del conjunto de datos.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


La fecha y hora en que el conjunto de registros de datos se actualizó por última vez.

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


Ejecuta la cadena de consulta asociada con el DataRecordset conectado (no basado en XML) y actualiza las formas vinculadas con nuevos datos de la fuente de datos devueltos por la consulta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| connectionType | int | El tipo de proveedor que se utilizará para connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Para la descripción de esta propiedad, por favor vea [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Para la descripción de esta propiedad, por favor vea [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Para la descripción de esta propiedad, por favor vea \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Para la descripción de esta propiedad, consulte \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Para la descripción de esta propiedad, consulte [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Para la descripción de esta propiedad, consulte \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Para la descripción de esta propiedad, consulte [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Para la descripción de esta propiedad, consulte [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Para la descripción de esta propiedad, consulte [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Para la descripción de esta propiedad, consulte [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Para la descripción de esta propiedad, consulte [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

