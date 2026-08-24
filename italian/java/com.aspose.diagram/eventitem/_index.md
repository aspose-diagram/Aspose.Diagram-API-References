---
title: EventItem
second_title: Riferimento API di Aspose.Diagram per Java
description: Incapsula un codice evento.
type: docs
weight: 145
url: /it/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Incapsula un codice evento. Un elemento EventItem può attivare due tipi di azioni: può eseguire un componente aggiuntivo, oppure può inviare una notifica dell'evento al programma chiamante.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EventItem()](#EventItem--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Specifica il codice azione dell'elemento EventItem padre. Perché un elemento EventItem venga salvato in un file DatadiagramML, deve essere persistente. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Rappresenta un flag che indica se l'evento è abilitato o disabilitato. |
| [getEventCode()](#getEventCode--) | Un codice che indica l'evento che attiva il componente aggiuntivo. |
| [getID()](#getID--) | L'ID dell'evento. |
| [getTarget()](#getTarget--) | Specifica la destinazione di un evento. |
| [getTargetArgs()](#getTargetArgs--) | Specifica una stringa contenente gli argomenti da inviare alla destinazione di un evento. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Per la descrizione di questa proprietà, vedere [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Per la descrizione di questa proprietà, vedere [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Per la descrizione di questa proprietà, vedere [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


Costruttore.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public int getAction()
```


Specifica il codice azione dell'elemento EventItem padre. Perché un elemento EventItem venga salvato in un file DatadiagramML, deve essere persistente. Attualmente, l'unico codice azione valido che un evento persistente può avere è 1 (ONEVENT\_ACT\_RUNADDON).

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


Rappresenta un flag che indica se l'evento è abilitato o disabilitato.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Un codice che indica l'evento che attiva il componente aggiuntivo. Per ulteriori informazioni sui codici evento, vedere Codici Evento nella Riferimento di Automazione di Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID dell'evento.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Specifica la destinazione di un evento.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Specifica una stringa contenente gli argomenti da inviare alla destinazione di un evento.

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


Per la descrizione di questa proprietà, vedere [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Per la descrizione di questa proprietà, vedere [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Per la descrizione di questa proprietà, vedere [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Per la descrizione di questa proprietà, vedere [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Per la descrizione di questa proprietà, vedere [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

