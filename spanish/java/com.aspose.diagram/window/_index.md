---
title: Window
second_title: Referencia de API de Aspose.Diagram para Java
description: Representa una ventana abierta en una instancia de Microsoft Visio.
type: docs
weight: 444
url: /es/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Representa una ventana abierta en una instancia de Microsoft Visio. Este elemento contiene la información necesaria para recrear exactamente una ventana de la interfaz de usuario en el espacio de trabajo de la aplicación cuando el archivo DatadiagramML se abre inicialmente por Visio.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Window()](#Window--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID del contenedor: Página, Hoja o Maestro. |
| [getContainerType()](#getContainerType--) | Puede ser uno de los siguientes valores: Document, Page, o Master. |
| [getDocument()](#getDocument--) | Ruta del archivo del documento mostrado en esta ventana. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Especifica si la función de cuadrícula dinámica está habilitada para un documento o ventana. |
| [getGlueSettings()](#getGlueSettings--) | Especifica los objetos a los que se adhieren las formas cuando el pegado está habilitado en el documento. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getMaster()](#getMaster--) | ID del maestro si esta ventana muestra un maestro. |
| [getPage()](#getPage--) | ID de la página si esta ventana muestra una página. |
| [getParentWindow()](#getParentWindow--) | ID de la ventana en la que se contiene esta ventana de stencil. |
| [getReadOnly()](#getReadOnly--) | Indicador de solo lectura si este stencil no es un stencil de documento. |
| [getSheet()](#getSheet--) | ID de la hoja en el contenedor. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Especifica si los puntos de conexión se muestran en una ventana. |
| [getShowGrid()](#getShowGrid--) | Especifica si se muestra una cuadrícula en la ventana de dibujo. |
| [getShowGuides()](#getShowGuides--) | Especifica si se muestran guías en la ventana de dibujo. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Especifica si se muestran saltos de página en una ventana. |
| [getShowRulers()](#getShowRulers--) | Especifica si se muestran reglas en la ventana de dibujo. |
| [getSnapAngles()](#getSnapAngles--) | Contiene una colección de elementos SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Especifica si una configuración específica de extensión de ajuste está habilitada o deshabilitada para la ventana activa. |
| [getSnapSettings()](#getSnapSettings--) | Especifica los objetos a los que las formas se ajustan cuando el ajuste está activo en la ventana. |
| [getStencilGroup()](#getStencilGroup--) | Especifica el grupo de ventanas de stencil combinadas del cual la ventana es miembro. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Contiene un entero que especifica la posición relativa de un stencil dentro de un grupo en una ventana. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Especifica el ancho del control de pestaña de página de una ventana de dibujo (como una fracción del ancho total de la ventana de dibujo). |
| [getViewCenterX()](#getViewCenterX--) | Doble opcional. |
| [getViewCenterY()](#getViewCenterY--) | Doble opcional. |
| [getViewScale()](#getViewScale--) | Doble opcional. |
| [getWindowHeight()](#getWindowHeight--) | Altura del rectángulo de la ventana. |
| [getWindowLeft()](#getWindowLeft--) | Coordenada izquierda del rectángulo de la ventana. |
| [getWindowState()](#getWindowState--) | Este atributo puede ser una suma de los siguientes valores. |
| [getWindowTop()](#getWindowTop--) | Coordenada superior del rectángulo de la ventana. |
| [getWindowType()](#getWindowType--) | Un valor enumerado que puede ser uno de los siguientes: Drawing, Sheet, Stencil o Icon. Un elemento Window con WindowType='Stencil' debe aparecer después de su ventana de dibujo padre (WindowType='Drawing') y antes de cualquier otro elemento de ventana de dibujo. |
| [getWindowWidth()](#getWindowWidth--) | Ancho del rectángulo de la ventana. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Para la descripción de esta propiedad, consulte [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Para la descripción de esta propiedad, consulte [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Para la descripción de esta propiedad, consulte [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Para la descripción de esta propiedad, consulte [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Para la descripción de esta propiedad, consulte [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Para la descripción de esta propiedad, consulte [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Para la descripción de esta propiedad, consulte [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Para la descripción de esta propiedad, consulte [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Para la descripción de esta propiedad, consulte [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Para la descripción de esta propiedad, consulte [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Para la descripción de esta propiedad, consulte [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Para la descripción de esta propiedad, consulte [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Para la descripción de esta propiedad, consulte [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Para la descripción de esta propiedad, consulte [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Para la descripción de esta propiedad, consulte [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Para la descripción de esta propiedad, consulte [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Para la descripción de esta propiedad, consulte [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Para la descripción de esta propiedad, consulte [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Para la descripción de esta propiedad, consulte [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Para la descripción de esta propiedad, consulte [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Para la descripción de esta propiedad, consulte [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Para la descripción de esta propiedad, consulte [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Para la descripción de esta propiedad, consulte [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Para la descripción de esta propiedad, consulte [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Para la descripción de esta propiedad, consulte [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Para la descripción de esta propiedad, consulte [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Para la descripción de esta propiedad, consulte [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Para la descripción de esta propiedad, consulte [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


Constructor.

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
### getContainer() {#getContainer--}
```
public int getContainer()
```


ID del contenedor: Page, Sheet o Master. Sólo relevante y necesario si se especifica ContainerType.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Puede ser uno de los siguientes valores: Document, Page o Master. Solo es relevante cuando WindowType se especifica como Drawing o Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Ruta del archivo del documento mostrado en esta ventana. Este atributo es relevante para ventanas cuyo WindowType está especificado como Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Especifica si la función de cuadrícula dinámica está habilitada para un documento o ventana.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Especifica los objetos a los que se adhieren las formas cuando el pegado está habilitado en el documento.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


ID del maestro si esta ventana muestra un maestro.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


ID de página si esta ventana está mostrando una página. Relevante sólo cuando WindowType está especificado como Drawing y ContainerType está especificado como Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID de la ventana en la que está contenida esta ventana de stencil. Relevante sólo cuando WindowType está especificado como Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Indicador de solo lectura si este stencil no es un stencil de documento.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID de la hoja en el contenedor. Relevante sólo cuando Container está especificado como Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Especifica si los puntos de conexión se muestran en una ventana.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Especifica si se muestra una cuadrícula en la ventana de dibujo.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Especifica si se muestran guías en la ventana de dibujo.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Especifica si se muestran saltos de página en una ventana.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Especifica si se muestran reglas en la ventana de dibujo.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Contiene una colección de elementos SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Especifica si una configuración de extensión de ajuste específica está habilitada o deshabilitada para la ventana activa. El valor puede ser una suma de los valores en la tabla siguiente.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Especifica los objetos a los que los shapes se ajustan cuando el ajuste está activo en la ventana. El valor puede ser una suma de los valores en la tabla siguiente.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Especifica el grupo de ventanas de stencil combinadas del que la ventana es miembro. Este atributo es relevante sólo para elementos Window cuyo atributo WindowType es Stencil, y sólo si la ventana de stencil forma parte de un grupo combinado de ventanas de stencil. Todas las ventanas de stencil que forman parte del mismo grupo combinado tienen el mismo valor del elemento StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Contiene un entero que especifica la posición relativa de un stencil dentro de un grupo en una ventana.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Especifica el ancho del control de pestaña de página de una ventana de dibujo (como una fracción del ancho total de la ventana de dibujo).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Doble opcional.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Doble opcional.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Doble opcional.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Altura del rectángulo de la ventana.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Coordenada izquierda del rectángulo de la ventana.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Este atributo puede ser una suma de los siguientes valores.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Coordenada superior del rectángulo de la ventana.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Un valor enumerado que puede ser uno de los siguientes: Drawing, Sheet, Stencil o Icon. Un elemento Window con WindowType='Stencil' debe aparecer después de su ventana de dibujo padre (WindowType='Drawing') y antes de cualquier otro elemento de ventana de dibujo.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Ancho del rectángulo de la ventana.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


Para la descripción de esta propiedad, consulte [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Para la descripción de esta propiedad, consulte [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Para la descripción de esta propiedad, consulte [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Para la descripción de esta propiedad, consulte [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Para la descripción de esta propiedad, consulte [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Para la descripción de esta propiedad, consulte [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Para la descripción de esta propiedad, consulte [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Para la descripción de esta propiedad, consulte [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Para la descripción de esta propiedad, consulte [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Para la descripción de esta propiedad, consulte [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Para la descripción de esta propiedad, consulte [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Para la descripción de esta propiedad, consulte [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Para la descripción de esta propiedad, consulte [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Para la descripción de esta propiedad, consulte [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Para la descripción de esta propiedad, consulte [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Para la descripción de esta propiedad, consulte [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Para la descripción de esta propiedad, consulte [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Para la descripción de esta propiedad, consulte [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Para la descripción de esta propiedad, consulte [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Para la descripción de esta propiedad, consulte [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Para la descripción de esta propiedad, consulte [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Para la descripción de esta propiedad, consulte [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Para la descripción de esta propiedad, consulte [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Para la descripción de esta propiedad, consulte [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Para la descripción de esta propiedad, consulte [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Para la descripción de esta propiedad, consulte [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Para la descripción de esta propiedad, consulte [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Para la descripción de esta propiedad, consulte [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Para la descripción de esta propiedad, consulte [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

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

