---
title: PageProps
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene celdas que controlan los atributos de la página, como el ancho, la altura y la escala de la página.
type: docs
weight: 268
url: /es/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Contiene celdas que controlan los atributos de la página, como el ancho, la altura y la escala de la página.
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Determina si la página de dibujo se redimensiona automáticamente para ajustarse al diagrama. |
| [getDrawingScale()](#getDrawingScale--) | Representa el valor de la unidad de dibujo en la escala de dibujo actual. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Especifica el tipo de escala de dibujo a usar para una página. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Especifica el tamaño de dibujo de una página. |
| [getInhibitSnap()](#getInhibitSnap--) | Especifica si las formas en una página de primer plano se ajustan a otros objetos en la página y a formas en la página de fondo. |
| [getPageHeight()](#getPageHeight--) | Especifica la altura de la página en unidades de dibujo. |
| [getPageScale()](#getPageScale--) | Especifica el valor de la unidad de página predeterminada en la escala de dibujo actual. |
| [getPageWidth()](#getPageWidth--) | Especifica el ancho de la página en unidades de dibujo. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Contiene un número que especifica el ángulo de dirección oblicua cuando se aplica el tipo de sombra de página predeterminado. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Especifica la distancia en unidades de página que la sombra paralela de una forma se desplaza horizontalmente respecto a la forma. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Especifica la distancia en unidades de página que la sombra paralela de una forma se desplaza verticalmente respecto a la forma. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Especifica el porcentaje para ampliar o reducir la sombra de una forma. |
| [getShdwType()](#getShdwType--) | Indica el tipo de sombra predeterminado para una página. |
| [getUIVisibility()](#getUIVisibility--) | Determina si el nombre de la página se muestra en la interfaz de usuario (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, por favor consulta [getDel()](../../com.aspose.diagram/pageprops\\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Determina si la página de dibujo se redimensiona automáticamente para ajustarse al diagrama.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Representa el valor de la unidad de dibujo en la escala de dibujo actual. La escala de dibujo para la página es la proporción de la unidad de página contenida en el elemento PageScale a la unidad de dibujo. Las unidades de este elemento determinan las unidades de longitud predeterminada (DL) para la página.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Especifica el tipo de escala de dibujo a usar para una página.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Especifica el tamaño de dibujo de una página.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Especifica si las formas en una página de primer plano se ajustan a otros objetos en la página y a formas en la página de fondo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Especifica la altura de la página en unidades de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Especifica el valor de la unidad de página predeterminada en la escala de dibujo actual. La escala de dibujo para la página es la proporción de la unidad de página en el elemento PageScale a la unidad de dibujo mostrada en el elemento DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Especifica el ancho de la página en unidades de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Contiene un número que especifica el ángulo de dirección oblicua cuando se aplica el tipo de sombra de página predeterminado.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Especifica la distancia en unidades de página que la sombra paralela de una forma se desplaza horizontalmente respecto a la forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Especifica la distancia en unidades de página que la sombra paralela de una forma se desplaza verticalmente respecto a la forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Especifica el porcentaje para ampliar o reducir la sombra de una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Indica el tipo de sombra predeterminado para una página.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Determina si el nombre de la página se muestra en la interfaz de usuario (UI). Un valor de uno indica que la página no es visible; un valor de cero indica que la página es visible.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Para la descripción de esta propiedad, por favor consulta [getDel()](../../com.aspose.diagram/pageprops\\#getDel--)

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

