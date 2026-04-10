---
title: Para
second_title: Referensi API Aspose.Diagram untuk Java
description: Berisi elemen pemformatan paragraf untuk teks bentuk seperti indentasi, spasi baris, bullet, dan perataan horizontal paragraf.
type: docs
weight: 274
url: /id/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Berisi elemen pemformatan paragraf untuk teks bentuk, seperti indentasi, spasi baris, bullet, dan perataan horizontal paragraf.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Para()](#Para--) | Konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Membuat salinan mendalam dari instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Menentukan gaya bullet. |
| [getBulletFont()](#getBulletFont--) | Mewakili nomor font yang digunakan untuk memformat teks ketika string bullet khusus ditentukan dan nilai dalam elemen Bullet tidak nol. |
| [getBulletFontSize()](#getBulletFontSize--) | Menentukan ukuran bullet. |
| [getBulletStr()](#getBulletStr--) | \"Digunakan untuk membuat gaya bullet khusus. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. |
| [getFlags()](#getFlags--) | Menunjukkan apakah arah teks dari kiri ke kanan atau dari kanan ke kiri. |
| [getHorzAlign()](#getHorzAlign--) | Menentukan perataan horizontal teks dalam blok teks bentuk. |
| [getIX()](#getIX--) | Indeks berbasis nol dari elemen dalam elemen induknya. |
| [getIndFirst()](#getIndFirst--) | Menentukan jarak baris pertama setiap paragraf dalam blok teks bentuk diindentasi dari indentasi kiri paragraf. |
| [getIndLeft()](#getIndLeft--) | Menentukan jarak semua baris teks dalam paragraf diindentasi dari margin kiri blok teks. |
| [getIndRight()](#getIndRight--) | Menentukan jarak semua baris teks dalam paragraf diindentasi dari margin kanan blok teks. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Menentukan apakah font bullet harus dilokalkan (diterjemahkan ke bahasa lain). |
| [getSpAfter()](#getSpAfter--) | Menentukan jumlah ruang yang disisipkan setelah setiap paragraf dalam blok teks bentuk. |
| [getSpBefore()](#getSpBefore--) | Menentukan jumlah ruang yang disisipkan sebelum setiap paragraf dalam blok teks bentuk. |
| [getSpLine()](#getSpLine--) | Menentukan jarak antara satu baris teks dengan baris berikutnya, di mana 100% adalah tinggi satu baris teks. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Mewakili jarak antara baris pertama paragraf dan bullet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | Untuk deskripsi properti ini, silakan lihat [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | Untuk deskripsi properti ini, silakan lihat [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | Untuk deskripsi properti ini, silakan lihat [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | Untuk deskripsi properti ini, silakan lihat [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | Untuk deskripsi properti ini, silakan lihat [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | Untuk deskripsi properti ini, silakan lihat [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Membuat salinan mendalam dari instance ini.

**Returns:**
java.lang.Object -
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Menentukan gaya bullet.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Mewakili nomor font yang digunakan untuk memformat teks ketika string bullet khusus ditentukan dan nilai dalam elemen Bullet tidak nol.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Menentukan ukuran bullet.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Digunakan untuk membuat gaya bullet khusus. Masukkan gaya sebagai string (dalam tanda kutip). Misalnya, Anda dapat memasukkan string, ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Bendera yang menunjukkan apakah elemen telah dihapus secara lokal. Nilai 1 menunjukkan bahwa elemen tersebut dihapus secara lokal.

**Returns:**
int
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Menunjukkan apakah arah teks dari kiri ke kanan atau dari kanan ke kiri.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Menentukan perataan horizontal teks dalam blok teks bentuk.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


Indeks berbasis nol dari elemen dalam elemen induknya.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Menentukan jarak baris pertama setiap paragraf dalam blok teks bentuk diindentasi dari indent kiri paragraf. Nilai ini independen dari skala gambar. Jika gambar diskalakan, indent baris pertama tetap sama.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Menentukan jarak semua baris teks dalam paragraf diindentasi dari margin kiri blok teks. Nilai ini independen dari skala gambar. Jika gambar diskalakan, indent kiri tetap sama.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Menentukan jarak semua baris teks dalam paragraf diindentasi dari margin kanan blok teks. Nilai ini independen dari skala gambar. Jika gambar diskalakan, indentasi kanan tetap sama.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Menentukan apakah font bullet harus dilokalkan (diterjemahkan ke bahasa lain).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Menentukan jumlah ruang yang disisipkan setelah setiap paragraf dalam blok teks bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Menentukan jumlah ruang yang disisipkan sebelum setiap paragraf dalam blok teks bentuk.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Menentukan jarak antara satu baris teks dengan baris berikutnya, di mana 100% adalah tinggi satu baris teks.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Mewakili jarak antara baris pertama paragraf dan bullet.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


Untuk deskripsi properti ini, silakan lihat [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


Untuk deskripsi properti ini, silakan lihat [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Untuk deskripsi properti ini, silakan lihat [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


Untuk deskripsi properti ini, silakan lihat [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


Untuk deskripsi properti ini, silakan lihat [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Untuk deskripsi properti ini, silakan lihat [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


Untuk deskripsi properti ini, silakan lihat [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

