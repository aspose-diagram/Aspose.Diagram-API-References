---
title: Encoding
second_title: Aspose.Diagram for Java API 참조
description: 문자 인코딩을 나타냅니다.
type: docs
weight: 143
url: /ko/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

문자 인코딩을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | 지정된 Encoding 객체가 현재 인스턴스와 같은지 여부를 결정합니다. |
| [equals(Object o)](#equals-java.lang.Object-) | 지정된 Object가 현재 인스턴스와 같은지 여부를 결정합니다. |
| [getASCII()](#getASCII--) | ASCII (7비트) 문자 집합에 대한 인코딩을 가져옵니다. |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | 빅 엔디안 바이트 순서를 사용한 UTF-16 형식에 대한 인코딩을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | 운영 체제의 현재 ANSI 코드 페이지에 대한 인코딩을 가져옵니다. |
| [getEncoding(int codePage)](#getEncoding-int-) | 지정된 코드 페이지 식별자와 연결된 인코딩을 반환합니다. |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | 지정된 문자 집합 이름과 연결된 인코딩을 반환합니다. |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | 지정된 문자 집합 객체와 연결된 인코딩을 반환합니다. |
| [getUTF7()](#getUTF7--) | UTF-7 형식에 대한 인코딩을 가져옵니다. |
| [getUTF8()](#getUTF8--) | UTF-8 형식에 대한 인코딩을 가져옵니다. |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | UTF-8 식별자 없이 UTF-8 형식에 대한 인코딩을 가져옵니다. |
| [getUnicode()](#getUnicode--) | 리틀 엔디안 바이트 순서를 사용한 UTF-16 형식에 대한 인코딩을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


지정된 Encoding 객체가 현재 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | 현재 인스턴스와 비교할 Encoding 객체입니다. |

**Returns:**
boolean - 값이 현재 인스턴스와 같으면 true; 그렇지 않으면 false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


지정된 Object가 현재 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | 현재 인스턴스와 비교할 객체. |

**Returns:**
boolean - 값이 Encoding의 인스턴스이며 현재 인스턴스와 같으면 true; 그렇지 않으면 false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


ASCII (7비트) 문자 집합에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


빅 엔디안 바이트 순서를 사용한 UTF-16 형식에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


운영 체제의 현재 ANSI 코드 페이지에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


지정된 코드 페이지 식별자와 연결된 인코딩을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| codePage | int | 선호하는 인코딩의 코드 페이지 식별자. -or- 0은 기본 인코딩을 사용합니다. |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


지정된 문자 집합 이름과 연결된 인코딩을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charsetName | java.lang.String | 지정된 문자 집합 이름 |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


지정된 문자 집합 객체와 연결된 인코딩을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| charset | java.nio.charset.Charset | 지정된 문자 집합 객체 |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


UTF-7 형식에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


UTF-8 형식에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


UTF-8 식별자 없이 UTF-8 형식에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


리틀 엔디안 바이트 순서를 사용한 UTF-16 형식에 대한 인코딩을 가져옵니다.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

