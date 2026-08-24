---
title: DataColumn
second_title: Referencia de API de Aspose.Diagram para Java
description: Define cómo aparece una columna de datos en la ventana de Datos externos en la interfaz de usuario de Visio y califica los datos en la columna definiendo su tipo de datos y formato.
type: docs
weight: 108
url: /es/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Define cómo aparece una columna de datos en la ventana de Datos externos en la interfaz de usuario de Visio y califica los datos en la columna definiendo su tipo de datos y formato.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DataColumn()](#DataColumn--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | ID de calendario de la columna de datos. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | Nombre externo de la columna de datos. |
| [getCurrency()](#getCurrency--) | ID de moneda de la columna de datos. |
| [getDataType()](#getDataType--) | Tipo de los datos en la columna de datos. |
| [getDegree()](#getDegree--) | Especifica el grado (potencia) de las unidades, por ejemplo al cuadrado o al cubo. |
| [getDisplayOrder()](#getDisplayOrder--) | Define la posición de visualización de la columna de datos en la ventana de Datos externos, desde la columna más a la izquierda (0) hasta la columna más a la derecha (valor máximo). |
| [getDisplayWidth()](#getDisplayWidth--) | Ancho de la columna de datos en la ventana de Datos externos. |
| [getHyperlink()](#getHyperlink--) | Si la columna de datos crea un hipervínculo en una forma cuando la forma está vinculada a datos. |
| [getLabel()](#getLabel--) | Etiqueta de la columna de datos. |
| [getLangID()](#getLangID--) | El ID de idioma de la columna de datos |
| [getMapped()](#getMapped--) | Especifica si la columna es visible en la ventana de Datos externos. |
| [getName()](#getName--) | Nombre interno de la columna de datos. |
| [getOrigLabel()](#getOrigLabel--) | Etiqueta de columna devuelta a Visio por la interfaz ADO subyacente. |
| [getUnitType()](#getUnitType--) | Tipo de unidad de los datos en la columna de datos. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | Para la descripción de esta propiedad, consulte [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--) |
| [setCurrency(int value)](#setCurrency-int-) | Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getCurrency() & 0xFFFF)\} |
| [setDataType(int value)](#setDataType-int-) | Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getDataType() & 0xFFFF)\} |
| [setDegree(long value)](#setDegree-long-) | Para la descripción de esta propiedad, consulte [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--) |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | Para la descripción de esta propiedad, consulte [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--) |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | Para la descripción de esta propiedad, consulte [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--) |
| [setHyperlink(int value)](#setHyperlink-int-) | Para la descripción de esta propiedad, consulte [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--) |
| [setLabel(String value)](#setLabel-java.lang.String-) | Para la descripción de esta propiedad, consulte [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--) |
| [setLangID(long value)](#setLangID-long-) | Para la descripción de esta propiedad, consulte [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--) |
| [setMapped(int value)](#setMapped-int-) | Para la descripción de esta propiedad, consulte [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/datacolumn\#getName--) |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | Para la descripción de esta propiedad, consulte [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--) |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | Para la descripción de esta propiedad, consulte [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


ID de calendario de la columna de datos.

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


Nombre externo de la columna de datos. Aparece en los encabezados de la ventana de Datos externos y en las etiquetas de los gráficos de datos.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


ID de moneda de la columna de datos.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


Tipo de los datos en la columna de datos.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


Especifica el grado (potencia) de las unidades, por ejemplo al cuadrado o al cubo. El valor predeterminado (atributo ausente) es 1.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


Define la posición de visualización de la columna de datos en la ventana de Datos externos, desde la columna más a la izquierda (0) hasta la columna más a la derecha (valor máximo).

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


Ancho de la columna de datos en la ventana de Datos externos.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


Si la columna de datos crea un hipervínculo en una forma cuando la forma está vinculada a datos.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


Etiqueta de la columna de datos.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


El ID de idioma de la columna de datos

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


Especifica si la columna es visible en la ventana de Datos externos. Verdadero (1) para que la columna sea visible; falso (0) para que la columna no sea visible. El valor predeterminado (atributo ausente) es que la columna sea visible.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Nombre interno de la columna de datos. Se usa como nombre de fila para el elemento de datos de forma (propiedad personalizada) añadido a una forma cuando la forma está vinculada a una fila de datos.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


Etiqueta de columna devuelta a Visio por la interfaz ADO subyacente.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


Tipo de unidad de los datos en la columna de datos.

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


Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


Para la descripción de esta propiedad, consulte [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getCurrency() & 0xFFFF)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


Para la descripción de esta propiedad, consulte \{@link DataColumn\#(getDataType() & 0xFFFF)\}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


Para la descripción de esta propiedad, consulte [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


Para la descripción de esta propiedad, consulte [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


Para la descripción de esta propiedad, consulte [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


Para la descripción de esta propiedad, consulte [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


Para la descripción de esta propiedad, consulte [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


Para la descripción de esta propiedad, consulte [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


Para la descripción de esta propiedad, consulte [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/datacolumn\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


Para la descripción de esta propiedad, consulte [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


Para la descripción de esta propiedad, consulte [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

