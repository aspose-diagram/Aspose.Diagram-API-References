---
title: Act
second_title: Referencia de API de Aspose.Diagram para Java
description: Define nombres de comandos personalizados que aparecen en el menú contextual de un objeto y especifica las acciones que realizan los comandos.
type: docs
weight: 11
url: /es/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Define nombres de comandos personalizados que aparecen en el menú contextual de un objeto y especifica las acciones que realizan los comandos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Act()](#Act--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Contiene la fórmula que se ejecuta cuando un usuario hace clic en el nombre del comando definido en el elemento Menu correspondiente. |
| [getBeginGroup()](#getBeginGroup--) | Indica si se inserta un separador en el menú encima de esta acción. |
| [getButtonFace()](#getButtonFace--) | Identifica el ícono que aparece junto a un elemento en un menú contextual. |
| [getChecked()](#getChecked--) | Determina si se muestra una marca de verificación junto al nombre del comando en el menú contextual de una forma. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDisabled()](#getDisabled--) | El elemento Disabled determina si el nombre del comando se muestra en el menú contextual. |
| [getFlyoutChild()](#getFlyoutChild--) | Determina si la fila de acción es un submenú desplegable hijo de la última fila anterior que no es un hijo desplegable. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getInvisible()](#getInvisible--) | El elemento Invisible indica si la acción es visible en la etiqueta inteligente o en el menú contextual. |
| [getMenu()](#getMenu--) | Especifica el nombre del comando que aparece en el menú contextual de una forma o página. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getReadOnly()](#getReadOnly--) | Determina si la acción en una etiqueta inteligente o menú contextual es de solo lectura. |
| [getSortKey()](#getSortKey--) | Especifica un número que determina el orden de las acciones que aparecen en un menú contextual o de etiqueta inteligente. |
| [getTagName()](#getTagName--) | Contiene el nombre de la etiqueta inteligente con la que está asociada la acción. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profunda de esta instancia.

**Returns:**
java.lang.Object -
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Contiene la fórmula que se ejecuta cuando un usuario hace clic en el nombre del comando definido en el elemento Menu correspondiente.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Indica si se inserta un separador en el menú encima de esta acción.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Identifica el ícono que aparece junto a un elemento en un menú contextual.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Determina si se muestra una marca de verificación junto al nombre del comando en el menú contextual de una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


El elemento Disabled determina si el nombre del comando se muestra en el menú contextual.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Determina si la fila de acción es un submenú desplegable hijo de la última fila anterior que no es un hijo desplegable.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


El elemento Invisible indica si la acción es visible en la etiqueta inteligente o en el menú contextual.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Especifica el nombre del comando que aparece en el menú contextual de una forma o página.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public String getName()
```


El nombre del elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


El nombre universal del elemento.

**Returns:**
java.lang.String
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Determina si la acción en una etiqueta inteligente o menú contextual es de solo lectura.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Especifica un número que determina el orden de las acciones que aparecen en un menú contextual o de etiqueta inteligente.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Contiene el nombre de la etiqueta inteligente con la que está asociada la acción.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/act\#getNameU--)

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

