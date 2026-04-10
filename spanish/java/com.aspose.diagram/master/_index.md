---
title: Master
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que definen una plantilla maestra para el documento.
type: docs
weight: 240
url: /es/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Contiene elementos que definen un master para el documento. Un master es una forma en una plantilla que se usa repetidamente para crear dibujos. Cuando arrastras una forma de una plantilla a la página de dibujo, la forma se convierte en una instancia de ese master, y una copia local del master se incluye en el documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Master()](#Master--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Especifica si el texto del master en la ventana de plantilla está alineado a la izquierda, a la derecha o al centro. |
| [getBaseID()](#getBaseID--) | Un GUID (identificador global único) que identifica el master entre documentos. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contiene un elemento Connect para cada conexión entre dos formas en un dibujo. |
| [getHidden()](#getHidden--) | Especifica si el master está oculto en la interfaz de usuario. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getIcon()](#getIcon--) | Especifica un icono binario codificado en MIME (Multipurpose Internet Mail Extensions) (en formato .ico) para un elemento Master o MasterShortcut en un documento. |
| [getIconSize()](#getIconSize--) | El tamaño del icono del elemento. |
| [getIconUpdate()](#getIconUpdate--) | Especifica si el icono se genera automáticamente a partir del propio master. |
| [getMatchByName()](#getMatchByName--) | El atributo MatchByName determina cómo Microsoft Visio decide si un master de documento ya está presente cuando se suelta una instancia de un master en la página de dibujo. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getPageSheet()](#getPageSheet--) | Contiene elementos que definen la hoja de página para un elemento Página o Maestro. |
| [getPatternFlags()](#getPatternFlags--) | El atributo PatternFlags determina si un master se comporta como un patrón personalizado. |
| [getPrompt()](#getPrompt--) | La barra de estado y la información sobre herramientas solicitan al elemento. |
| [getShapes()](#getShapes--) | Colección de objetos Shape. |
| [getUniqueID()](#getUniqueID--) | Un GUID que identifica el master dentro del documento. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Para la descripción de esta propiedad, consulte [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Para la descripción de esta propiedad, consulte [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Para la descripción de esta propiedad, consulte [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Para la descripción de esta propiedad, consulte [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Para la descripción de esta propiedad, consulte [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Para la descripción de esta propiedad, consulte [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Para la descripción de esta propiedad, consulte [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Para la descripción de esta propiedad, consulte [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Para la descripción de esta propiedad, consulte [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profunda de esta instancia.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Especifica si el texto del master en la ventana de plantilla está alineado a la izquierda, a la derecha o al centro.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Un GUID (identificador global único) que identifica el master entre documentos.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contiene un elemento Connect para cada conexión entre dos formas en un dibujo.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Especifica si el master está oculto en la interfaz de usuario.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Especifica un icono binario codificado en MIME (Multipurpose Internet Mail Extensions) (en formato .ico) para un elemento Master o MasterShortcut en un documento.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


El tamaño del icono del elemento.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Especifica si el icono se genera automáticamente a partir del propio master.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


El atributo MatchByName determina cómo Microsoft Visio decide si un master de documento ya está presente cuando se suelta una instancia de un master en la página de dibujo. Permite que los cambios realizados en un master de documento se apliquen a nuevas instancias del master, incluso si las instancias se arrastran desde un archivo de plantilla independiente.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contiene elementos que definen la hoja de página para un elemento Página o Maestro.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


El atributo PatternFlags determina si un master se comporta como un patrón personalizado.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


La barra de estado y la información sobre herramientas solicitan al elemento.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Colección de objetos Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID que identifica el master dentro del documento.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Para la descripción de esta propiedad, consulte [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Para la descripción de esta propiedad, consulte [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Para la descripción de esta propiedad, consulte [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Para la descripción de esta propiedad, consulte [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Para la descripción de esta propiedad, consulte [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Para la descripción de esta propiedad, consulte [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Para la descripción de esta propiedad, consulte [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Para la descripción de esta propiedad, consulte [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Para la descripción de esta propiedad, consulte [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

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

