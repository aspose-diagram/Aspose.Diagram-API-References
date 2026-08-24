---
title: Изображение
second_title: Справочник API Aspose.Diagram for Java
description: Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения.
type: docs
weight: 196
url: /ru/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Размытие или смягчение растрового изображения. |
| [getBrightness()](#getBrightness--) | Регулирует яркость растрового изображения. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Указывает контраст растрового изображения. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDenoise()](#getDenoise--) | Удаляет шум (пиксели со случайно распределёнными уровнями цвета) из растрового изображения. |
| [getGamma()](#getGamma--) | Регулирует или корректирует интенсивность изображения для конкретного выходного устройства, например монитора или сканера. |
| [getSharpen()](#getSharpen--) | Указывает степень резкости растрового изображения. |
| [getTransparency()](#getTransparency--) | Указывает уровень прозрачности цвета слоя, от 0 (непрозрачный) до 1 (полностью прозрачный). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Размытие или смягчение растрового изображения. Элемент Blur содержит значение от 0 до 1; значение по умолчанию — 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Регулирует яркость растрового изображения. Элемент Brightness содержит значение от 0 до 1; значение по умолчанию — 0,5.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


Указывает контраст растрового изображения. Элемент Contrast содержит значение от 0 до 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Удаляет шум (пиксели со случайно распределёнными уровнями цвета) из растрового изображения.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Регулирует или корректирует интенсивность изображения для конкретного выходного устройства, например монитора или сканера. Значение по умолчанию — 1 (без коррекции).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Указывает степень резкости растрового изображения. Резкость изображения достигается увеличением контраста соседних пикселей.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Указывает уровень прозрачности цвета слоя, от 0 (непрозрачный) до 1 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

