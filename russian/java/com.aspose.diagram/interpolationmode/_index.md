---
title: InterpolationMode
second_title: Справочник API Aspose.Diagram for Java
description: Перечисление InterpolationMode указывает алгоритм, используемый при масштабировании или вращении изображений.
type: docs
weight: 206
url: /ru/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

Перечисление InterpolationMode указывает алгоритм, используемый при масштабировании или вращении изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [BICUBIC](#BICUBIC) | Указывает бикубическую интерполяцию. |
| [BILINEAR](#BILINEAR) | Указывает билинейную интерполяцию. |
| [DEFAULT](#DEFAULT) | Указывает режим по умолчанию. |
| [HIGH](#HIGH) | Указывает интерполяцию высокого качества. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Указывает высококачественную бикубическую интерполяцию. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Указывает высококачественную билинейную интерполяцию. |
| [INVALID](#INVALID) | Эквивалентно элементу Invalid перечисления QualityMode. |
| [LOW](#LOW) | Указывает интерполяцию низкого качества. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Указывает интерполяцию ближайшего соседа. |
## Методы

| Метод | Описание |
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


Указывает бикубическую интерполяцию. Предфильтрация не выполняется. Этот режим не подходит для уменьшения изображения ниже 25 % от его исходного размера.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Указывает билинейную интерполяцию. Предфильтрация не выполняется. Этот режим не подходит для уменьшения изображения ниже 50 % от его исходного размера.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Указывает режим по умолчанию.

### HIGH {#HIGH}
```
public static final int HIGH
```


Указывает интерполяцию высокого качества.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Указывает высококачественную бикубическую интерполяцию. Выполняется предфильтрация для обеспечения высококачественного уменьшения. Этот режим обеспечивает наивысшее качество преобразованных изображений.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Указывает высококачественную билинейную интерполяцию. Выполняется предфильтрация для обеспечения высококачественного уменьшения.

### INVALID {#INVALID}
```
public static final int INVALID
```


Эквивалентно элементу Invalid перечисления QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Указывает интерполяцию низкого качества.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Указывает интерполяцию ближайшего соседа.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

