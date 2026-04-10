---
title: PdfPermissions
second_title: Referencia de API de Aspose.Diagram para Java
description: Especifica los permisos de usuario para el documento PDF.
type: docs
weight: 280
url: /es/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Especifica los permisos de usuario para el documento PDF.
## Campos

| Campo | Descripción |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Permite todas las operaciones en el documento PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | Permite copiar o extraer de otro modo texto y gráficos del documento, incluida la extracción con fines de accesibilidad. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Permite extraer texto y gráficos en apoyo a la accesibilidad para usuarios con discapacidad o para otros propósitos. |
| [DISALLOW_ALL](#DISALLOW-ALL) | No permite ninguna operación en el documento PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Permite ensamblar el documento: insertar, rotar o eliminar páginas y crear elementos de navegación como marcadores o imágenes en miniatura. |
| [FILL_IN](#FILL-IN) | Permite rellenar formularios y firmar el documento. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Permite imprimir el documento a la mayor resolución posible. Cuando se usa cifrado RC4 de 40 bits, esta opción se ignora y la impresión de alta resolución está permitida cuando la opción Printing está activada. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Permite agregar o modificar anotaciones de texto. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Permite modificar el contenido del documento\u9225\u6a9a. |
| [PRINTING](#PRINTING) | Permite imprimir el documento. |
## Métodos

| Método | Descripción |
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


Permite todas las operaciones en el documento PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Permite copiar o extraer de otro modo texto y gráficos del documento, incluida la extracción con fines de accesibilidad.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Permite extraer texto y gráficos en apoyo a la accesibilidad para usuarios con discapacidad o para otros propósitos. Al usar cifrado RC4 de 40 bits, esta opción se ignora y la accesibilidad está permitida siempre que ContentCopy esté configurado.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


No permite ninguna operación en el documento PDF. Este es el valor predeterminado.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Permite ensamblar el documento: insertar, rotar o eliminar páginas y crear elementos de navegación como marcadores o imágenes en miniatura. Al usar cifrado RC4 de 40 bits, esta opción se ignora y el ensamblado del documento está permitido cuando ModifyContents está configurado.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Permite rellenar formularios y firmar el documento. Al usar cifrado RC4 de 40 bits, esta opción se ignora y el relleno de formularios está permitido siempre que ModifyAnnotations esté configurado.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Permite imprimir el documento a la mayor resolución posible. Cuando se usa cifrado RC4 de 40 bits, esta opción se ignora y la impresión de alta resolución está permitida cuando la opción Printing está activada.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Permite agregar o modificar anotaciones de texto. Al usar cifrado RC4 de 40 bits, esta opción también permite rellenar campos de formulario.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Permite modificar el contenido del documento\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Permite imprimir el documento.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

