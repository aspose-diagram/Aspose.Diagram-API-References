---
title: StreamProviderOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente les options du flux.
type: docs
weight: 390
url: /fr/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

Représente les options du flux.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | Le chemin par défaut (URL) enregistré dans le fichier HTML généré pour la source référencée. |
| [getStream()](#getStream--) | Obtient/Définit le flux de sortie pour écrire les données enregistrées. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | Le chemin personnalisé (URL) de l'utilisateur enregistré dans le fichier HTML généré pour la source référencée. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | Pour la description de cette propriété, veuillez consulter [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


Le chemin par défaut (URL) enregistré dans le fichier HTML généré pour la source référencée. Par exemple, les données de la feuille enregistrées dans xxx\_files/sheet001.htm, l'URL utilisée dans le fichier HTML principal doit être comme "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


Obtient/Définit le flux de sortie pour écrire les données enregistrées.

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


Le chemin personnalisé (URL) de l'utilisateur enregistré dans le fichier HTML généré pour la source référencée. Si l'utilisateur ne le définit pas, DefaultPath sera utilisé. Par exemple, les données de la feuille seront enregistrées par l'utilisateur dans d:/sheet001.htm, l'URL utilisée dans le fichier HTML principal doit être "d:/sheet001.htm" ou tout autre chemin relatif valide pouvant être accédé par le fichier HTML principal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


Pour la description de cette propriété, veuillez consulter [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.OutputStream |  |

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

