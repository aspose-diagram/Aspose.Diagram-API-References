---
title: RadioButtonActiveXControl
second_title: Referencia de API de Aspose.Diagram para Java
description: Representa un control ActiveX RadioButton.
type: docs
weight: 313
url: /es/java/com.aspose.diagram/radiobuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.ToggleButtonActiveXControl](../../com.aspose.diagram/togglebuttonactivexcontrol)
```
public class RadioButtonActiveXControl extends ToggleButtonActiveXControl
```

Representa un control ActiveX RadioButton.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | la tecla de acceso rápido para el control. |
| [getAlignment()](#getAlignment--) | la posición del Caption relativa al control. |
| [getBackOleColor()](#getBackOleColor--) | el color OLE del fondo. |
| [getCaption()](#getCaption--) | el texto descriptivo que aparece en un control. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | los datos binarios del control. |
| [getForeOleColor()](#getForeOleColor--) | el color OLE del primer plano. |
| [getGroupName()](#getGroupName--) | el nombre del grupo. |
| [getHeight()](#getHeight--) | la altura del control en unidades de puntos. |
| [getIMEMode()](#getIMEMode--) | el modo de ejecución predeterminado del Editor de Métodos de Entrada para el control al recibir el foco. |
| [getMouseIcon()](#getMouseIcon--) | un ícono personalizado para mostrar como puntero del mouse del control. |
| [getMousePointer()](#getMousePointer--) | el tipo de ícono que se muestra como puntero del mouse del control. |
| [getPicture()](#getPicture--) | los datos de la imagen. |
| [getPicturePosition()](#getPicturePosition--) | la ubicación de la imagen del control relativa a su leyenda. |
| [getSpecialEffect()](#getSpecialEffect--) | el efecto especial del control. |
| [getType()](#getType--) | Obtiene el tipo del control ActiveX. |
| [getValue()](#getValue--) | Indica si el control está marcado o no. |
| [getWidth()](#getWidth--) | el ancho del control en unidades de punto. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indica si el control cambiará de tamaño automáticamente para mostrar todo su contenido. |
| [isEnabled()](#isEnabled--) | Indica si el control puede recibir el foco y responder a eventos generados por el usuario. |
| [isLocked()](#isLocked--) | Indica si los datos del control están bloqueados para edición. |
| [isTransparent()](#isTransparent--) | Indica si el control es transparente. |
| [isTripleState()](#isTripleState--) | Indica cómo el control especificado mostrará los valores Null. |
| [isWordWrapped()](#isWordWrapped--) | Indica si el contenido del control se ajusta automáticamente al final de una línea. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | Para la descripción de esta propiedad, consulte [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--) |
| [setAlignment(int value)](#setAlignment-int-) | Para la descripción de esta propiedad, consulte [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Para la descripción de esta propiedad, consulte [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Para la descripción de esta propiedad, consulte [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | Para la descripción de esta propiedad, consulte [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Para la descripción de esta propiedad, consulte [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Para la descripción de esta propiedad, consulte [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setGroupName(String value)](#setGroupName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--) |
| [setHeight(double value)](#setHeight-double-) | Para la descripción de esta propiedad, consulte [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Para la descripción de esta propiedad, consulte [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Para la descripción de esta propiedad, consulte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Para la descripción de esta propiedad, consulte [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Para la descripción de esta propiedad, consulte [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Para la descripción de esta propiedad, consulte [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | Para la descripción de esta propiedad, consulte [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Para la descripción de esta propiedad, consulte [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Para la descripción de esta propiedad, consulte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | Para la descripción de esta propiedad, consulte [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | Para la descripción de esta propiedad, consulte [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Para la descripción de esta propiedad, consulte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Para la descripción de esta propiedad, consulte [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--) |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


la tecla de acceso rápido para el control.

**Returns:**
char
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


la posición del Caption relativa al control.

**Returns:**
int
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


el color OLE del fondo.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


el texto descriptivo que aparece en un control.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


los datos binarios del control.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


El color OLE del primer plano. No se aplica al control Image.

**Returns:**
int
### getGroupName() {#getGroupName--}
```
public String getGroupName()
```


el nombre del grupo.

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public double getHeight()
```


la altura del control en unidades de puntos.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


el modo de ejecución predeterminado del Editor de Métodos de Entrada para el control al recibir el foco.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


un ícono personalizado para mostrar como puntero del mouse del control.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


el tipo de ícono que se muestra como puntero del mouse del control.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


los datos de la imagen.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


la ubicación de la imagen del control relativa a su leyenda.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


el efecto especial del control.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Obtiene el tipo del control ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public int getValue()
```


Indica si el control está marcado o no.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


el ancho del control en unidades de punto.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


Indica si el control cambiará de tamaño automáticamente para mostrar todo su contenido.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indica si el control puede recibir el foco y responder a eventos generados por el usuario.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indica si los datos del control están bloqueados para edición.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indica si el control es transparente.

**Returns:**
boolean
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


Indica cómo el control especificado mostrará los valores Null.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Configuración | Descripción                                                                                                                                     |
| True    | El control ciclará a través de los estados para los valores Sí, No y Null. El control aparece atenuado (gris) cuando su propiedad Value está establecida en Null. |
| False   | (Predeterminado) El control ciclará a través de los estados para los valores Sí y No. Los valores Null se muestran como si fueran valores No.                           |

|

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Indica si el contenido del control se ajusta automáticamente al final de una línea.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


Para la descripción de esta propiedad, consulte [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char |  |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Para la descripción de esta propiedad, consulte [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Para la descripción de esta propiedad, consulte [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Para la descripción de esta propiedad, consulte [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Para la descripción de esta propiedad, consulte [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Para la descripción de esta propiedad, consulte [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Para la descripción de esta propiedad, consulte [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGroupName(String value) {#setGroupName-java.lang.String-}
```
public void setGroupName(String value)
```


Para la descripción de esta propiedad, consulte [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Para la descripción de esta propiedad, consulte [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Para la descripción de esta propiedad, consulte [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Para la descripción de esta propiedad, consulte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Para la descripción de esta propiedad, consulte [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Para la descripción de esta propiedad, consulte [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Para la descripción de esta propiedad, consulte [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


Para la descripción de esta propiedad, consulte [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Para la descripción de esta propiedad, consulte [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Para la descripción de esta propiedad, consulte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


Para la descripción de esta propiedad, consulte [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Para la descripción de esta propiedad, consulte [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Para la descripción de esta propiedad, consulte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Para la descripción de esta propiedad, consulte [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

