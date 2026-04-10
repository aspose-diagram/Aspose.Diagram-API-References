---
title: Campo
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que especifican funciones y fórmulas insertadas en el texto de las formas.
type: docs
weight: 147
url: /es/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Contiene elementos que especifican funciones y fórmulas insertadas en el texto de la forma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Field()](#Field--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Determina el calendario que se utiliza para propiedades personalizadas, campos de texto y fórmulas de elementos. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDisplayValue()](#getDisplayValue--) | Obtiene el valor de cadena formateada de este campo. |
| [getEditMode()](#getEditMode--) | Reservado para uso futuro. |
| [getFormat()](#getFormat--) | El elemento Format especifica el formato para un campo de texto que es una cadena, número, fecha u hora, duración o moneda. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getObjectKind()](#getObjectKind--) | Indica el tipo de campo de texto. |
| [getType()](#getType--) | Tipo especifica un tipo de datos para el valor del campo de texto. |
| [getUICat()](#getUICat--) | Especifica la categoría de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000. |
| [getUICod()](#getUICod--) | Especifica el código de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000. |
| [getUIFmt()](#getUIFmt--) | Especifica el formato de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000. |
| [getValue()](#getValue--) | Contiene el valor para un campo de texto. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Obtiene el valor de cadena formateada de este campo.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Reservado para uso futuro.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


El elemento Format especifica el formato para un campo de texto que es una cadena, número, fecha o hora, duración o moneda. El tipo de campo de texto se especifica en el elemento Type correspondiente.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Indica el tipo de campo de texto.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Tipo especifica un tipo de datos para el valor del campo de texto.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Especifica la categoría de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Especifica el código de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Especifica el formato de un campo insertado en versiones de Microsoft Visio anteriores a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Contiene el valor para un campo de texto.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/field\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

