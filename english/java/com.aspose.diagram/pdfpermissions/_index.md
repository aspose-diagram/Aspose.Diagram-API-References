---
title: PdfPermissions
second_title: Aspose.Diagram for Java API Reference
description: Specifies user permissions for PDF document.
type: docs
weight: 283
url: /java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Specifies user permissions for PDF document.
## Fields

| Field | Description |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Allows all operations on the PDF document. |
| [CONTENT_COPY](#CONTENT-COPY) | Allows copying or otherwise extracting text and graphics from the document, including extraction for accessibility purposes. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Allows extract text and graphics in support of accessibility to disabled users or for other purposes. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Disallows all operations on the PDF document. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Allows assembling the document: inserting, rotating, or deleting pages and creating navigation elements such as bookmarks or thumbnail images. |
| [FILL_IN](#FILL-IN) | Allows filling in forms and signing the document. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Allows printing the document to the highest resolution possible.When using RC4 40-bit encryption, this option is ignored and high resolution printing is allowed when Printing is set. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Allows adding or modifying text annotations. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Allows modifying the document\\u9225\\u6a9a contents. |
| [PRINTING](#PRINTING) | Allows printing the document. |
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
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Allows all operations on the PDF document.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Allows copying or otherwise extracting text and graphics from the document, including extraction for accessibility purposes.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Allows extract text and graphics in support of accessibility to disabled users or for other purposes. When using RC4 40-bit encryption, this option is ignored and accessibility is allowed whenever ContentCopy is set.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Disallows all operations on the PDF document. This is the default value.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Allows assembling the document: inserting, rotating, or deleting pages and creating navigation elements such as bookmarks or thumbnail images. When using RC4 40-bit encryption, this option is ignored and document assembly is allowed when ModifyContents is set.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Allows filling in forms and signing the document. When using RC4 40-bit encryption, this option is ignored and filling in form is allowed whenever ModifyAnnotations is set.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Allows printing the document to the highest resolution possible.When using RC4 40-bit encryption, this option is ignored and high resolution printing is allowed when Printing is set.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Allows adding or modifying text annotations. When using RC4 40-bit encryption, this option also allows filling in form fields.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Allows modifying the document\\u9225\\u6a9a contents.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Allows printing the document.

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

