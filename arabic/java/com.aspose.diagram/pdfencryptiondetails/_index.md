---
title: PdfEncryptionDetails
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على تفاصيل لتشفير PDF.
type: docs
weight: 279
url: /ar/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

يحتوي على تفاصيل لتشفير PDF.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | وضع التشفير. |
| [getOwnerPassword()](#getOwnerPassword--) | كلمة مرور المالك. |
| [getPermissions()](#getPermissions--) | الأذونات. |
| [getUserPassword()](#getUserPassword--) | كلمة مرور المستخدم. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) |
| [setPermissions(int value)](#setPermissions-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


منشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
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


وضع التشفير.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


كلمة مرور المالك. فتح المستند باستخدام كلمة مرور المالك الصحيحة (على افتراض أنها ليست هي نفسها كلمة مرور المستخدم) يتيح وصولًا كاملاً (كمالك) إلى المستند. هذا الوصول غير المحدود يشمل القدرة على تغيير كلمات مرور المستند\u9225\u6a9a وأذونات الوصول.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


الأذونات.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


كلمة مرور المستخدم. فتح المستند باستخدام كلمة مرور المستخدم الصحيحة (أو فتح مستند لا يحتوي على كلمة مرور مستخدم) يتيح تنفيذ عمليات إضافية وفقًا لأذونات وصول المستخدم المحددة في قاموس تشفير المستند\u9225\u6a9a.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

