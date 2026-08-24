---
title: Hipervínculo
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos para crear múltiples saltos entre una forma o página de dibujo y otra página de dibujo, otro archivo o un sitio web.
type: docs
weight: 193
url: /es/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Contiene elementos para crear múltiples saltos entre una forma o página de dibujo y otra página de dibujo, otro archivo o un sitio web.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Especifica una dirección URL, un nombre de archivo DOS o una ruta UNC a la que saltar. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Especifica el hipervínculo predeterminado para una forma o página. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDescription()](#getDescription--) | El elemento Description contiene una cadena de texto que describe el hipervínculo. |
| [getExtraInfo()](#getExtraInfo--) | Contiene información que se utilizará para resolver una URL, como las coordenadas de un mapa de imagen. |
| [getFrame()](#getFrame--) | Contiene el nombre de un marco al que dirigirse cuando Microsoft Visio está abierto como documento activo en una aplicación contenedora. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getInvisible()](#getInvisible--) | El elemento Invisible indica si un hipervínculo aparece en el menú contextual de una forma o página. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getNewWindow()](#getNewWindow--) | Especifica si Microsoft Visio abre una ventana en una nueva ubicación cuando sigue un hipervínculo para abrir una página web u otro documento de Visio. |
| [getSortKey()](#getSortKey--) | El elemento Invisible indica si un hipervínculo aparece en el menú contextual de una forma o página. |
| [getSubAddress()](#getSubAddress--) | Especifica una ubicación dentro del documento de destino a la que enlazar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Especifica una dirección URL, un nombre de archivo DOS o una ruta UNC a la que saltar.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Especifica el hipervínculo predeterminado para una forma o página.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


El elemento Description contiene una cadena de texto que describe el hipervínculo.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Contiene información que se utilizará para resolver una URL, como las coordenadas de un mapa de imagen. Por ejemplo, x=41 y=7 especificaría las coordenadas de un mapa de imagen.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Contiene el nombre de un marco al que dirigirse cuando Microsoft Visio está abierto como documento activo en una aplicación contenedora. El valor predeterminado es una cadena vacía.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


El elemento Invisible indica si un hipervínculo aparece en el menú contextual de una forma o página.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Especifica si Microsoft Visio abre una ventana en una nueva ubicación cuando sigue un hipervínculo para abrir una página web u otro documento de Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


El elemento Invisible indica si un hipervínculo aparece en el menú contextual de una forma o página.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Especifica una ubicación dentro del documento de destino a la que enlazar.

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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

