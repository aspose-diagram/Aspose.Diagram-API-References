---
title: Protección
second_title: Referencia de API de Aspose.Diagram para Java
description: El bloqueo ayuda a prevenir cambios inadvertidos en la forma, pero no impide que Microsoft Visio restablezca valores en otras circunstancias.
type: docs
weight: 312
url: /es/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

El bloqueo ayuda a evitar cambios inadvertidos en la forma, pero no impide que Microsoft Visio restablezca valores en otras circunstancias. Tampoco protege contra cambios realizados en la ventana ShapeSheet.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getLockAspect()](#getLockAspect--) | Especifica si la relación de aspecto de la forma está bloqueada. |
| [getLockBegin()](#getLockBegin--) | Especifica si el punto inicial de una forma 1-D está bloqueado en una ubicación específica. |
| [getLockCalcWH()](#getLockCalcWH--) | Especifica si el rectángulo de selección de una forma está bloqueado de modo que no pueda recalcularse cuando se edita un vértice o se cambia el tipo de elemento en el elemento Geom. |
| [getLockCrop()](#getLockCrop--) | Especifica si un objeto externo está bloqueado contra ser recortado con la herramienta Recortar en Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Determina si el usuario puede agregar, eliminar o modificar propiedades personalizadas en la interfaz de usuario (UI) mediante el cuadro de diálogo Definir propiedades personalizadas. |
| [getLockDelete()](#getLockDelete--) | Especifica si una forma está bloqueada contra ser eliminada. |
| [getLockEnd()](#getLockEnd--) | Especifica si el punto final de una forma 1-D está bloqueado en una ubicación específica. |
| [getLockFormat()](#getLockFormat--) | Especifica si el formato de una forma está bloqueado de modo que no pueda cambiarse. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Permite que una subforma bloquee los cambios de formato que se aplican a una forma de grupo principal en la interfaz de usuario de Visio y que de otro modo se propagarían a las formas de grupo individuales. |
| [getLockGroup()](#getLockGroup--) | Especifica si un grupo está bloqueado de modo que no pueda desagruparse. |
| [getLockHeight()](#getLockHeight--) | Especifica si la altura de la forma está bloqueada. |
| [getLockMoveX()](#getLockMoveX--) | Especifica si la posición horizontal de la forma está bloqueada de modo que no pueda moverse horizontalmente. |
| [getLockMoveY()](#getLockMoveY--) | Especifica si la posición vertical de la forma está bloqueada de modo que no pueda moverse verticalmente. |
| [getLockRotate()](#getLockRotate--) | Especifica si la forma está bloqueada contra ser rotada con la herramienta Rotación o los comandos Rotar a la izquierda o Rotar a la derecha en Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Especifica si el rectángulo de selección de una forma está bloqueado de modo que no pueda recalcularse cuando se edita un vértice o se cambia el tipo de elemento en el elemento Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Especifica si el texto de una forma está bloqueado de modo que no pueda editarse. |
| [getLockThemeColors()](#getLockThemeColors--) | Impide que los usuarios apliquen colores de tema a la forma. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Impide que los usuarios apliquen efectos de tema a la forma. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Especifica si los vértices de una forma están bloqueados de modo que no puedan editarse con ninguna herramienta de la barra de herramientas. |
| [getLockWidth()](#getLockWidth--) | Especifica si el ancho de la forma está bloqueado de modo que permanezca sin cambios cuando se redimensiona la forma. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Especifica si la relación de aspecto de la forma está bloqueada. Si está bloqueada, la forma solo puede dimensionarse proporcionalmente; no puede dimensionarse en una sola dimensión.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Especifica si el punto inicial de una forma 1-D está bloqueado en una ubicación específica.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Especifica si el rectángulo de selección de una forma está bloqueado de modo que no pueda recalcularse cuando se edita un vértice o se cambia el tipo de elemento en el elemento Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Especifica si un objeto externo está bloqueado contra ser recortado con la herramienta Recortar en Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Determina si el usuario puede agregar, eliminar o modificar propiedades personalizadas en la interfaz de usuario (UI) mediante el cuadro de diálogo Definir propiedades personalizadas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Especifica si una forma está bloqueada contra ser eliminada.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Especifica si el punto final de una forma 1-D está bloqueado en una ubicación específica.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Especifica si el formato de una forma está bloqueado de modo que no pueda cambiarse. Específicamente, este elemento protege contra la modificación del formato de texto, línea y relleno, o contra el cambio del elemento Style del que hereda la forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Permite que una subforma bloquee los cambios de formato que se aplican a una forma de grupo principal en la interfaz de usuario de Visio y que de otro modo se propagarían a las formas de grupo individuales.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Especifica si un grupo está bloqueado de modo que no pueda desagruparse.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Especifica si la altura de la forma está bloqueada. Si está bloqueada, su altura permanece sin cambios cuando se redimensiona la forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Especifica si la posición horizontal de la forma está bloqueada de modo que no pueda moverse horizontalmente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Especifica si la posición vertical de la forma está bloqueada de modo que no pueda moverse verticalmente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Especifica si la forma está bloqueada contra ser rotada con la herramienta Rotación o los comandos Rotar a la izquierda o Rotar a la derecha en Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Especifica si el rectángulo de selección de una forma está bloqueado de modo que no pueda recalcularse cuando se edita un vértice o se cambia el tipo de elemento en el elemento Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Especifica si el texto de una forma está bloqueado de modo que no pueda editarse. Sin embargo, el texto aún puede formatearse aplicando un estilo, usando las opciones de Style en la pestaña Fuente del cuadro de diálogo Texto.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Impide que los usuarios apliquen colores de tema a la forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Impide que los usuarios apliquen efectos de tema a la forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Especifica si los vértices de una forma están bloqueados de modo que no puedan editarse con ninguna herramienta de la barra de herramientas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Especifica si el ancho de la forma está bloqueado de modo que permanezca sin cambios cuando se redimensiona la forma.

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


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

