---
title: InterpolationMode
second_title: Aspose.Diagram for Java API Reference
description: The InterpolationMode enumeration specifies the algorithm that is used when images are scaled or rotated.
type: docs
weight: 210
url: /java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

The InterpolationMode enumeration specifies the algorithm that is used when images are scaled or rotated.
## Fields

| Field | Description |
| --- | --- |
| [BICUBIC](#BICUBIC) | Specifies bicubic interpolation. |
| [BILINEAR](#BILINEAR) | Specifies bilinear interpolation. |
| [DEFAULT](#DEFAULT) | Specifies default mode. |
| [HIGH](#HIGH) | Specifies high quality interpolation. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Specifies high-quality, bicubic interpolation. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Specifies high-quality, bilinear interpolation. |
| [INVALID](#INVALID) | Equivalent to the Invalid element of the QualityMode enumeration. |
| [LOW](#LOW) | Specifies low quality interpolation. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Specifies nearest-neighbor interpolation. |
## Methods

| Method | Description |
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


Specifies bicubic interpolation. No prefiltering is done. This mode is not suitable for shrinking an image below 25 percent of its original size.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Specifies bilinear interpolation. No prefiltering is done. This mode is not suitable for shrinking an image below 50 percent of its original size.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Specifies default mode.

### HIGH {#HIGH}
```
public static final int HIGH
```


Specifies high quality interpolation.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Specifies high-quality, bicubic interpolation. Prefiltering is performed to ensure high-quality shrinking. This mode produces the highest quality transformed images.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Specifies high-quality, bilinear interpolation. Prefiltering is performed to ensure high-quality shrinking.

### INVALID {#INVALID}
```
public static final int INVALID
```


Equivalent to the Invalid element of the QualityMode enumeration.

### LOW {#LOW}
```
public static final int LOW
```


Specifies low quality interpolation.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Specifies nearest-neighbor interpolation.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

