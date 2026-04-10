---
title: InterpolationMode
second_title: Riferimento API di Aspose.Diagram per Java
description: L'enumerazione InterpolationMode specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate.
type: docs
weight: 206
url: /it/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

L'enumerazione InterpolationMode specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BICUBIC](#BICUBIC) | Specifica l'interpolazione bicubica. |
| [BILINEAR](#BILINEAR) | Specifica l'interpolazione bilineare. |
| [DEFAULT](#DEFAULT) | Specifica la modalità predefinita. |
| [HIGH](#HIGH) | Specifica l'interpolazione ad alta qualità. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Specifica l'interpolazione bicubica ad alta qualità. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Specifica l'interpolazione bilineare ad alta qualità. |
| [INVALID](#INVALID) | Equivalente all'elemento Invalid dell'enumerazione QualityMode. |
| [LOW](#LOW) | Specifica l'interpolazione a bassa qualità. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Specifica l'interpolazione nearest-neighbor. |
## Metodi

| Metodo | Descrizione |
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


Specifica l'interpolazione bicubica. Non viene eseguito alcun prefiltraggio. Questa modalità non è adatta per ridurre un'immagine al di sotto del 25 percento della sua dimensione originale.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Specifica l'interpolazione bilineare. Non viene eseguito alcun prefiltraggio. Questa modalità non è adatta per ridurre un'immagine al di sotto del 50 percento della sua dimensione originale.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Specifica la modalità predefinita.

### HIGH {#HIGH}
```
public static final int HIGH
```


Specifica l'interpolazione ad alta qualità.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Specifica l'interpolazione bicubica ad alta qualità. Viene eseguito il prefiltraggio per garantire una riduzione ad alta qualità. Questa modalità produce le immagini trasformate della massima qualità.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Specifica l'interpolazione bilineare ad alta qualità. Viene eseguito il prefiltraggio per garantire una riduzione ad alta qualità.

### INVALID {#INVALID}
```
public static final int INVALID
```


Equivalente all'elemento Invalid dell'enumerazione QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Specifica l'interpolazione a bassa qualità.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Specifica l'interpolazione nearest-neighbor.

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

