---
title: PdfEncryptionDetails
second_title: Aspose.Diagram for Java API リファレンス
description: PDF 暗号化に関する詳細を含みます。
type: docs
weight: 279
url: /ja/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

PDF 暗号化に関する詳細を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | 暗号化モードです。 |
| [getOwnerPassword()](#getOwnerPassword--) | 所有者パスワードです。 |
| [getPermissions()](#getPermissions--) | 権限です。 |
| [getUserPassword()](#getUserPassword--) | ユーザーパスワードです。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | このプロパティの説明については、[getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) を参照してください。 |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | このプロパティの説明については、[getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) を参照してください。 |
| [setPermissions(int value)](#setPermissions-int-) | このプロパティの説明については、[getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) を参照してください。 |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | このプロパティの説明については、[getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


コンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


暗号化モードです。

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


所有者パスワードです。正しい所有者パスワードでドキュメントを開くと（ユーザーパスワードと同じでないと仮定して）、ドキュメントへの完全な（所有者）アクセスが可能になります。この無制限のアクセスには、ドキュメント\u9225\u6a9a パスワードとアクセス権限を変更できる機能が含まれます。

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


権限です。

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


ユーザーパスワードです。正しいユーザーパスワードでドキュメントを開く（またはユーザーパスワードが設定されていないドキュメントを開く）と、ドキュメント\u9225\u6a9a 暗号化辞書に指定されたユーザーアクセス権限に従って追加の操作を実行できます。

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


このプロパティの説明については、[getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


このプロパティの説明については、[getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


このプロパティの説明については、[getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


このプロパティの説明については、[getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

