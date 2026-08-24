---
title: IssueTarget
second_title: Referensi API Aspose.Diagram untuk Java
description: Bergantung pada target dari isu validasi induk, menentukan baik halaman atau baik halaman maupun bentuk yang terkait dengan isu validasi induk.
type: docs
weight: 210
url: /id/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

Bergantung pada target dari isu validasi induk, menentukan baik halaman, atau halaman dan bentuk, yang terkait dengan isu validasi induk. Jika target dari isu validasi induk adalah dokumen, IssueTarget tidak menentukan halaman maupun bentuk.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Menentukan pengenal unik dari halaman yang terkait dengan isu validasi induk. |
| [getShapeId()](#getShapeId--) | Menentukan pengenal unik dari bentuk yang terkait dengan isu validasi induk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Untuk deskripsi properti ini, silakan lihat [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Untuk deskripsi properti ini, silakan lihat [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


Menentukan pengenal unik dari halaman yang terkait dengan isu validasi induk. Jika targetnya adalah dokumen, nilai PageID dapat berupa 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Menentukan pengenal unik dari bentuk yang terkait dengan isu validasi induk. Jika targetnya adalah dokumen atau halaman, nilai ShapeID dapat berupa 0xFFFFFFFF.

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


Untuk deskripsi properti ini, silakan lihat [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Untuk deskripsi properti ini, silakan lihat [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

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

