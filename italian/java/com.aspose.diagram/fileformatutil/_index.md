---
title: FileFormatUtil
second_title: Riferimento API di Aspose.Diagram per Java
description: Fornisce metodi di utilità per convertire le enumerazioni di formato file in stringhe o estensioni di file e viceversa.
type: docs
weight: 152
url: /it/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

Fornisce metodi di utilità per convertire le enumerazioni di formato file in stringhe o estensioni di file e viceversa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | Rileva e restituisce le informazioni sul formato di un Visio memorizzato in uno stream. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | Rileva e restituisce le informazioni sul formato di un Visio memorizzato in un file. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


Rileva e restituisce le informazioni sul formato di un Visio memorizzato in uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


Rileva e restituisce le informazioni sul formato di un Visio memorizzato in un file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
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

