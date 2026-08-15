---
title: PdfPermissions
second_title: Aspose.Diagram for Java API リファレンス
description: PDF ドキュメントのユーザー権限を指定します。
type: docs
weight: 280
url: /ja/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

PDF ドキュメントのユーザー権限を指定します。
## Fields

| Field | 説明 |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | PDF ドキュメントに対するすべての操作を許可します。 |
| [CONTENT_COPY](#CONTENT-COPY) | ドキュメントからテキストやグラフィックをコピーまたは抽出することを許可します。アクセシビリティ目的の抽出も含まれます。 |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | 障害者向けのアクセシビリティ支援やその他の目的でテキストとグラフィックの抽出を許可します。 |
| [DISALLOW_ALL](#DISALLOW-ALL) | PDF ドキュメントに対するすべての操作を禁止します。 |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | ドキュメントの組み立てを許可します：ページの挿入、回転、削除や、ブックマークやサムネイル画像などのナビゲーション要素の作成。 |
| [FILL_IN](#FILL-IN) | フォームへの入力とドキュメントへの署名を許可します。 |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | 可能な限り最高解像度でドキュメントの印刷を許可します。RC4 40 ビット暗号化を使用している場合、このオプションは無視され、Printing が設定されているときは高解像度印刷が許可されます。 |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | テキスト注釈の追加または変更を許可します。 |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | 文書\u9225\u6a9a の内容を変更することを許可します。 |
| [PRINTING](#PRINTING) | 文書の印刷を許可します。 |
## メソッド

| メソッド | 説明 |
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


PDF ドキュメントに対するすべての操作を許可します。

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


ドキュメントからテキストやグラフィックをコピーまたは抽出することを許可します。アクセシビリティ目的の抽出も含まれます。

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


障害者向けのアクセシビリティ支援やその他の目的で、テキストとグラフィックの抽出を許可します。RC4 40ビット暗号化を使用する場合、このオプションは無視され、ContentCopy が設定されている場合は常にアクセシビリティが許可されます。

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


PDF 文書に対するすべての操作を禁止します。これはデフォルト値です。

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


文書の組み立てを許可します：ページの挿入、回転、削除や、ブックマークやサムネイル画像などのナビゲーション要素の作成。RC4 40ビット暗号化を使用する場合、このオプションは無視され、ModifyContents が設定されているときに文書の組み立てが許可されます。

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


フォームへの入力と文書への署名を許可します。RC4 40ビット暗号化を使用する場合、このオプションは無視され、ModifyAnnotations が設定されている場合は常にフォームへの入力が許可されます。

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


可能な限り最高解像度でドキュメントの印刷を許可します。RC4 40 ビット暗号化を使用している場合、このオプションは無視され、Printing が設定されているときは高解像度印刷が許可されます。

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


テキスト注釈の追加または変更を許可します。RC4 40ビット暗号化を使用する場合、このオプションはフォームフィールドへの入力も許可します。

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


文書\u9225\u6a9a の内容を変更することを許可します。

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


文書の印刷を許可します。

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

