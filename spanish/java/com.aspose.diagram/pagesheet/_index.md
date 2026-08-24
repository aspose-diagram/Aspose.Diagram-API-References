---
title: PageSheet
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que definen la hoja de página para un elemento Página o Maestro.
type: docs
weight: 270
url: /es/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Contiene elementos que definen la hoja de página para un elemento Página o Maestro.
## Métodos

| Método | Descripción |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Copia la pagesheet de un objeto fuente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Contiene una colección de elementos Act. |
| [getAnnotations()](#getAnnotations--) | Contiene elementos que incluyen información sobre los comentarios insertados en una página del documento. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contiene una colección de elementos ConnectionABCD. |
| [getConnections()](#getConnections--) | Contiene una colección de elementos Connection. |
| [getFillStyle()](#getFillStyle--) | Elemento StyleSheet del cual PageSheet hereda el formato de relleno. |
| [getForeign()](#getForeign--) | Contiene elementos que especifican el ancho y la altura de un objeto de otro programa utilizado en un documento de Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE. |
| [getHyperlinks()](#getHyperlinks--) | Contiene una colección de elementos Hyperlink. |
| [getLayers()](#getLayers--) | Contiene una colección de elementos Layer. |
| [getLineStyle()](#getLineStyle--) | Elemento StyleSheet del cual PageSheet hereda el formato de línea. |
| [getPageLayout()](#getPageLayout--) | Contiene Diagram que controla la configuración de diseño de página para formas y conectores, como el espaciado entre todas las formas en la página, el espaciado entre todos los conectores en la página y el estilo de enrutamiento para todos los conectores en la página. |
| [getPageProps()](#getPageProps--) | Contiene Diagram que controla los atributos de la página, como el ancho, la altura y la escala. |
| [getPrintProps()](#getPrintProps--) | Contiene elementos que controlan cómo se formatea (aparece) la página de dibujo en la página de la impresora. |
| [getProps()](#getProps--) | Contiene una colección de elementos Prop. |
| [getRulerGrid()](#getRulerGrid--) | Contiene elementos que especifican la configuración de las reglas y la cuadrícula de la página. |
| [getScratchs()](#getScratchs--) | Contiene una colección de elementos Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contiene una colección de elementos SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Elemento StyleSheet del cual PageSheet hereda el formato de texto. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identificador único global) para el elemento. |
| [getUsers()](#getUsers--) | Contiene una colección de elementos User. |
| [getXForm()](#getXForm--) | Contiene elementos que especifican información general de posicionamiento sobre una forma. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getFillStyle()](../../com.aspose.diagram/pagesheet\\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getLineStyle()](../../com.aspose.diagram/pagesheet\\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Copia la pagesheet de un objeto fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | hoja de página de origen. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contiene una colección de elementos Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Contiene elementos que incluyen información sobre los comentarios insertados en una página del documento.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Contiene una colección de elementos ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contiene una colección de elementos Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Elemento StyleSheet del cual PageSheet hereda el formato de relleno.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contiene elementos que especifican el ancho y la altura de un objeto de otro programa utilizado en un documento Microsoft Visio. También incluye elementos que especifican la distancia a la que la imagen del objeto se desplaza dentro de sus bordes.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contiene una colección de elementos Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Contiene una colección de elementos Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Elemento StyleSheet del cual PageSheet hereda el formato de línea.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Contiene Diagram que controla la configuración de diseño de página para formas y conectores, como el espaciado entre todas las formas en la página, el espaciado entre todos los conectores en la página y el estilo de enrutamiento para todos los conectores en la página.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Contiene Diagram que controla los atributos de la página, como el ancho, la altura y la escala.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Contiene elementos que controlan cómo se formatea (aparece) la página de dibujo en la página de la impresora.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contiene una colección de elementos Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Contiene elementos que especifican la configuración de las reglas y la cuadrícula de la página.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contiene una colección de elementos Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contiene una colección de elementos SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Elemento StyleSheet del cual PageSheet hereda el formato de texto.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identificador único global) para el elemento.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contiene una colección de elementos User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Contiene elementos que especifican información general de posicionamiento sobre una forma.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getFillStyle()](../../com.aspose.diagram/pagesheet\\#getFillStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getLineStyle()](../../com.aspose.diagram/pagesheet\\#getLineStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

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

