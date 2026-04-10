---
title: PdfPermissions
second_title: Aspose.Diagram for Java API 参考
description: 指定 PDF 文档的用户权限。
type: docs
weight: 280
url: /zh/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

指定 PDF 文档的用户权限。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | 允许对 PDF 文档进行所有操作。 |
| [CONTENT_COPY](#CONTENT-COPY) | 允许复制或以其他方式从文档中提取文本和图形，包括出于可访问性目的的提取。 |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | 允许提取文本和图形，以支持残障用户的可访问性或出于其他目的。 |
| [DISALLOW_ALL](#DISALLOW-ALL) | 不允许对 PDF 文档进行任何操作。 |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | 允许组装文档：插入、旋转或删除页面，并创建书签或缩略图等导航元素。 |
| [FILL_IN](#FILL-IN) | 允许填写表单并对文档进行签名。 |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | 允许以最高可能分辨率打印文档。使用 RC4 40 位加密时，此选项将被忽略，并且在设置 Printing 时允许高分辨率打印。 |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | 允许添加或修改文本批注。 |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | 允许修改文档\u9225\u6a9a 内容。 |
| [PRINTING](#PRINTING) | 允许打印文档。 |
## 方法

| 方法 | 描述 |
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


允许对 PDF 文档进行所有操作。

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


允许复制或以其他方式从文档中提取文本和图形，包括出于可访问性目的的提取。

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


允许提取文本和图形，以支持残障用户的可访问性或用于其他目的。使用 RC4 40 位加密时，此选项将被忽略，并且只要设置了 ContentCopy，就会允许可访问性。

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


禁止对 PDF 文档的所有操作。这是默认值。

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


允许组装文档：插入、旋转或删除页面，并创建书签或缩略图等导航元素。使用 RC4 40 位加密时，此选项将被忽略，并且只要设置了 ModifyContents，就允许文档组装。

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


允许填写表单并对文档进行签名。使用 RC4 40 位加密时，此选项将被忽略，只要设置了 ModifyAnnotations，就允许填写表单。

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


允许以最高可能分辨率打印文档。使用 RC4 40 位加密时，此选项将被忽略，并且在设置 Printing 时允许高分辨率打印。

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


允许添加或修改文本批注。使用 RC4 40 位加密时，此选项还允许填写表单字段。

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


允许修改文档\u9225\u6a9a 内容。

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


允许打印文档。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

