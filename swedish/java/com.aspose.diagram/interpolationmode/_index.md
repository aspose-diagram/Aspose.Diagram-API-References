---
title: InterpolationMode
second_title: Aspose.Diagram för Java API-referens
description: InterpolationMode‑enumerationen specificerar den algoritm som används när bilder skalas eller roteras.
type: docs
weight: 206
url: /sv/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

InterpolationMode‑enumerationen specificerar den algoritm som används när bilder skalas eller roteras.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BICUBIC](#BICUBIC) | Anger bikubisk interpolering. |
| [BILINEAR](#BILINEAR) | Anger bilinjär interpolering. |
| [DEFAULT](#DEFAULT) | Anger standardläge. |
| [HIGH](#HIGH) | Anger högkvalitativ interpolering. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Anger högkvalitativ, bikubisk interpolering. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Anger högkvalitativ, bilinjär interpolering. |
| [INVALID](#INVALID) | Motsvarar elementet Invalid i QualityMode‑enumerationen. |
| [LOW](#LOW) | Anger lågkvalitativ interpolering. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Anger närmaste-granne-interpolering. |
## Metoder

| Metod | Beskrivning |
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


Anger bikubisk interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att krympa en bild under 25 procent av dess originalstorlek.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Anger bilinjär interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att krympa en bild under 50 procent av dess originalstorlek.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Anger standardläge.

### HIGH {#HIGH}
```
public static final int HIGH
```


Anger högkvalitativ interpolering.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Anger högkvalitativ, bikubisk interpolering. Förfiltrering utförs för att säkerställa högkvalitativ krympning. Detta läge producerar de högsta kvalitetsförändrade bilderna.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Anger högkvalitativ, bilinjär interpolering. Förfiltrering utförs för att säkerställa högkvalitativ krympning.

### INVALID {#INVALID}
```
public static final int INVALID
```


Motsvarar elementet Invalid i QualityMode‑enumerationen.

### LOW {#LOW}
```
public static final int LOW
```


Anger lågkvalitativ interpolering.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Anger närmaste-granne-interpolering.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

