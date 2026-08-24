---
title: Issue
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili satu masalah validasi dalam dokumen.
type: docs
weight: 208
url: /id/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Mewakili satu masalah validasi dalam dokumen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Issue()](#Issue--) | Konstruktor |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Menentukan pengidentifikasi unik dari masalah validasi. |
| [getIgnored()](#getIgnored--) | Menentukan apakah masalah validasi saat ini diabaikan. |
| [getIssueTarget()](#getIssueTarget--) | Bergantung pada target masalah validasi induk, menentukan halaman, atau halaman dan bentuk, yang terkait dengan masalah validasi induk. |
| [getRuleInfo()](#getRuleInfo--) | Menentukan informasi tentang aturan validasi yang terkait dengan masalah validasi induk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Untuk deskripsi properti ini, silakan lihat [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Konstruktor

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
### getID() {#getID--}
```
public long getID()
```


Menentukan pengidentifikasi unik dari masalah validasi.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Menentukan apakah masalah validasi saat ini diabaikan. Nilai default adalah False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Bergantung pada target dari isu validasi induk, menentukan baik halaman, atau halaman dan bentuk, yang terkait dengan isu validasi induk. Jika target dari isu validasi induk adalah dokumen, IssueTarget tidak menentukan halaman maupun bentuk.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Menentukan informasi tentang aturan validasi yang terkait dengan masalah validasi induk.

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

