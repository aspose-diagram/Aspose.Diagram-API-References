---
title: PdfEncryptionDetails
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene detalles para un cifrado PDF.
type: docs
weight: 279
url: /es/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

Contiene detalles para un cifrado PDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | Ctor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | el modo de cifrado. |
| [getOwnerPassword()](#getOwnerPassword--) | la contraseña Owner. |
| [getPermissions()](#getPermissions--) | los permisos. |
| [getUserPassword()](#getUserPassword--) | la contraseña User. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | Para la descripción de esta propiedad, consulte [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Para la descripción de esta propiedad, consulte [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) |
| [setPermissions(int value)](#setPermissions-int-) | Para la descripción de esta propiedad, consulte [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Para la descripción de esta propiedad, consulte [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


Ctor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

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
### getEncryptionAlgorithm() {#getEncryptionAlgorithm--}
```
public int getEncryptionAlgorithm()
```


el modo de cifrado.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


la contraseña del propietario. Abrir el documento con la contraseña de propietario correcta (asumiendo que no sea la misma que la contraseña de usuario) permite acceso total (de propietario) al documento. Este acceso ilimitado incluye la capacidad de cambiar las contraseñas del documento\\u9225\\u6a9a y los permisos de acceso.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


los permisos.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


la contraseña de usuario. Abrir el documento con la contraseña de usuario correcta (o abrir un documento que no tenga contraseña de usuario) permite realizar operaciones adicionales según los permisos de acceso de usuario especificados en el diccionario de cifrado del documento\\u9225\\u6a9a.

**Returns:**
java.lang.String
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




### setEncryptionAlgorithm(int value) {#setEncryptionAlgorithm-int-}
```
public void setEncryptionAlgorithm(int value)
```


Para la descripción de esta propiedad, consulte [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Para la descripción de esta propiedad, consulte [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


Para la descripción de esta propiedad, consulte [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Para la descripción de esta propiedad, consulte [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

