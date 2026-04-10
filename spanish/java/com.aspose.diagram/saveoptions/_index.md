---
title: SaveOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Esta es una clase base abstracta para clases que permiten al usuario especificar opciones adicionales al guardar un diagrama en un formato particular.
type: docs
weight: 349
url: /es/java/com.aspose.diagram/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

Esta es una clase base abstracta para clases que permiten al usuario especificar opciones adicionales al guardar un diagrama en un formato particular. Una instancia de la clase SaveOptions o cualquier clase derivada se pasa a las sobrecargas de Save de flujo o Save de cadena para que el usuario defina opciones personalizadas al guardar un documento.
## Métodos

| Método | Descripción |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un objeto de opciones de guardado de una clase adecuada para el formato de guardado especificado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Cuando los caracteres en el diagrama son Unicode y no se establecen con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en PDF, imagen o XPS. |
| [getSaveFormat()](#getSaveFormat--) | Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado. |
| [getWarningCallback()](#getWarningCallback--) | callback de advertencia. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Crea un objeto de opciones de guardado de una clase adecuada para el formato de guardado especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| saveFormat | int | El Aspose.Diagram.SaveFileFormat para el cual crear un objeto de opciones de guardado. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Cuando los caracteres del diagrama son Unicode y no se establecen con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en PDF, imagen o XPS. Establezca la DefaultFont, como MingLiu o MS Gothic, para mostrar estos caracteres.

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


callback de advertencia.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Para la descripción de esta propiedad, consulte [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

