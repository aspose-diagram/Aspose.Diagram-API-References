---
title: PdfEncryptionDetails
second_title: Справочник API Aspose.Diagram for Java
description: Содержит детали шифрования PDF.
type: docs
weight: 279
url: /ru/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

Содержит детали шифрования PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | режим шифрования. |
| [getOwnerPassword()](#getOwnerPassword--) | пароль владельца. |
| [getPermissions()](#getPermissions--) | разрешения. |
| [getUserPassword()](#getUserPassword--) | пароль пользователя. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | Для описания этого свойства, пожалуйста, см. [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) |
| [setPermissions(int value)](#setPermissions-int-) | Для описания этого свойства, пожалуйста, см. [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


Конструктор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

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
### getEncryptionAlgorithm() {#getEncryptionAlgorithm--}
```
public int getEncryptionAlgorithm()
```


режим шифрования.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


Пароль владельца. Открытие документа с правильным паролем владельца (при условии, что он отличается от пароля пользователя) предоставляет полный (владельческий) доступ к документу. Этот неограниченный доступ включает возможность изменять пароли документа\\u9225\\u6a9a и права доступа.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


разрешения.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


Пароль пользователя. Открытие документа с правильным паролем пользователя (или открытие документа без пароля пользователя) позволяет выполнять дополнительные операции в соответствии с правами доступа пользователя, указанными в словаре шифрования документа\\u9225\\u6a9a.

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


Для описания этого свойства, пожалуйста, см. [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Для описания этого свойства, пожалуйста, см. [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


Для описания этого свойства, пожалуйста, см. [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Для описания этого свойства, пожалуйста, см. [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

