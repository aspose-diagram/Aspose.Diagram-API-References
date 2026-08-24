---
title: Para
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene los elementos de formato de párrafo para el texto de las formas, como sangrías, interlineado, viñetas y alineación horizontal de los párrafos.
type: docs
weight: 274
url: /es/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Contiene los elementos de formato de párrafo para el texto de la forma, como sangrías, interlineado, viñetas y alineación horizontal de los párrafos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Para()](#Para--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Determina el estilo de viñeta. |
| [getBulletFont()](#getBulletFont--) | Representa el número de la fuente utilizada para formatear el texto cuando se especifica una cadena de viñeta personalizada y el valor en el elemento Bullet no es cero. |
| [getBulletFontSize()](#getBulletFontSize--) | Especifica el tamaño de una viñeta. |
| [getBulletStr()](#getBulletStr--) | "Utilizado para crear un estilo de viñeta personalizado. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getFlags()](#getFlags--) | Indica si la dirección del texto es de izquierda a derecha o de derecha a izquierda. |
| [getHorzAlign()](#getHorzAlign--) | Especifica la alineación horizontal del texto en el bloque de texto de la forma. |
| [getIX()](#getIX--) | El índice basado en cero del elemento dentro de su elemento padre. |
| [getIndFirst()](#getIndFirst--) | Especifica la distancia a la que la primera línea de cada párrafo en el bloque de texto de la forma está sangrada desde la sangría izquierda del párrafo. |
| [getIndLeft()](#getIndLeft--) | Especifica la distancia a la que todas las líneas de texto en un párrafo están sangradas desde el margen izquierdo del bloque de texto. |
| [getIndRight()](#getIndRight--) | Especifica la distancia a la que todas las líneas de texto en un párrafo están sangradas desde el margen derecho del bloque de texto. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Especifica si la fuente de viñeta debe localizarse (traducirse a otro idioma). |
| [getSpAfter()](#getSpAfter--) | Especifica la cantidad de espacio insertado después de cada párrafo en el bloque de texto de la forma. |
| [getSpBefore()](#getSpBefore--) | Especifica la cantidad de espacio insertado antes de cada párrafo en el bloque de texto de la forma. |
| [getSpLine()](#getSpLine--) | Especifica la distancia entre una línea de texto y la siguiente, donde el 100 % es la altura de una línea de texto. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Representa la distancia entre la primera línea del párrafo y la viñeta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | Para la descripción de esta propiedad, consulte [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | Para la descripción de esta propiedad, consulte [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | Para la descripción de esta propiedad, consulte [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | Para la descripción de esta propiedad, consulte [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | Para la descripción de esta propiedad, consulte [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | Para la descripción de esta propiedad, consulte [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | Para la descripción de esta propiedad, consulte [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
```


Constructor.

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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Determina el estilo de viñeta.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Representa el número de la fuente utilizada para formatear el texto cuando se especifica una cadena de viñeta personalizada y el valor en el elemento Bullet no es cero.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Especifica el tamaño de una viñeta.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Utilizado para crear un estilo de viñeta personalizado. Introduzca el estilo como una cadena (entre comillas). Por ejemplo, podría introducir la cadena, ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Indica si la dirección del texto es de izquierda a derecha o de derecha a izquierda.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Especifica la alineación horizontal del texto en el bloque de texto de la forma.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


El índice basado en cero del elemento dentro de su elemento padre.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Especifica la distancia a la que la primera línea de cada párrafo en el bloque de texto de la forma está sangrada desde la sangría izquierda del párrafo. Este valor es independiente de la escala del dibujo. Si el dibujo se escala, la sangría de la primera línea permanece igual.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Especifica la distancia a la que todas las líneas de texto en un párrafo están sangradas desde el margen izquierdo del bloque de texto. Este valor es independiente de la escala del dibujo. Si el dibujo se escala, la sangría izquierda permanece igual.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Especifica la distancia a la que todas las líneas de texto en un párrafo están sangradas desde el margen derecho del bloque de texto. Este valor es independiente de la escala del dibujo. Si el dibujo se escala, la sangría derecha permanece igual.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Especifica si la fuente de viñeta debe localizarse (traducirse a otro idioma).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Especifica la cantidad de espacio insertado después de cada párrafo en el bloque de texto de la forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Especifica la cantidad de espacio insertado antes de cada párrafo en el bloque de texto de la forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Especifica la distancia entre una línea de texto y la siguiente, donde el 100 % es la altura de una línea de texto.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Representa la distancia entre la primera línea del párrafo y la viñeta.

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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


Para la descripción de esta propiedad, consulte [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


Para la descripción de esta propiedad, consulte [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


Para la descripción de esta propiedad, consulte [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


Para la descripción de esta propiedad, consulte [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


Para la descripción de esta propiedad, consulte [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Para la descripción de esta propiedad, consulte [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


Para la descripción de esta propiedad, consulte [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


Para la descripción de esta propiedad, consulte [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

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

