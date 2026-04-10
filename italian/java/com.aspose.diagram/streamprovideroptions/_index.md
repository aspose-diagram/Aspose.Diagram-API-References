---
title: StreamProviderOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta le opzioni di flusso.
type: docs
weight: 390
url: /it/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

Rappresenta le opzioni di flusso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | Il percorso predefinito (URL) salvato nel file HTML generato per la fonte di riferimento. |
| [getStream()](#getStream--) | Ottiene/Imposta lo stream di output per scrivere i dati salvati |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | Il percorso personalizzato (URL) dell'utente salvato nel file HTML generato per la fonte di riferimento. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | Per la descrizione di questa proprietà, vedere [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
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
| Parametro | Tipo | Descrizione |
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


Il percorso predefinito (URL) salvato nel file HTML generato per la fonte di riferimento. Ad esempio, i dati del foglio salvati in xxx\_files/sheet001.htm, l'URL utilizzato nel file HTML principale dovrebbe essere simile a "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


Ottiene/Imposta lo stream di output per scrivere i dati salvati

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


Il percorso personalizzato (URL) dell'utente salvato nel file HTML generato per la fonte di riferimento. Se non definito dall'utente, verrà utilizzato DefaultPath. Ad esempio, i dati del foglio saranno salvati dall'utente in d:/sheet001.htm, l'URL utilizzato nel file HTML principale dovrebbe essere "d:/sheet001.htm" o un altro percorso relativo valido che possa essere accessibile dal file HTML principale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


Per la descrizione di questa proprietà, vedere [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.OutputStream |  |

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

