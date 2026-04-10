---
title: PrintSaveOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Permite especificar opciones adicionales al imprimir el diagrama.
type: docs
weight: 308
url: /es/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Permite especificar opciones adicionales al imprimir el diagrama.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Inicializa una nueva instancia de esta clase |
## Métodos

| Método | Descripción |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un objeto de opciones de guardado de una clase adecuada para el formato de guardado especificado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Cuando los caracteres en el diagrama son Unicode y no se establecen con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en PDF, imagen o XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Configuración para renderizar metarchivo Emf. |
| [getEnlargePage()](#getEnlargePage--) | Especifica si se amplía la página. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Define si es necesario exportar las formas guía o no. |
| [getPageCount()](#getPageCount--) | el número de páginas a renderizar al guardar en un archivo multipágina. |
| [getPageSize()](#getPageSize--) | el tamaño de página para las imágenes generadas. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Especifica si se imprimirán todas las páginas o solo el primer plano. |
| [getSaveFormat()](#getSaveFormat--) | Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado. |
| [getShapes()](#getShapes--) | formas a renderizar. |
| [getWarningCallback()](#getWarningCallback--) | callback de advertencia. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Define si es necesario exportar los comentarios o no. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Para la descripción de esta propiedad, consulte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Para la descripción de esta propiedad, consulte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Para la descripción de esta propiedad, consulte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Para la descripción de esta propiedad, consulte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageCount(int value)](#setPageCount-int-) | Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Para la descripción de esta propiedad, consulte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Para la descripción de esta propiedad, consulte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Inicializa una nueva instancia de esta clase

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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Configuración para renderizar metafiles EMF. Los metafiles EMF identificados como "EMF+ Dual" pueden contener tanto registros EMF+ como registros EMF. Cualquiera de los tipos de registro puede usarse para renderizar la imagen, solo registros EMF+, o solo registros EMF. Cuando EmfPlusPrefer está configurado, se analizarán los registros EMF+, de lo contrario solo se analizarán los registros EMF. El valor predeterminado es EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Especifica si se debe ampliar la página. Si es verdadero, se amplía la página. Si es falso, no se amplía la página. El valor predeterminado es verdadero.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Define si es necesario exportar las formas guía o no. El valor predeterminado es verdadero.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


el número de páginas a renderizar al guardar en un archivo multipágina. El valor predeterminado es MaxValue, lo que significa que se imprimirán todas las páginas del diagrama.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


el tamaño de página para las imágenes generadas. Puede ser [PageSize](../../com.aspose.diagram/pagesize) o nulo. El valor predeterminado es nulo. Si PageSize es nulo, entonces el tamaño de página para la imagen generada se obtiene del diagrama de origen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Especifica si se imprimirán todas las páginas o solo el primer plano. Si es verdadero, se imprimen solo las páginas del primer plano (con fondo si está presente). Si es falso, se imprimen las páginas del primer plano (con fondo si está presente) y luego las páginas de fondo vacías. Solo puede devolver verdadero cuando PageCount > 1. El valor predeterminado es false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formas para renderizar. El recuento predeterminado es 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Define si es necesario exportar los comentarios o no. El valor predeterminado es false.

**Returns:**
boolean
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

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Para la descripción de esta propiedad, consulte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Para la descripción de esta propiedad, consulte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Para la descripción de esta propiedad, consulte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Para la descripción de esta propiedad, consulte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Para la descripción de esta propiedad, consulte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Para la descripción de esta propiedad, consulte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

