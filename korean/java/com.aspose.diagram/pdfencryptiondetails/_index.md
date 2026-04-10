---
title: PdfEncryptionDetails
second_title: Aspose.Diagram for Java API 참조
description: PDF 암호화에 대한 세부 정보를 포함합니다.
type: docs
weight: 279
url: /ko/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

PDF 암호화에 대한 세부 정보를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | 암호화 모드입니다. |
| [getOwnerPassword()](#getOwnerPassword--) | 소유자 비밀번호입니다. |
| [getPermissions()](#getPermissions--) | 권한입니다. |
| [getUserPassword()](#getUserPassword--) | 사용자 비밀번호입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | 이 속성에 대한 설명은 [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)을(를) 참조하십시오. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | 이 속성에 대한 설명은 [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)을(를) 참조하십시오. |
| [setPermissions(int value)](#setPermissions-int-) | 이 속성에 대한 설명은 [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)을(를) 참조하십시오. |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | 이 속성에 대한 설명은 [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


생성자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

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
### getEncryptionAlgorithm() {#getEncryptionAlgorithm--}
```
public int getEncryptionAlgorithm()
```


암호화 모드입니다.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


소유자 비밀번호. 올바른 소유자 비밀번호로 문서를 열면(사용자 비밀번호와 동일하지 않다고 가정) 문서에 대한 전체(소유자) 액세스가 허용됩니다. 이 무제한 액세스에는 문서\\u9225\\u6a9a 비밀번호 및 액세스 권한을 변경할 수 있는 기능이 포함됩니다.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


권한입니다.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


사용자 비밀번호. 올바른 사용자 비밀번호로 문서를 열거나(사용자 비밀번호가 없는 문서를 열 경우) 문서에 지정된 사용자 액세스 권한에 따라 추가 작업을 수행할 수 있습니다. 이 작업은 문서\\u9225\\u6a9a 암호화 사전에서 지정된 사용자 액세스 권한에 따라 수행됩니다.

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


이 속성에 대한 설명은 [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


이 속성에 대한 설명은 [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


이 속성에 대한 설명은 [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


이 속성에 대한 설명은 [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

