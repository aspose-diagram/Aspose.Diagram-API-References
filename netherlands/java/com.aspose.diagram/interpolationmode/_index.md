---
title: InterpolationMode
second_title: Aspose.Diagram voor Java API-referentie
description: De InterpolationMode-enumeratie specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd.
type: docs
weight: 206
url: /nl/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

De InterpolationMode-enumeratie specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BICUBIC](#BICUBIC) | Specificeert bicubische interpolatie. |
| [BILINEAR](#BILINEAR) | Specificeert bilineaire interpolatie. |
| [DEFAULT](#DEFAULT) | Specificeert de standaardmodus. |
| [HIGH](#HIGH) | Specificeert interpolatie van hoge kwaliteit. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Specificeert hoogkwalitatieve, bicubische interpolatie. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Specificeert hoogkwalitatieve, bilineaire interpolatie. |
| [INVALID](#INVALID) | Gelijk aan het Invalid‑element van de QualityMode‑enumeratie. |
| [LOW](#LOW) | Specificeert interpolatie van lage kwaliteit. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Specificeert nearest-neighbor interpolatie. |
## Methoden

| Methode | Beschrijving |
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


Specificeert bicubische interpolatie. Er wordt geen prefiltering uitgevoerd. Deze modus is niet geschikt om een afbeelding te verkleinen tot minder dan 25 procent van de oorspronkelijke grootte.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Specificeert bilineaire interpolatie. Er wordt geen prefiltering uitgevoerd. Deze modus is niet geschikt om een afbeelding te verkleinen tot minder dan 50 procent van de oorspronkelijke grootte.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Specificeert de standaardmodus.

### HIGH {#HIGH}
```
public static final int HIGH
```


Specificeert interpolatie van hoge kwaliteit.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Specificeert hoogkwalitatieve, bicubische interpolatie. Prefiltering wordt uitgevoerd om verkleining van hoge kwaliteit te garanderen. Deze modus levert de hoogste kwaliteit getransformeerde afbeeldingen.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Specificeert hoogkwalitatieve, bilineaire interpolatie. Prefiltering wordt uitgevoerd om verkleining van hoge kwaliteit te garanderen.

### INVALID {#INVALID}
```
public static final int INVALID
```


Gelijk aan het Invalid‑element van de QualityMode‑enumeratie.

### LOW {#LOW}
```
public static final int LOW
```


Specificeert interpolatie van lage kwaliteit.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Specificeert nearest-neighbor interpolatie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

