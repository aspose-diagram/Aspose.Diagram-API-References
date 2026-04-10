---
title: EventItem
second_title: Referensi API Aspose.Diagram untuk Java
description: Mengkapsulkan kode peristiwa.
type: docs
weight: 145
url: /id/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Menyatukan kode acara. Elemen EventItem dapat memicu dua jenis tindakan: dapat menjalankan add-on, atau dapat mengirim notifikasi acara ke program pemanggil.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EventItem()](#EventItem--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Menentukan kode aksi dari elemen EventItem induk. Untuk elemen EventItem dapat disimpan dalam file DatadiagramML, harus dapat dipertahankan. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Mewakili flag yang menunjukkan apakah acara diaktifkan atau dinonaktifkan. |
| [getEventCode()](#getEventCode--) | Kode yang menunjukkan acara yang memicu add-on. |
| [getID()](#getID--) | ID acara. |
| [getTarget()](#getTarget--) | Menentukan target dari sebuah acara. |
| [getTargetArgs()](#getTargetArgs--) | Menentukan string yang berisi argumen yang akan dikirim ke target acara. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Untuk deskripsi properti ini, silakan lihat [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Untuk deskripsi properti ini, silakan lihat [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Untuk deskripsi properti ini, silakan lihat [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


Konstruktor.

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
### getAction() {#getAction--}
```
public int getAction()
```


Menentukan kode aksi dari elemen EventItem induk. Untuk elemen EventItem dapat disimpan dalam file DatadiagramML, harus dapat dipertahankan. Saat ini, satu-satunya kode aksi yang valid untuk acara yang dapat dipertahankan adalah 1 (ONEVENT_ACT_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Mewakili flag yang menunjukkan apakah acara diaktifkan atau dinonaktifkan.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Kode yang menunjukkan acara yang memicu add-on. Untuk informasi lebih lanjut tentang kode acara, lihat Kode Acara dalam Referensi Otomasi Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


ID acara.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Menentukan target dari sebuah acara.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Menentukan string yang berisi argumen yang akan dikirim ke target acara.

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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


Untuk deskripsi properti ini, silakan lihat [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Untuk deskripsi properti ini, silakan lihat [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Untuk deskripsi properti ini, silakan lihat [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Untuk deskripsi properti ini, silakan lihat [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Untuk deskripsi properti ini, silakan lihat [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

