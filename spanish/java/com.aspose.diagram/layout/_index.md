---
title: Diseño
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que controlan la colocación de formas y la configuración de enrutamiento de conectores.
type: docs
weight: 215
url: /es/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Contiene elementos que controlan la colocación de formas y la configuración de enrutamiento de conectores.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Determina cuándo se redirige un conector. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Determina si un conector salta cuando dos conectores se cruzan, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Determina la dirección del salto de línea para saltos de línea que ocurren en un segmento horizontal de un conector dinámico. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Determina la dirección del salto de línea para saltos de línea que ocurren en un segmento vertical de un conector dinámico. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Determina el estilo de salto de línea para saltos de línea en un conector dinámico. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Determina la apariencia de un conector. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDisplayLevel()](#getDisplayLevel--) | Determina la banda de nivel de visualización (el rango relativo de agrupación por orden Z) para la forma. |
| [getRelationships()](#getRelationships--) | Almacena las relaciones entre contenedores, listas, anotaciones y formas. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Especifica el comportamiento de colocación para una forma colocable. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Especifica si las formas colocables pueden situarse encima de una forma cuando el usuario selecciona Organizar Formas (menú Formas). |
| [getShapePermeableX()](#getShapePermeableX--) | Especifica si un conector puede enrutar horizontalmente a través de una forma. |
| [getShapePermeableY()](#getShapePermeableY--) | Especifica si un conector puede enrutar verticalmente a través de una forma. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Especifica cómo una forma colocable se voltea y/o rota en la página cuando un usuario selecciona Lay Out Shapes (menú Shapes). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Determina el estilo de colocación para los hijos. |
| [getShapePlowCode()](#getShapePlowCode--) | Especifica si una forma colocable se aleja cuando arrastras otra forma colocable cerca de la forma en la página de dibujo. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Especifica el estilo de enrutamiento y la dirección para un conector en la página de dibujo. |
| [getShapeSplit()](#getShapeSplit--) | Determina si esta forma puede dividir formas que son divisibles. |
| [getShapeSplittable()](#getShapeSplittable--) | Determina si esta forma 1-D puede dividirse. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Para la descripción de esta propiedad, consulte [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Determina cuándo se redirige un conector.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Determina si un conector salta cuando dos conectores se cruzan,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Determina la dirección del salto de línea para saltos de línea que ocurren en un segmento horizontal de un conector dinámico.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Determina la dirección del salto de línea para saltos de línea que ocurren en un segmento vertical de un conector dinámico.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Determina el estilo de salto de línea para saltos de línea en un conector dinámico.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Determina la apariencia de un conector.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Determina la banda de nivel de visualización (el rango relativo de agrupación por orden Z) para la forma.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Almacena las relaciones entre contenedores, listas, anotaciones y formas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Especifica el comportamiento de colocación para una forma colocable.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Especifica si las formas colocables pueden situarse encima de una forma cuando el usuario selecciona Organizar Formas (menú Formas).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Especifica si un conector puede enrutar horizontalmente a través de una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Especifica si un conector puede enrutar verticalmente a través de una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Especifica cómo una forma colocable se voltea y/o rota en la página cuando un usuario selecciona Lay Out Shapes (menú Shapes).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Determina el estilo de colocación para los hijos.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Especifica si una forma colocable se aleja cuando arrastras otra forma colocable cerca de la forma en la página de dibujo.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Especifica el estilo de enrutamiento y la dirección para un conector en la página de dibujo.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Determina si esta forma puede dividir formas que son divisibles.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Determina si esta forma 1-D puede dividirse.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Para la descripción de esta propiedad, consulte [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

