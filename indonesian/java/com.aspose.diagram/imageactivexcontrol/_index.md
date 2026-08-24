---
title: ImageActiveXControl
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili kontrol gambar.
type: docs
weight: 197
url: /id/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

Mewakili kontrol gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | warna ole latar belakang. |
| [getBorderOleColor()](#getBorderOleColor--) | warna ole latar belakang. |
| [getBorderStyle()](#getBorderStyle--) | tipe batas yang digunakan oleh kontrol. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | data biner kontrol. |
| [getForeOleColor()](#getForeOleColor--) | warna ole latar depan. |
| [getHeight()](#getHeight--) | tinggi kontrol dalam satuan poin. |
| [getIMEMode()](#getIMEMode--) | mode run-time default Input Method Editor untuk kontrol saat menerima fokus. |
| [getMouseIcon()](#getMouseIcon--) | ikon khusus untuk ditampilkan sebagai penunjuk mouse bagi kontrol. |
| [getMousePointer()](#getMousePointer--) | jenis ikon yang ditampilkan sebagai penunjuk mouse bagi kontrol. |
| [getPicture()](#getPicture--) | data gambar. |
| [getPictureAlignment()](#getPictureAlignment--) | penyelarasan gambar di dalam Form atau Image. |
| [getPictureSizeMode()](#getPictureSizeMode--) | cara menampilkan gambar. |
| [getSpecialEffect()](#getSpecialEffect--) | efek khusus kontrol. |
| [getType()](#getType--) | Mendapatkan jenis kontrol ActiveX. |
| [getWidth()](#getWidth--) | lebar kontrol dalam satuan poin. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Menunjukkan apakah kontrol akan secara otomatis mengubah ukuran untuk menampilkan seluruh isinya. |
| [isEnabled()](#isEnabled--) | Menunjukkan apakah kontrol dapat menerima fokus dan merespons peristiwa yang dihasilkan pengguna. |
| [isLocked()](#isLocked--) | Menunjukkan apakah data dalam kontrol terkunci untuk penyuntingan. |
| [isTiled()](#isTiled--) | Menunjukkan apakah gambar ditile di seluruh latar belakang. |
| [isTransparent()](#isTransparent--) | Menunjukkan apakah kontrol transparan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | For untuk deskripsi properti ini, silakan lihat [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Untuk deskripsi properti ini, silakan lihat [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | For untuk deskripsi properti ini, silakan lihat [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | For untuk deskripsi properti ini, silakan lihat [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Untuk deskripsi properti ini, silakan lihat [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Untuk deskripsi properti ini, silakan lihat [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Untuk deskripsi properti ini, silakan lihat [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Untuk deskripsi properti ini, silakan lihat [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Untuk deskripsi properti ini, silakan lihat [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Untuk deskripsi properti ini, silakan lihat [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Untuk deskripsi properti ini, silakan lihat [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | For untuk deskripsi properti ini, silakan lihat [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--) |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | Untuk deskripsi properti ini, silakan lihat [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | Untuk deskripsi properti ini, silakan lihat [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Untuk deskripsi properti ini, silakan lihat [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) |
| [setTiled(boolean value)](#setTiled-boolean-) | Untuk deskripsi properti ini, silakan lihat [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Untuk deskripsi properti ini, silakan lihat [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Untuk deskripsi properti ini, silakan lihat [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


warna ole latar belakang.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


warna ole latar belakang.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


tipe batas yang digunakan oleh kontrol.

**Returns:**
int
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
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


penyelarasan gambar di dalam Form atau Image.

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


cara menampilkan gambar.

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
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Menunjukkan apakah gambar ditile di seluruh latar belakang.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Menunjukkan apakah kontrol transparan.

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




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


For untuk deskripsi properti ini, silakan lihat [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)

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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


For untuk deskripsi properti ini, silakan lihat [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


For untuk deskripsi properti ini, silakan lihat [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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


For untuk deskripsi properti ini, silakan lihat [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


Untuk deskripsi properti ini, silakan lihat [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Untuk deskripsi properti ini, silakan lihat [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Untuk deskripsi properti ini, silakan lihat [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Untuk deskripsi properti ini, silakan lihat [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

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

