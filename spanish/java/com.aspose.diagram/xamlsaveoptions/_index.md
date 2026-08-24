---
title: XAMLSaveOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Permite especificar opciones adicionales al renderizar páginas de diagrama a XAML.
type: docs
weight: 448
url: /es/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

Permite especificar opciones adicionales al renderizar páginas de diagrama a XAML.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | Inicializa una nueva instancia de esta clase que puede usarse para guardar un documento en el formato Aspose.Diagram.SaveFileFormat. |
## Métodos

| Método | Descripción |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un objeto de opciones de guardado de una clase adecuada para el formato de guardado especificado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Cuando los caracteres en el diagrama son Unicode y no se establecen con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en PDF, imagen o XPS. |
| [getPageCount()](#getPageCount--) | el número de páginas a renderizar en XAML. |
| [getPageIndex()](#getPageIndex--) | el índice basado en cero de la primera página a renderizar. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Especifica si todas las páginas se guardarán en una imagen o solo el primer plano. |
| [getSaveFormat()](#getSaveFormat--) | Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se utiliza este objeto de opciones de guardado. |
| [getStreamProvider()](#getStreamProvider--) | el IStreamProvider para exportar objetos. |
| [getWarningCallback()](#getWarningCallback--) | callback de advertencia. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Para la descripción de esta propiedad, consulte [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
```


Inicializa una nueva instancia de esta clase que puede usarse para guardar un documento en el formato Aspose.Diagram.SaveFileFormat.

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


el número de páginas a renderizar en XAML. El valor predeterminado es MaxValue, lo que significa que se renderizarán todas las páginas del diagrama.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


el índice basado en cero de la primera página a renderizar. El valor predeterminado es 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Especifica si todas las páginas se guardarán en la imagen o solo el primer plano. Si es true, se renderizan solo las páginas de primer plano (con fondo si está presente). Si es false, se renderizan las páginas de primer plano (con fondo si está presente) y luego esas páginas de fondo vacías. Solo puede devolver true cuando PageCount > 1. El valor predeterminado es false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se utiliza este objeto de opciones de guardado. Solo puede ser Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


el IStreamProvider para exportar objetos.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Para la descripción de esta propiedad, consulte [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

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

