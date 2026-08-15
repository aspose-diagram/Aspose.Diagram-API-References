---
title: InterpolationMode
second_title: Référence API d'Aspose.Diagram pour Java
description: L'énumération InterpolationMode spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées.
type: docs
weight: 206
url: /fr/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

L'énumération InterpolationMode spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées.
## Champs

| Champ | Description |
| --- | --- |
| [BICUBIC](#BICUBIC) | Spécifie une interpolation bicubique. |
| [BILINEAR](#BILINEAR) | Spécifie une interpolation bilinéaire. |
| [DEFAULT](#DEFAULT) | Spécifie le mode par défaut. |
| [HIGH](#HIGH) | Spécifie une interpolation de haute qualité. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Spécifie une interpolation bicubique de haute qualité. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Spécifie une interpolation bilinéaire de haute qualité. |
| [INVALID](#INVALID) | Équivalent à l'élément Invalid de l'énumération QualityMode. |
| [LOW](#LOW) | Spécifie une interpolation de basse qualité. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Spécifie une interpolation du plus proche voisin. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


Spécifie une interpolation bicubique. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 25 % de sa taille originale.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Spécifie une interpolation bilinéaire. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image en dessous de 50 % de sa taille originale.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Spécifie le mode par défaut.

### HIGH {#HIGH}
```
public static final int HIGH
```


Spécifie une interpolation de haute qualité.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Spécifie une interpolation bicubique de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité. Ce mode produit les images transformées de la plus haute qualité.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Spécifie une interpolation bilinéaire de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité.

### INVALID {#INVALID}
```
public static final int INVALID
```


Équivalent à l'élément Invalid de l'énumération QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Spécifie une interpolation de basse qualité.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Spécifie une interpolation du plus proche voisin.

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

