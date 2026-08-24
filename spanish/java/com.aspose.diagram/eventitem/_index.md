---
title: EventItem
second_title: Referencia de API de Aspose.Diagram para Java
description: Encapsula un código de evento.
type: docs
weight: 145
url: /es/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Encapsula un código de evento. Un elemento EventItem puede desencadenar dos tipos de acciones: puede ejecutar un complemento, o puede enviar una notificación del evento al programa que lo llama.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EventItem()](#EventItem--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Especifica el código de acción del elemento EventItem padre. Para que un elemento EventItem se guarde en un archivo DatadiagramML, debe ser persistente. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Representa una bandera que indica si el evento está habilitado o deshabilitado. |
| [getEventCode()](#getEventCode--) | Un código que indica el evento que desencadena el complemento. |
| [getID()](#getID--) | El ID del evento. |
| [getTarget()](#getTarget--) | Especifica el objetivo de un evento. |
| [getTargetArgs()](#getTargetArgs--) | Especifica una cadena que contiene argumentos para ser enviados al objetivo de un evento. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Para la descripción de esta propiedad, consulte [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Para la descripción de esta propiedad, consulte [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Para la descripción de esta propiedad, consulte [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Para la descripción de esta propiedad, consulte [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Para la descripción de esta propiedad, consulte [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


Especifica el código de acción del elemento EventItem padre. Para que un elemento EventItem se guarde en un archivo DatadiagramML, debe ser persistente. Actualmente, el único código de acción válido que puede tener un evento persistente es 1 (ONEVENT\_ACT\_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Representa una bandera que indica si el evento está habilitado o deshabilitado.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Un código que indica el evento que desencadena el complemento. Para obtener más información sobre los códigos de evento, consulte Códigos de Evento en la Referencia de Automatización de Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


El ID del evento.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Especifica el objetivo de un evento.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Especifica una cadena que contiene argumentos para ser enviados al objetivo de un evento.

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


Para la descripción de esta propiedad, consulte [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Para la descripción de esta propiedad, consulte [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Para la descripción de esta propiedad, consulte [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Para la descripción de esta propiedad, consulte [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Para la descripción de esta propiedad, consulte [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

