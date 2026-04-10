---
title: PdfPermissions
second_title: Справочник API Aspose.Diagram for Java
description: Указывает пользовательские разрешения для PDF‑документа.
type: docs
weight: 280
url: /ru/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Указывает пользовательские разрешения для PDF‑документа.
## Поля

| Поле | Описание |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Разрешает все операции над PDF‑документом. |
| [CONTENT_COPY](#CONTENT-COPY) | Разрешает копирование или иное извлечение текста и графики из документа, включая извлечение в целях доступности. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Разрешает извлечение текста и графики в поддержку доступности для пользователей с ограниченными возможностями или в других целях. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Запрещает все операции над PDF‑документом. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Разрешает сборку документа: вставку, поворот или удаление страниц и создание навигационных элементов, таких как закладки или миниатюры. |
| [FILL_IN](#FILL-IN) | Разрешает заполнение форм и подпись документа. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Разрешает печать документа с максимально возможным разрешением. При использовании 40‑битного шифрования RC4 эта опция игнорируется, и печать с высоким разрешением разрешена, если включена настройка Printing. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Разрешает добавлять или изменять текстовые аннотации. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Разрешает изменять содержимое документа\u9225\u6a9a. |
| [PRINTING](#PRINTING) | Разрешает печатать документ. |
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
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Разрешает все операции над PDF‑документом.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Разрешает копирование или иное извлечение текста и графики из документа, включая извлечение в целях доступности.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Разрешает извлекать текст и графику в поддержку доступности для пользователей с ограниченными возможностями или для других целей. При использовании 40‑битного шифрования RC4 эта опция игнорируется, и доступность разрешена, когда установлен параметр ContentCopy.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Запрещает все операции с PDF‑документом. Это значение по умолчанию.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Разрешает сборку документа: вставку, вращение или удаление страниц и создание навигационных элементов, таких как закладки или миниатюры. При использовании 40‑битного шифрования RC4 эта опция игнорируется, и сборка документа разрешена, когда установлен параметр ModifyContents.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Разрешает заполнять формы и подписывать документ. При использовании 40‑битного шифрования RC4 эта опция игнорируется, и заполнение форм разрешено, когда установлен параметр ModifyAnnotations.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Разрешает печать документа с максимально возможным разрешением. При использовании 40‑битного шифрования RC4 эта опция игнорируется, и печать с высоким разрешением разрешена, если включена настройка Printing.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Разрешает добавлять или изменять текстовые аннотации. При использовании 40‑битного шифрования RC4 эта опция также позволяет заполнять поля форм.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Разрешает изменять содержимое документа\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Разрешает печатать документ.

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

