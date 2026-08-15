---
title: PdfPermissions
second_title: Aspose.Diagram for Java API 참조
description: PDF 문서에 대한 사용자 권한을 지정합니다.
type: docs
weight: 280
url: /ko/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

PDF 문서에 대한 사용자 권한을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | PDF 문서에 대한 모든 작업을 허용합니다. |
| [CONTENT_COPY](#CONTENT-COPY) | 문서에서 텍스트와 그래픽을 복사하거나 추출하는 것을 허용합니다. 접근성 목적을 위한 추출도 포함됩니다. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | 장애인 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출하는 것을 허용합니다. |
| [DISALLOW_ALL](#DISALLOW-ALL) | PDF 문서에 대한 모든 작업을 금지합니다. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | 문서를 조립하는 것을 허용합니다: 페이지 삽입, 회전, 삭제 및 북마크나 썸네일 이미지와 같은 탐색 요소 생성. |
| [FILL_IN](#FILL-IN) | 양식을 작성하고 문서에 서명하는 것을 허용합니다. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | 가능한 최고 해상도로 문서를 인쇄하는 것을 허용합니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며, Printing이 설정된 경우 고해상도 인쇄가 허용됩니다. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | 텍스트 주석을 추가하거나 수정할 수 있습니다. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | 문서\u9225\u6a9a 내용을 수정할 수 있습니다. |
| [PRINTING](#PRINTING) | 문서를 인쇄할 수 있습니다. |
## 메서드

| 메서드 | 설명 |
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
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


PDF 문서에 대한 모든 작업을 허용합니다.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


문서에서 텍스트와 그래픽을 복사하거나 추출하는 것을 허용합니다. 접근성 목적을 위한 추출도 포함됩니다.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


장애인 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있습니다. RC4 40비트 암호화를 사용할 경우 이 옵션은 무시되며 ContentCopy가 설정된 경우 언제든지 접근성이 허용됩니다.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


PDF 문서에 대한 모든 작업을 허용하지 않습니다. 이것이 기본값입니다.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


문서를 조립할 수 있습니다: 페이지 삽입, 회전 또는 삭제와 북마크나 썸네일 이미지와 같은 탐색 요소를 생성합니다. RC4 40비트 암호화를 사용할 경우 이 옵션은 무시되며 ModifyContents가 설정된 경우 문서 조립이 허용됩니다.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


양식을 작성하고 문서에 서명할 수 있습니다. RC4 40비트 암호화를 사용할 경우 이 옵션은 무시되며 ModifyAnnotations가 설정된 경우 언제든지 양식 작성이 허용됩니다.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


가능한 최고 해상도로 문서를 인쇄하는 것을 허용합니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며, Printing이 설정된 경우 고해상도 인쇄가 허용됩니다.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


텍스트 주석을 추가하거나 수정할 수 있습니다. RC4 40비트 암호화를 사용할 경우 이 옵션은 양식 필드 작성도 허용합니다.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


문서\u9225\u6a9a 내용을 수정할 수 있습니다.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


문서를 인쇄할 수 있습니다.

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

