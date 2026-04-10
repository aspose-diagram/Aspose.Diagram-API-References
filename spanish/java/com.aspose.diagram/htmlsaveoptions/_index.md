---
title: HTMLSaveOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Permite especificar opciones adicionales al renderizar páginas de diagramas a HTML.
type: docs
weight: 187
url: /es/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Permite especificar opciones adicionales al renderizar páginas de diagramas a HTML.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Inicializa una nueva instancia de esta clase que puede usarse para guardar un documento en el formato Aspose.Diagram.SaveFileFormat. |
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
| [getExportHiddenPage()](#getExportHiddenPage--) | Define si es necesario exportar la página oculta o no. |
| [getPageCount()](#getPageCount--) | el número de páginas a renderizar en HTML. |
| [getPageIndex()](#getPageIndex--) | el índice basado en cero de la primera página a renderizar. |
| [getPageSize()](#getPageSize--) | el tamaño de página para las imágenes generadas. |
| [getResolution()](#getResolution--) | la resolución para el HTML generado, en puntos por pulgada. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Indica si se guarda el HTML como un solo archivo. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Especifica si todas las páginas se guardarán en una imagen o solo el primer plano. |
| [getSaveFormat()](#getSaveFormat--) | Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se utiliza este objeto de opciones de guardado. |
| [getSaveTitle()](#getSaveTitle--) | Define si es necesario exportar el título o no. |
| [getSaveToolBar()](#getSaveToolBar--) | Especifica si se guarda la barra de herramientas. El valor predeterminado es true. |
| [getShapes()](#getShapes--) | formas a renderizar. |
| [getStreamProvider()](#getStreamProvider--) | el IStreamProvider para exportar objetos. |
| [getTitle()](#getTitle--) | el título del diagrama a renderizar en HTML. |
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
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Para la descripción de esta propiedad, consulte [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Para la descripción de esta propiedad, consulte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Para la descripción de esta propiedad, consulte [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Para la descripción de esta propiedad, consulte [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Para la descripción de esta propiedad, consulte [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Para la descripción de esta propiedad, consulte [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Para la descripción de esta propiedad, consulte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Para la descripción de esta propiedad, consulte [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Para la descripción de esta propiedad, consulte [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Define si es necesario exportar la página oculta o no. El valor predeterminado es verdadero.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


el número de páginas a renderizar en HTML. El valor predeterminado es MaxValue, lo que significa que se renderizarán todas las páginas del diagrama.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


el índice basado en cero de la primera página a renderizar. El valor predeterminado es 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


el tamaño de página para las imágenes generadas. Puede ser [PageSize](../../com.aspose.diagram/pagesize) o nulo. El valor predeterminado es nulo. Si PageSize es nulo, entonces el tamaño de página para la imagen generada se obtiene del diagrama de origen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


la resolución para el html generado, en puntos por pulgada. Esta propiedad tiene efecto solo al guardar en html. El valor predeterminado es 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Indica si se guarda el html como un solo archivo. El valor predeterminado es false. Si hay varias páginas, esas páginas y otros recursos deben guardarse en archivos separados. En algunos escenarios, el usuario puede necesitar obtener solo un archivo resultante, por conveniencia de la transferencia. Si es así, el usuario puede establecer esta propiedad como true.

**Returns:**
boolean
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
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Define si es necesario exportar el título o no. El valor predeterminado es true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Especifica si se guarda la barra de herramientas. El valor predeterminado es true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formas para renderizar. El recuento predeterminado es 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


el IStreamProvider para exportar objetos.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


el título del diagrama a renderizar en HTML. Si Title es nulo, se utilizará Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) como Título. Si Diagram.DocumentProperties.Title es nulo o está vacío, se usará el nombre de archivo del Diagrama como Título.

**Returns:**
java.lang.String
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Para la descripción de esta propiedad, consulte [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Para la descripción de esta propiedad, consulte [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Para la descripción de esta propiedad, consulte [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Para la descripción de esta propiedad, consulte [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Para la descripción de esta propiedad, consulte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Para la descripción de esta propiedad, consulte [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Para la descripción de esta propiedad, consulte [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

