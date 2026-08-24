---
title: InterpolationMode
second_title: Referencia de API de Aspose.Diagram para Java
description: La enumeración InterpolationMode especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan.
type: docs
weight: 206
url: /es/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

La enumeración InterpolationMode especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan.
## Campos

| Campo | Descripción |
| --- | --- |
| [BICUBIC](#BICUBIC) | Especifica interpolación bicúbica. |
| [BILINEAR](#BILINEAR) | Especifica interpolación bilineal. |
| [DEFAULT](#DEFAULT) | Especifica el modo predeterminado. |
| [HIGH](#HIGH) | Especifica interpolación de alta calidad. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Especifica interpolación bicúbica de alta calidad. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Especifica interpolación bilineal de alta calidad. |
| [INVALID](#INVALID) | Equivalente al elemento Invalid de la enumeración QualityMode. |
| [LOW](#LOW) | Especifica interpolación de baja calidad. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Especifica interpolación del vecino más cercano. |
## Métodos

| Método | Descripción |
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


Especifica interpolación bicúbica. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 25 % de su tamaño original.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Especifica interpolación bilineal. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 50 % de su tamaño original.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Especifica el modo predeterminado.

### HIGH {#HIGH}
```
public static final int HIGH
```


Especifica interpolación de alta calidad.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Especifica interpolación bicúbica de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad. Este modo produce las imágenes transformadas de mayor calidad.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Especifica interpolación bilineal de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad.

### INVALID {#INVALID}
```
public static final int INVALID
```


Equivalente al elemento Invalid de la enumeración QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Especifica interpolación de baja calidad.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Especifica interpolación del vecino más cercano.

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

