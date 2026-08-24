---
title: Propiedad
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos para definir propiedades personalizadas y elementos para asociar datos con una forma.
type: docs
weight: 309
url: /es/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Contiene elementos para definir propiedades personalizadas y elementos para asociar datos con una forma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Prop()](#Prop--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Determina el calendario que se utiliza para propiedades personalizadas, campos de texto y fórmulas de elementos. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getFormat()](#getFormat--) | El elemento de formato especifica el formato de una propiedad personalizada que es una cadena, lista fija, número, lista variable, fecha u hora, duración o moneda. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getInvisible()](#getInvisible--) | El elemento invisible especifica si la propiedad personalizada es visible en el cuadro de diálogo Propiedades personalizadas en Microsoft Visio. |
| [getLabel()](#getLabel--) | Especifica la etiqueta que aparece a los usuarios en el cuadro de diálogo Propiedades personalizadas. |
| [getLangID()](#getLangID--) | Indica el ID de configuración regional (LCID) del idioma en el que se ingresó la fórmula de la celda, el texto, la propiedad personalizada o el comentario. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getPrompt()](#getPrompt--) | El elemento de solicitud especifica el texto descriptivo o instructivo que aparece a los usuarios en el cuadro de diálogo Propiedades personalizadas cuando se selecciona la propiedad. |
| [getSortKey()](#getSortKey--) | Especifica una clave que determina el orden en que se enumeran las propiedades personalizadas en la interfaz de usuario de la aplicación. |
| [getType()](#getType--) | Tipo especifica un tipo de datos para el valor de la propiedad personalizada. |
| [getValue()](#getValue--) | Contiene datos XML bien formados, específicos de la solución, que están prefijados en un espacio de nombres explícito y se almacenan con un documento. |
| [getVerify()](#getVerify--) | Especifica si se solicita al usuario que introduzca información de la propiedad personalizada para una forma cuando se crea una instancia o la forma se duplica o copia. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Constructor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Crea una copia profunda de esta instancia.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
public Calendar getCalendar()
```


Determina el calendario que se utiliza para propiedades personalizadas, campos de texto y fórmulas de elementos.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


El elemento Format especifica el formato de una propiedad personalizada que es una cadena, lista fija, número, lista variable, fecha o hora, duración o moneda. El tipo de propiedad personalizada se especifica en el elemento Type correspondiente.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
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


El elemento invisible especifica si la propiedad personalizada es visible en el cuadro de diálogo Propiedades personalizadas en Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Especifica la etiqueta que aparece a los usuarios en el cuadro de diálogo Propiedades personalizadas.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indica el ID de configuración regional (LCID) del idioma en el que se ingresó la fórmula de la celda, el texto, la propiedad personalizada o el comentario.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


El elemento Prompt especifica el texto descriptivo o instructivo que aparece a los usuarios en el cuadro de diálogo Propiedades personalizadas cuando se selecciona la propiedad. Este texto también aparece como información sobre herramientas cuando el puntero del ratón se detiene sobre la propiedad en la ventana Propiedades personalizadas.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Especifica una clave que determina el orden en que se enumeran las propiedades personalizadas en la interfaz de usuario de la aplicación.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Tipo especifica un tipo de datos para el valor de la propiedad personalizada.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Contiene datos XML bien formados, específicos de la solución, que están prefijados en un espacio de nombres explícito y se almacenan con un documento.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Especifica si se solicita al usuario que introduzca información de la propiedad personalizada para una forma cuando se crea una instancia o la forma se duplica o copia.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

