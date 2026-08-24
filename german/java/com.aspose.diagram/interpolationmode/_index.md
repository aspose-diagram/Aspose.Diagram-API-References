---
title: InterpolationMode
second_title: Aspose.Diagram for Java API-Referenz
description: Die Aufzählung InterpolationMode gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.
type: docs
weight: 206
url: /de/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

Die Aufzählung InterpolationMode gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BICUBIC](#BICUBIC) | Gibt bikubische Interpolation an. |
| [BILINEAR](#BILINEAR) | Gibt bilineare Interpolation an. |
| [DEFAULT](#DEFAULT) | Gibt den Standardmodus an. |
| [HIGH](#HIGH) | Gibt hochqualitative Interpolation an. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Gibt hochqualitative, bikubische Interpolation an. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Gibt hochqualitative, bilineare Interpolation an. |
| [INVALID](#INVALID) | Entspricht dem Invalid-Element der QualityMode-Aufzählung. |
| [LOW](#LOW) | Gibt niedrige Qualitätsinterpolation an. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Gibt nächstnachbar-Interpolation an. |
## Methoden

| Methode | Beschreibung |
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


Gibt bikubische Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 25 % seiner Originalgröße zu verkleinern.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Gibt bilineare Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 50 % seiner Originalgröße zu verkleinern.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Gibt den Standardmodus an.

### HIGH {#HIGH}
```
public static final int HIGH
```


Gibt hochqualitative Interpolation an.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Gibt hochqualitative, bikubische Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten. Dieser Modus erzeugt die qualitativ hochwertigsten transformierten Bilder.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Gibt hochqualitative, bilineare Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten.

### INVALID {#INVALID}
```
public static final int INVALID
```


Entspricht dem Invalid-Element der QualityMode-Aufzählung.

### LOW {#LOW}
```
public static final int LOW
```


Gibt niedrige Qualitätsinterpolation an.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Gibt nächstnachbar-Interpolation an.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

