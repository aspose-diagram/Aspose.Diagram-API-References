---
title: RelEllipticalArcTo
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que especifican información sobre un arco elíptico. Las coordenadas se especifican como coordenadas relativas.
type: docs
weight: 318
url: /es/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

Contiene elementos que especifican información sobre un arco elíptico. Las coordenadas se especifican como coordenadas relativas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | Crea una instancia de la clase [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | La coordenada x del punto de control del arco. |
| [getB()](#getB--) | La coordenada y del punto de control de un arco. |
| [getC()](#getC--) | El ángulo del eje mayor de un arco relativo al eje x de su elemento padre. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | La proporción del eje mayor de un arco respecto a su eje menor. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getX()](#getX--) | La coordenada x del vértice final de un arco elíptico. |
| [getY()](#getY--) | La coordenada y del vértice final de un arco elíptico. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


Crea una instancia de la clase [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


La coordenada x del punto de control del arco. El punto de control se ubica mejor aproximadamente a mitad de camino entre los vértices inicial y final del arco. De lo contrario, el arco puede crecer a un tamaño extremo para pasar por el punto de control, con resultados impredecibles.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


La coordenada y del punto de control de un arco.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


El ángulo del eje mayor de un arco relativo al eje x de su elemento padre.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


La proporción del eje mayor de un arco respecto a su eje menor. A pesar del significado habitual de estas palabras, el eje mayor no tiene que ser mayor que el eje menor, por lo que esta proporción no tiene que ser mayor que 1. Establecer este elemento a un valor menor o igual a 0 o mayor que 1000 puede producir resultados impredecibles.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


La coordenada x del vértice final de un arco elíptico.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


La coordenada y del vértice final de un arco elíptico.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

