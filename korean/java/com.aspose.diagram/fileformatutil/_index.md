---
title: FileFormatUtil
second_title: Aspose.Diagram for Java API 참조
description: 파일 형식 열거형을 문자열이나 파일 확장자로 변환하고 다시 변환하는 유틸리티 메서드를 제공합니다.
type: docs
weight: 152
url: /ko/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

파일 형식 열거형을 문자열이나 파일 확장자로 변환하고 다시 변환하는 유틸리티 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | 스트림에 저장된 Visio 형식에 대한 정보를 감지하고 반환합니다. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | 파일에 저장된 Visio 형식에 대한 정보를 감지하고 반환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


스트림에 저장된 Visio 형식에 대한 정보를 감지하고 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 스트림 |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


파일에 저장된 Visio 형식에 대한 정보를 감지하고 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
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

