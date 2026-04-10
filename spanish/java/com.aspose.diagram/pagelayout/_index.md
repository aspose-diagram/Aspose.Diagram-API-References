---
title: PageLayout
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene celdas que controlan la configuración del diseño de página para formas y conectores, como el espaciado entre todas las formas en la página, el espaciado entre todos los conectores en la página y el estilo de enrutamiento para todos los conectores en la página.
type: docs
weight: 263
url: /es/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Contiene celdas que controlan la configuración del diseño de página para formas y conectores, como el espaciado entre todas las formas en la página, el espaciado entre todos los conectores en la página y el estilo de enrutamiento para todos los conectores en la página.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Determina la cantidad de espacio vertical entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Determina la cantidad de espacio vertical entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Especifica cómo se colocan las formas en la página cuando se disponen y el usuario selecciona Organizar Formas (menú Forma). |
| [getBlockSizeX()](#getBlockSizeX--) | Determina el tamaño del bloque vertical, el área en la que cada una de sus formas debe encajar en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo. |
| [getBlockSizeY()](#getBlockSizeY--) | Determina la cantidad de espacio horizontal entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Determina cuál forma es la principal al usar formas mediante manejadores de control. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDynamicsOff()](#getDynamicsOff--) | Especifica si las formas colocables se mueven y los conectores se redirigen alrededor de otras formas y conectores en la página de dibujo. |
| [getEnableGrid()](#getEnableGrid--) | Especifica si Microsoft Visio organiza las formas basándose en una cuadrícula interna de página cuando el usuario selecciona Organizar Formas (menú Forma). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Especifica qué conectores dinámicos separar si se enrutan uno sobre otro. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Especifica qué conectores dinámicos alinear uno sobre otro si se enrutan sobre sí mismos. |
| [getLineJumpCode()](#getLineJumpCode--) | Especifica el estilo de salto de línea para todos los conectores en la página de dibujo que no tienen un estilo de salto de línea local. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Especifica el tamaño de los saltos de línea en los segmentos horizontales de los conectores dinámicos en la página, como un porcentaje del valor del elemento LineToLineX (que especifica el espacio horizontal entre todos los conectores en la página de dibujo). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Especifica el tamaño de los saltos de línea en los segmentos verticales de los conectores dinámicos en la página, como un porcentaje del valor del elemento LineToLineY (que especifica el espacio vertical entre todos los conectores en la página de dibujo). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Especifica la dirección de los saltos de línea en los segmentos horizontales de conectores dinámicos en la página de dibujo para los que no has aplicado una dirección de salto local. |
| [getLineRouteExt()](#getLineRouteExt--) | Especifica la apariencia predeterminada para todos los conectores en una página. |
| [getLineToLineX()](#getLineToLineX--) | Especifica el espacio horizontal mínimo entre conectores dinámicos en la página de dibujo. |
| [getLineToLineY()](#getLineToLineY--) | Especifica el espacio vertical mínimo entre conectores dinámicos en la página de dibujo. |
| [getLineToNodeX()](#getLineToNodeX--) | Especifica el espacio vertical mínimo entre conectores dinámicos y formas en la página de dibujo. |
| [getLineToNodeY()](#getLineToNodeY--) | Determina el tamaño del bloque horizontal, el área en la que cada una de sus formas debe encajar en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Especifica la dirección de los saltos de línea en los conectores dinámicos verticales en la página de dibujo para los que no has aplicado una dirección de salto local. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Especifica el espacio horizontal mínimo entre conectores dinámicos y formas en la página de dibujo. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Indica si las formas en la página pueden dividirse automáticamente. |
| [getPlaceDepth()](#getPlaceDepth--) | Especifica si las formas colocables se alejan cuando el usuario arrastra una forma colocable cerca de otra forma colocable en la página de dibujo. |
| [getPlaceFlip()](#getPlaceFlip--) | Especifica cómo las formas colocables se voltean y/o rotan en una página cuando las formas se disponen usando el comando Organizar Formas en Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Especifica el estilo y la dirección de enrutamiento para todos los conectores dinámicos en la página de dibujo que no tienen un estilo de enrutamiento local. |
| [getPlowCode()](#getPlowCode--) | Determina los conectores dinámicos a los que desea agregar saltos. |
| [getResizePage()](#getResizePage--) | Especifica si se debe ampliar la página para encerrar el dibujo después de que el usuario seleccione Organizar Formas (menú Formas). |
| [getRouteStyle()](#getRouteStyle--) | Para un dibujo que se dispone automáticamente, especifica el método mediante el cual se analiza el dibujo antes de crear el diseño y determina el tipo de diseño. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Determina la cantidad de espacio vertical entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Determina la cantidad de espacio vertical entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Especifica cómo se colocan las formas en la página cuando se disponen y el usuario selecciona Organizar Formas (menú Forma).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Determina el tamaño del bloque vertical, el área en la que cada una de sus formas debe encajar en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Determina la cantidad de espacio horizontal entre formas en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Determina cuál forma es la principal al usar formas mediante manejadores de control. Este elemento establece el comportamiento de todas las formas en la página de dibujo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Especifica si las formas colocables se mueven y los conectores se redirigen alrededor de otras formas y conectores en la página de dibujo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Especifica si Microsoft Visio organiza las formas basándose en una cuadrícula interna de página cuando el usuario selecciona Organizar Formas (menú Forma).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Especifica qué conectores dinámicos separar si se enrutan uno sobre otro.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Especifica qué conectores dinámicos alinear uno sobre otro si se enrutan sobre sí mismos.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Especifica el estilo de salto de línea para todos los conectores en la página de dibujo que no tienen un estilo de salto de línea local.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Especifica el tamaño de los saltos de línea en los segmentos horizontales de los conectores dinámicos en la página, como un porcentaje del valor del elemento LineToLineX (que especifica el espacio horizontal entre todos los conectores en la página de dibujo). El valor de este elemento varía de 0 a 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Especifica el tamaño de los saltos de línea en los segmentos verticales de los conectores dinámicos en la página, como un porcentaje del valor del elemento LineToLineY (que especifica el espacio vertical entre todos los conectores en la página de dibujo). Este elemento puede contener un valor de 0 a 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Especifica la dirección de los saltos de línea en los segmentos horizontales de conectores dinámicos en la página de dibujo para los que no has aplicado una dirección de salto local.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Especifica la apariencia predeterminada para todos los conectores en una página.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Especifica el espacio horizontal mínimo entre conectores dinámicos en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Especifica el espacio vertical mínimo entre conectores dinámicos en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Especifica el espacio vertical mínimo entre conectores dinámicos y formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Determina el tamaño del bloque horizontal, el área en la que cada una de sus formas debe encajar en la página de dibujo cuando utiliza Microsoft Visio para organizar las formas en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Especifica la dirección de los saltos de línea en los conectores dinámicos verticales en la página de dibujo para los que no has aplicado una dirección de salto local.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Especifica el espacio horizontal mínimo entre conectores dinámicos y formas en la página de dibujo.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Indica si las formas en la página pueden dividirse automáticamente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Especifica si las formas colocables se alejan cuando el usuario arrastra una forma colocable cerca de otra forma colocable en la página de dibujo.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Especifica cómo las formas colocables se voltean y/o rotan en una página cuando las formas se disponen usando el comando Lay Out Shapes en Microsoft Visio. Se permiten los siguientes valores hexadecimales.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Especifica el estilo y la dirección de enrutamiento para todos los conectores dinámicos en la página de dibujo que no tienen un estilo de enrutamiento local.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Determina los conectores dinámicos a los que desea agregar saltos.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Especifica si se debe ampliar la página para encerrar el dibujo después de que el usuario seleccione Organizar Formas (menú Formas).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Para un dibujo que se dispone automáticamente, especifica el método mediante el cual se analiza el dibujo antes de crear el diseño y determina el tipo de diseño.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

