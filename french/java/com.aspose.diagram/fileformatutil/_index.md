---
title: FileFormatUtil
second_title: Référence API d'Aspose.Diagram pour Java
description: Fournit des méthodes utilitaires pour convertir les énumérations de formats de fichiers en chaînes ou en extensions de fichiers et inversement.
type: docs
weight: 152
url: /fr/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

Fournit des méthodes utilitaires pour convertir les énumérations de formats de fichiers en chaînes ou en extensions de fichiers et inversement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | Détecte et renvoie les informations sur le format d'un visio stocké dans un flux. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | Détecte et renvoie les informations sur le format d'un visio stocké dans un fichier. |
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


Détecte et renvoie les informations sur le format d'un visio stocké dans un flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


Détecte et renvoie les informations sur le format d'un visio stocké dans un fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

