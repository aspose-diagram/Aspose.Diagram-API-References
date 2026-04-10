---
title: Varios
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene varios elementos de formas y grupos, como los que controlan el resaltado de selección y la visibilidad.
type: docs
weight: 247
url: /es/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Contiene varios elementos de formas y grupos, como los que controlan el resaltado de selección y la visibilidad.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Contiene una fórmula de activación generada por Microsoft Visio que determina si mover el punto inicial de una forma 1-D para mantener su conexión con otra forma. |
| [getCalendar()](#getCalendar--) | Determina el calendario que se utiliza para propiedades personalizadas, campos de texto y fórmulas de elementos. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Contiene el texto del comentario en formato de cadena para una forma. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Determina el porcentaje en que se escala una forma cuando se suelta en la página de dibujo. |
| [getDynFeedback()](#getDynFeedback--) | Especifica el tipo de retroalimentación visual que se brinda a los usuarios cuando arrastran un conector. |
| [getEndTrigger()](#getEndTrigger--) | Contiene una fórmula de activación generada por Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Especifica si se permite el pegado dinámico (forma a forma) al conectar con una forma. |
| [getHideText()](#getHideText--) | Oculta el texto de una forma. |
| [getLangID()](#getLangID--) | Indica el ID de configuración regional (LCID) del idioma en el que se ingresó la fórmula de la celda, el texto, la propiedad personalizada o el comentario. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Determina si las formas se localizan (si su elemento LangID se restablece) cuando se copian entre documentos. |
| [getNoAlignBox()](#getNoAlignBox--) | Especifica si se muestra el rectángulo de selección cuando la forma está seleccionada. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Especifica si se muestran los manejadores de control cuando la forma está seleccionada. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Especifica si una forma cambia de tamaño o rota dinámicamente mientras el usuario la manipula. |
| [getNoObjHandles()](#getNoObjHandles--) | Especifica si se muestran los manejadores de selección cuando la forma está seleccionada. |
| [getNonPrinting()](#getNonPrinting--) | Especifica si una forma seleccionada puede imprimirse. |
| [getObjType()](#getObjType--) | Especifica si los objetos son colocables o enrutables en diagramas cuando utilizas Microsoft Visio para organizar formas en la página de dibujo. |
| [getShapeKeywords()](#getShapeKeywords--) | Contiene palabras clave de búsqueda que se han asignado a formas maestras personalizadas. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Especifica si recalcular el rectángulo de selección de una forma cada vez que se mueve un manejador de control. |
| [getWalkPreference()](#getWalkPreference--) | Especifica si un extremo de una forma 1-D se mueve a un punto de conexión horizontal o vertical en la forma a la que está pegada, usando pegado dinámico, cuando la forma se desplaza a una posición ambigua. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Especifica si la forma puede añadirse a un grupo soltándola sobre el grupo. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Indica si los valores de celdas especificadas en una forma maestra sobrescriben los valores (incluidos los locales) de una forma que se está reemplazando durante una operación de sustitución de forma. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Contiene una fórmula de activación generada por Microsoft Visio que determina si mover el punto inicial de una forma 1-D para mantener su conexión con otra forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Determina el calendario que se utiliza para propiedades personalizadas, campos de texto y fórmulas de elementos.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Contiene el texto del comentario en formato de cadena para una forma.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Determina el porcentaje en que se escala una forma cuando se suelta en la página de dibujo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Especifica el tipo de retroalimentación visual que se brinda a los usuarios cuando arrastran un conector.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Contiene una fórmula de activación generada por Microsoft Visio. Esta fórmula de activación determina si mover el punto final de una forma 1-D para mantener su conexión con otra forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Especifica si se permite el pegado dinámico (forma a forma) al conectar con una forma.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Oculta el texto de una forma. Puedes ver el texto, editar propiedades y aplicar estilos al texto en el bloque de texto, aunque los cambios no aparecerán hasta que especifiques el elemento HideText como 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indica el ID de configuración regional (LCID) del idioma en el que se ingresó la fórmula de la celda, el texto, la propiedad personalizada o el comentario.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Determina si las formas se localizan (si su elemento LangID se restablece) cuando se copian entre documentos.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Especifica si se muestra el rectángulo de selección cuando la forma está seleccionada.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Especifica si se muestran los manejadores de control cuando la forma está seleccionada.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Especifica si una forma cambia de tamaño o rota dinámicamente mientras el usuario la manipula.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Especifica si se muestran los manejadores de selección cuando la forma está seleccionada.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Especifica si una forma seleccionada puede imprimirse.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Especifica si los objetos son colocables o enrutables en diagramas cuando utilizas Microsoft Visio para organizar formas en la página de dibujo.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Contiene palabras clave de búsqueda que se han asignado a formas maestras personalizadas.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Especifica si recalcular el rectángulo de selección de una forma cada vez que se mueve un manejador de control.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Especifica si un extremo de una forma 1-D se mueve a un punto de conexión horizontal o vertical en la forma a la que está pegada, usando pegado dinámico, cuando la forma se desplaza a una posición ambigua.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Especifica si la forma puede añadirse a un grupo soltándola sobre el grupo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Indica si los valores de celdas especificadas en una forma maestra sobrescriben los valores (incluidos los locales) de una forma que se está reemplazando durante una operación de sustitución de forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

