---
title: StreamProviderOptions
second_title: Aspose.Diagram for Java API 참조
description: 스트림 옵션을 나타냅니다.
type: docs
weight: 390
url: /ko/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

스트림 옵션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | 참조된 소스에 대해 생성된 HTML 파일에 저장되는 기본 경로(URL)입니다. |
| [getStream()](#getStream--) | 저장된 데이터를 쓰기 위한 출력 스트림을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | 참조된 소스에 대해 생성된 HTML 파일에 저장되는 사용자 지정 경로(URL)입니다. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | 이 속성에 대한 설명은 [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


참조된 소스에 대해 생성된 HTML 파일에 저장되는 기본 경로(URL)입니다. 예를 들어, 시트 데이터가 xxx\_files/sheet001.htm에 저장되는 경우, 메인 HTML 파일에서 사용되는 URL은 "src=\"xxx\_files/sheet001.htm\""와 같이 되어야 합니다.

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


저장된 데이터를 쓰기 위한 출력 스트림을 가져오거나 설정합니다.

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


참조된 소스에 대해 생성된 HTML 파일에 저장되는 사용자 지정 경로(URL)입니다. 사용자가 정의하지 않으면 DefaultPath가 사용됩니다. 예를 들어, 시트 데이터가 사용자가 d:/sheet001.htm에 저장하면, 메인 HTML 파일에서 사용되는 URL은 "d:/sheet001.htm" 또는 메인 HTML 파일에서 접근 가능한 다른 유효한 상대 경로가 되어야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


이 속성에 대한 설명은 [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.OutputStream |  |

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

