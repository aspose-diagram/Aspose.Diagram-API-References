---
title: 이미지
second_title: Aspose.Diagram for Java API 참조
description: 비트맵에 대한 감마, 밝기, 대비, 흐림, 선명도, 노이즈 제거 및 투명도 값을 포함합니다.
type: docs
weight: 196
url: /ko/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

비트맵에 대한 감마, 밝기, 대비, 흐림, 선명화, 노이즈 제거 및 투명도 값을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | 비트맵 이미지를 흐리게 하거나 부드럽게 합니다. |
| [getBrightness()](#getBrightness--) | 비트맵 이미지의 밝기를 조정합니다. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | 비트맵 이미지의 대비를 지정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDenoise()](#getDenoise--) | 비트맵 이미지에서 노이즈(무작위로 분포된 색상 레벨을 가진 픽셀)를 제거합니다. |
| [getGamma()](#getGamma--) | 모니터나 스캐너와 같은 특정 출력 장치에 맞게 이미지의 강도를 조정하거나 보정합니다. |
| [getSharpen()](#getSharpen--) | 비트맵 이미지를 선명하게 할 정도를 지정합니다. |
| [getTransparency()](#getTransparency--) | 레이어 색상의 투명도 수준을 0(불투명)에서 1(완전 투명)까지 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/image\#getDel--)을 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


비트맵 이미지를 흐리게 하거나 부드럽게 합니다. Blur 요소는 0에서 1 사이의 값을 포함하며, 기본값은 0입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


비트맵 이미지의 밝기를 조정합니다. Brightness 요소는 0에서 1 사이의 값을 포함하며, 기본값은 0.5입니다.

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


비트맵 이미지의 대비를 지정합니다. Contrast 요소는 0에서 1 사이의 값을 포함합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


비트맵 이미지에서 노이즈(무작위로 분포된 색상 레벨을 가진 픽셀)를 제거합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


모니터나 스캐너와 같은 특정 출력 장치에 맞게 이미지의 강도를 조정하거나 보정합니다. 기본값은 1(보정 없음)입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


비트맵 이미지를 선명하게 할 정도를 지정합니다. 이미지를 선명하게 하면 인접 픽셀의 대비를 높여 초점을 맞춥니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


레이어 색상의 투명도 수준을 0(불투명)에서 1(완전 투명)까지 지정합니다.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/image\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

