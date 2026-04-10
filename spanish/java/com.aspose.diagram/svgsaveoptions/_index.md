---
title: SVGSaveOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Permite especificar opciones adicionales al renderizar páginas de diagramas a SVG.
type: docs
weight: 347
url: /es/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Permite especificar opciones adicionales al renderizar páginas de diagramas a SVG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Inicializa una nueva instancia de esta clase que puede usarse para guardar un documento en el formato Aspose.Diagram.SaveFileFormat. |
## Métodos

| Método | Descripción |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un objeto de opciones de guardado de una clase adecuada para el formato de guardado especificado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | La ruta personalizada del usuario (URL) guardada en el archivo SVG generado para la imagen. |
| [getDefaultFont()](#getDefaultFont--) | Cuando los caracteres en el diagrama son Unicode y no se establecen con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en PDF, imagen o XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Configuración para renderizar metarchivo Emf. |
| [getEnlargePage()](#getEnlargePage--) | Especifica si se amplía la página. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Define si es necesario exportar los elementos de rectángulo como etiqueta rect o no. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Define si es necesario exportar las formas guía o no. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Define si es necesario exportar la página oculta o no. |
| [getPageIndex()](#getPageIndex--) | el índice basado en cero de la página a renderizar. |
| [getPageSize()](#getPageSize--) | el tamaño de página para las imágenes generadas. |
| [getQuality()](#getQuality--) | un valor que determina la calidad de las imágenes generadas y que se aplica solo al guardar páginas en formato JPEG. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | si esta propiedad es verdadera, el SVG generado se ajustará al viewport. |
| [getSaveFormat()](#getSaveFormat--) | Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado. |
| [getShapes()](#getShapes--) | formas a renderizar. |
| [getWarningCallback()](#getWarningCallback--) | callback de advertencia. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Define si es necesario exportar los comentarios o no. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Define si es necesario exportar la escala en una matriz o no. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Define si se guarda el patrón de línea personalizado. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Define si se guarda la imagen por separado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | Para la descripción de esta propiedad, consulte [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Para la descripción de esta propiedad, consulte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Para la descripción de esta propiedad, consulte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Para la descripción de esta propiedad, consulte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | Para la descripción de esta propiedad, consulte [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Para la descripción de esta propiedad, consulte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Para la descripción de esta propiedad, consulte [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | Para la descripción de esta propiedad, consulte [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Para la descripción de esta propiedad, consulte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | Para la descripción de esta propiedad, consulte [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | Para la descripción de esta propiedad, consulte [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Para la descripción de esta propiedad, consulte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | Para la descripción de esta propiedad, consulte [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | Para la descripción de esta propiedad, consulte [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Para la descripción de esta propiedad, consulte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


La ruta personalizada del usuario (URL) guardada en el archivo svg generado para la imagen. Si no es definida por el usuario, se utilizará el directorio actual.

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Define si es necesario exportar los elementos rectángulo como etiqueta rect o no. El valor predeterminado es false.

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


el índice basado en cero de la página a renderizar. El valor predeterminado es 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


el tamaño de página para las imágenes generadas. Puede ser [PageSize](../../com.aspose.diagram/pagesize) o nulo. El valor predeterminado es nulo. Si PageSize es nulo, entonces el tamaño de página para la imagen generada se obtiene del diagrama de origen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


un valor que determina la calidad de las imágenes generadas y se aplica solo al guardar páginas en formato JPEG. El valor predeterminado es 100. Tiene efecto solo al guardar en JPEG. El valor debe estar entre 0 y 100. El valor predeterminado es 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


si esta propiedad es verdadera, el SVG generado se ajustará al viewport.

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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Define si es necesario exportar la escala en una matriz o no. El valor predeterminado es true.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Define si se guarda el patrón de línea personalizado.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Define si se guarda la imagen por separado.

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


Para la descripción de esta propiedad, consulte [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


Para la descripción de esta propiedad, consulte [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


Para la descripción de esta propiedad, consulte [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


Para la descripción de esta propiedad, consulte [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Para la descripción de esta propiedad, consulte [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Para la descripción de esta propiedad, consulte [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


Para la descripción de esta propiedad, consulte [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

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

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


Para la descripción de esta propiedad, consulte [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


Para la descripción de esta propiedad, consulte [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

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

