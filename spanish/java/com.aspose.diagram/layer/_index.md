---
title: Layer
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que definen una única capa y sus propiedades para una página.
type: docs
weight: 212
url: /es/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Contiene elementos que definen una única capa y sus propiedades para una página.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Layer()](#Layer--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Especifica si una capa está activa. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | El índice del color en la tabla de colores utilizado para mostrar la capa o un valor RGB que especifica un color personalizado que no está en la tabla de colores (por ejemplo, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Determina el grado de transparencia del color del texto de una capa o forma, de 0 (completamente opaco) a 1 (completamente transparente). |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getGlue()](#getGlue--) | Especifica si las formas pertenecientes a la capa pueden ser pegadas. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getLock()](#getLock--) | Especifica si las formas pertenecientes a la capa están bloqueadas para ser seleccionadas o editadas. |
| [getName()](#getName--) | El elemento Name especifica el nombre de una capa. |
| [getNameUniv()](#getNameUniv--) | Especifica el nombre universal de una capa. |
| [getPrint()](#getPrint--) | Especifica si las formas pertenecientes a la capa se imprimen cuando se imprime el dibujo. |
| [getSnap()](#getSnap--) | Especifica si otras formas pueden ajustarse a las formas asignadas a la capa. |
| [getStatus()](#getStatus--) | Especifica si la capa es una capa válida para un documento. |
| [getVisible()](#getVisible--) | Especifica si las formas pertenecientes a la capa son visibles en la página del dibujo. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Una bandera que indica si el elemento ha sido verificado localmente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Para la descripción de esta propiedad, consulte [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Especifica si una capa está activa. Las formas que no están preasignadas a capas se asignan a la(s) capa(s) activa(s) cuando se sueltan en la página del dibujo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


El índice del color en la tabla de colores utilizado para mostrar la capa o un valor RGB que especifica un color personalizado que no está en la tabla de colores (por ejemplo, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Determina el grado de transparencia del color del texto de una capa o forma, de 0 (completamente opaco) a 1 (completamente transparente).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Especifica si las formas pertenecientes a la capa pueden ser pegadas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Especifica si las formas pertenecientes a la capa están bloqueadas para ser seleccionadas o editadas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


El elemento Name especifica el nombre de una capa.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Especifica el nombre universal de una capa.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Especifica si las formas pertenecientes a la capa se imprimen cuando se imprime el dibujo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Especifica si otras formas pueden ajustarse a las formas asignadas a la capa. Las formas asignadas a la capa pueden ajustarse a otras formas, pero otras formas no pueden ajustarse a ellas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Especifica si la capa es una capa válida para un documento.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Especifica si las formas pertenecientes a la capa son visibles en la página del dibujo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Una bandera que indica si el elemento ha sido verificado localmente. Un valor de 1 indica que el elemento fue verificado localmente.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Para la descripción de esta propiedad, consulte [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

