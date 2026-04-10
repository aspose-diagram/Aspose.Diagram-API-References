---
title: Licence
second_title: Référence API d'Aspose.Diagram pour Java
description: Fournit des méthodes pour licencier le composant.
type: docs
weight: 219
url: /fr/java/com.aspose.diagram/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licence le composant. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licence le composant. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initialise une nouvelle instance de cette classe.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licence le composant.

Utilisez cette méthode pour charger une licence à partir d'un flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un flux qui contient la licence. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licence le composant.

Essaie de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier de l'assembly du composant.

3. Le dossier de l'assembly appelant du client.

4. Le dossier de l'assembly d'entrée.

5. Une ressource intégrée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource intégrée dans l'assembly appelant du client.

2. Le dossier du fichier JAR du composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String |  |

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

