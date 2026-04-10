---
title: Control
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos para las coordenadas x e y de cada controlador definido para una forma y elementos que especifican la forma en que el controlador debe comportarse.
type: docs
weight: 87
url: /es/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

Contiene elementos para las coordenadas x e y de cada mango de control definido para una forma, y elementos que especifican la forma en que el mango de control debe comportarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Control()](#Control--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [canGlue()](#canGlue--) | Determina si un controlador puede adherirse a otras formas. |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getPrompt()](#getPrompt--) | El elemento de aviso especifica el texto descriptivo que aparece como información sobre herramientas cuando el puntero del ratón se detiene sobre el controlador de una forma. |
| [getX()](#getX--) | La coordenada x que indica la ubicación del controlador de una forma. |
| [getXCon()](#getXCon--) | Especifica el tipo de comportamiento que la coordenada x del controlador muestra después de mover el controlador. |
| [getXDyn()](#getXDyn--) | Especifica la coordenada x del punto de anclaje de un controlador en coordenadas locales. |
| [getY()](#getY--) | La coordenada y que indica la ubicación del controlador de una forma. |
| [getYCon()](#getYCon--) | Especifica el tipo de comportamiento que la coordenada x del controlador muestra después de mover el controlador. |
| [getYDyn()](#getYDyn--) | Especifica la coordenada y del punto de anclaje de un controlador en coordenadas locales. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | Para la descripción de esta propiedad, consulte [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | Para la descripción de esta propiedad, consulte [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | Para la descripción de esta propiedad, consulte [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | Para la descripción de esta propiedad, consulte [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


Constructor.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


Determina si un controlador puede adherirse a otras formas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


El nombre del elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


El nombre universal del elemento.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


El elemento de aviso especifica el texto descriptivo que aparece como información sobre herramientas cuando el puntero del ratón se detiene sobre el controlador de una forma.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


La coordenada x que indica la ubicación del controlador de una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


Especifica el tipo de comportamiento que la coordenada x del controlador muestra después de mover el controlador.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


Especifica la coordenada x del punto de anclaje de un controlador en coordenadas locales. El punto de anclaje se usa para rubber-banding durante la dinámica.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


La coordenada y que indica la ubicación del controlador de una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


Especifica el tipo de comportamiento que la coordenada x del controlador muestra después de mover el controlador.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


Especifica la coordenada y del punto de anclaje de un controlador en coordenadas locales. El punto de anclaje se usa para rubber-banding durante la dinámica.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


Para la descripción de esta propiedad, consulte [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


Para la descripción de esta propiedad, consulte [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


Para la descripción de esta propiedad, consulte [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


Para la descripción de esta propiedad, consulte [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

