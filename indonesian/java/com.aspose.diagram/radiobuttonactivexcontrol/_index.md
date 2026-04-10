---
title: RadioButtonActiveXControl
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili kontrol ActiveX RadioButton.
type: docs
weight: 313
url: /id/java/com.aspose.diagram/radiobuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.ToggleButtonActiveXControl](../../com.aspose.diagram/togglebuttonactivexcontrol)
```
public class RadioButtonActiveXControl extends ToggleButtonActiveXControl
```

Mewakili kontrol ActiveX RadioButton.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | kunci akselerator untuk kontrol. |
| [getAlignment()](#getAlignment--) | posisi Caption relatif terhadap kontrol. |
| [getBackOleColor()](#getBackOleColor--) | warna ole latar belakang. |
| [getCaption()](#getCaption--) | teks deskriptif yang muncul pada kontrol. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | data biner kontrol. |
| [getForeOleColor()](#getForeOleColor--) | warna ole latar depan. |
| [getGroupName()](#getGroupName--) | nama grup. |
| [getHeight()](#getHeight--) | tinggi kontrol dalam satuan poin. |
| [getIMEMode()](#getIMEMode--) | mode run-time default Input Method Editor untuk kontrol saat menerima fokus. |
| [getMouseIcon()](#getMouseIcon--) | ikon khusus untuk ditampilkan sebagai penunjuk mouse bagi kontrol. |
| [getMousePointer()](#getMousePointer--) | jenis ikon yang ditampilkan sebagai penunjuk mouse bagi kontrol. |
| [getPicture()](#getPicture--) | data gambar. |
| [getPicturePosition()](#getPicturePosition--) | lokasi gambar kontrol relatif terhadap caption-nya. |
| [getSpecialEffect()](#getSpecialEffect--) | efek khusus kontrol. |
| [getType()](#getType--) | Mendapatkan jenis kontrol ActiveX. |
| [getValue()](#getValue--) | Menunjukkan apakah kontrol dicentang atau tidak. |
| [getWidth()](#getWidth--) | lebar kontrol dalam satuan poin. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Menunjukkan apakah kontrol akan secara otomatis mengubah ukuran untuk menampilkan seluruh isinya. |
| [isEnabled()](#isEnabled--) | Menunjukkan apakah kontrol dapat menerima fokus dan merespons peristiwa yang dihasilkan pengguna. |
| [isLocked()](#isLocked--) | Menunjukkan apakah data dalam kontrol terkunci untuk penyuntingan. |
| [isTransparent()](#isTransparent--) | Menunjukkan apakah kontrol transparan. |
| [isTripleState()](#isTripleState--) | Menunjukkan bagaimana kontrol yang ditentukan akan menampilkan nilai Null. |
| [isWordWrapped()](#isWordWrapped--) | Menunjukkan apakah isi kontrol secara otomatis membungkus pada akhir baris. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | Untuk deskripsi properti ini, silakan lihat [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--) |
| [setAlignment(int value)](#setAlignment-int-) | Untuk deskripsi properti ini, silakan lihat [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Untuk deskripsi properti ini, silakan lihat [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Untuk deskripsi properti ini, silakan lihat [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Untuk deskripsi properti ini, silakan lihat [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Untuk deskripsi properti ini, silakan lihat [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setGroupName(String value)](#setGroupName-java.lang.String-) | Untuk deskripsi properti ini, silakan lihat [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--) |
| [setHeight(double value)](#setHeight-double-) | Untuk deskripsi properti ini, silakan lihat [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Untuk deskripsi properti ini, silakan lihat [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Untuk deskripsi properti ini, silakan lihat [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Untuk deskripsi properti ini, silakan lihat [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Untuk deskripsi properti ini, silakan lihat [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Untuk deskripsi properti ini, silakan lihat [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | Untuk deskripsi properti ini, silakan lihat [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Untuk deskripsi properti ini, silakan lihat [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Untuk deskripsi properti ini, silakan lihat [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | Untuk deskripsi properti ini, silakan lihat [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | Untuk deskripsi properti ini, silakan lihat [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Untuk deskripsi properti ini, silakan lihat [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Untuk deskripsi properti ini, silakan lihat [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


kunci akselerator untuk kontrol.

**Returns:**
char
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


posisi Caption relatif terhadap kontrol.

**Returns:**
int
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


warna ole latar belakang.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


teks deskriptif yang muncul pada kontrol.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


data biner kontrol.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


Warna OLE latar depan. Tidak berlaku untuk kontrol Gambar.

**Returns:**
int
### getGroupName() {#getGroupName--}
```
public String getGroupName()
```


nama grup.

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public double getHeight()
```


tinggi kontrol dalam satuan poin.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


mode run-time default Input Method Editor untuk kontrol saat menerima fokus.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


ikon khusus untuk ditampilkan sebagai penunjuk mouse bagi kontrol.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


jenis ikon yang ditampilkan sebagai penunjuk mouse bagi kontrol.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


data gambar.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


lokasi gambar kontrol relatif terhadap caption-nya.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


efek khusus kontrol.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Mendapatkan jenis kontrol ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public int getValue()
```


Menunjukkan apakah kontrol dicentang atau tidak.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


lebar kontrol dalam satuan poin.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


Menunjukkan apakah kontrol akan secara otomatis mengubah ukuran untuk menampilkan seluruh isinya.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Menunjukkan apakah kontrol dapat menerima fokus dan merespons peristiwa yang dihasilkan pengguna.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Menunjukkan apakah data dalam kontrol terkunci untuk penyuntingan.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Menunjukkan apakah kontrol transparan.

**Returns:**
boolean
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


Menunjukkan bagaimana kontrol yang ditentukan akan menampilkan nilai Null.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Pengaturan | Deskripsi                                                                                                                                     |
| True    | Kontrol akan beralih melalui status untuk nilai Ya, Tidak, dan Null. Kontrol muncul redup (abu-abu) ketika properti Value-nya diatur ke Null. |
| False   | (Default) Kontrol akan beralih melalui status untuk nilai Ya dan Tidak. Nilai Null ditampilkan seolah-olah itu adalah nilai Tidak.                           |

|

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Menunjukkan apakah isi kontrol secara otomatis membungkus pada akhir baris.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


Untuk deskripsi properti ini, silakan lihat [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | char |  |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Untuk deskripsi properti ini, silakan lihat [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Untuk deskripsi properti ini, silakan lihat [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Untuk deskripsi properti ini, silakan lihat [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Untuk deskripsi properti ini, silakan lihat [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGroupName(String value) {#setGroupName-java.lang.String-}
```
public void setGroupName(String value)
```


Untuk deskripsi properti ini, silakan lihat [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Untuk deskripsi properti ini, silakan lihat [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Untuk deskripsi properti ini, silakan lihat [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Untuk deskripsi properti ini, silakan lihat [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Untuk deskripsi properti ini, silakan lihat [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Untuk deskripsi properti ini, silakan lihat [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

