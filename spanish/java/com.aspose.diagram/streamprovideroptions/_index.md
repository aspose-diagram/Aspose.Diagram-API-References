---
title: StreamProviderOptions
second_title: Referencia de API de Aspose.Diagram para Java
description: Representa las opciones de flujo.
type: docs
weight: 390
url: /es/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

Representa las opciones de flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | La ruta predeterminada (URL) guardada en el archivo HTML generado para la fuente referenciada. |
| [getStream()](#getStream--) | Obtiene/Establece el flujo de salida para escribir los datos guardados |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | La ruta personalizada del usuario (URL) guardada en el archivo HTML generado para la fuente referenciada. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | Para la descripción de esta propiedad, consulte [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


La ruta predeterminada (URL) guardada en el archivo HTML generado para la fuente referenciada. Por ejemplo, los datos de la hoja guardados en xxx\_files/sheet001.htm, la URL utilizada en el archivo HTML principal debería ser como "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


Obtiene/Establece el flujo de salida para escribir los datos guardados

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


La ruta personalizada del usuario (URL) guardada en el archivo HTML generado para la fuente referenciada. Si no es definida por el usuario, se utilizará DefaultPath. Por ejemplo, los datos de la hoja serán guardados por el usuario en d:/sheet001.htm, la URL utilizada en el archivo HTML principal debería ser "d:/sheet001.htm" u otra ruta relativa válida que pueda ser accedida por el archivo HTML principal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


Para la descripción de esta propiedad, consulte [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.OutputStream |  |

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

