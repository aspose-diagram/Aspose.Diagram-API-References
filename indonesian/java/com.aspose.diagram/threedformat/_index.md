---
title: ThreeDFormat
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili pemformatan tiga dimensi sebuah bentuk.
type: docs
weight: 406
url: /id/java/com.aspose.diagram/threedformat/
---

**Inheritance:**
java.lang.Object
```
public class ThreeDFormat
```

Mewakili pemformatan tiga dimensi sebuah bentuk.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getBevelBottomHeight()](#getBevelBottomHeight--) | Menentukan tinggi bevel bawah pada bentuk 3D. |
| [getBevelBottomType()](#getBevelBottomType--) | Menentukan jenis bevel bawaan untuk bevel bawah pada bentuk 3D |
| [getBevelBottomWidth()](#getBevelBottomWidth--) | Menentukan lebar bevel bawah pada bentuk 3D. |
| [getBevelContourColor()](#getBevelContourColor--) | Menentukan warna garis luar pada bentuk 3D |
| [getBevelContourSize()](#getBevelContourSize--) | Menentukan ketebalan garis luar pada bentuk 3D |
| [getBevelDepthColor()](#getBevelDepthColor--) | Menentukan warna ekstrusi pada bentuk 3D |
| [getBevelDepthSize()](#getBevelDepthSize--) | Menentukan kedalaman ekstrusi pada bentuk 3D |
| [getBevelLightingAngle()](#getBevelLightingAngle--) | Menentukan arah pencahayaan pada bentuk 3D. |
| [getBevelLightingType()](#getBevelLightingType--) | Menentukan jenis pencahayaan bawaan pada bentuk 3D |
| [getBevelMaterialType()](#getBevelMaterialType--) | Menentukan tampilan permukaan bawaan pada bentuk 3D |
| [getBevelTopHeight()](#getBevelTopHeight--) | Menentukan tinggi bevel atas pada bentuk 3D |
| [getBevelTopType()](#getBevelTopType--) | Menentukan jenis bevel bawaan untuk bevel atas pada bentuk 3D |
| [getBevelTopWidth()](#getBevelTopWidth--) | Menentukan lebar bevel atas pada bentuk 3D. |
| [getClass()](#getClass--) |  |
| [getDistanceFromGround()](#getDistanceFromGround--) | Menentukan jarak yang sebuah bentuk dengan properti rotasi 3D |
| [getKeepTextFlat()](#getKeepTextFlat--) | Menentukan apakah properti rotasi 3D diterapkan pada teks sebuah bentuk |
| [getPerspective()](#getPerspective--) | Menentukan sudut pandang untuk bentuk dengan properti rotasi 3D |
| [getRotationType()](#getRotationType--) | Menentukan jenis proyeksi dari properti efek sebuah bentuk. |
| [getRotationXAngle()](#getRotationXAngle--) | Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu y. |
| [getRotationYAngle()](#getRotationYAngle--) | Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu x |
| [getRotationZAngle()](#getRotationZAngle--) | Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu z. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBevelBottomHeight(DoubleValue value)](#setBevelBottomHeight-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--) |
| [setBevelBottomType(BevelType value)](#setBevelBottomType-com.aspose.diagram.BevelType-) | Untuk deskripsi properti ini, silakan lihat [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--) |
| [setBevelBottomWidth(DoubleValue value)](#setBevelBottomWidth-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--) |
| [setBevelContourColor(ColorValue value)](#setBevelContourColor-com.aspose.diagram.ColorValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--) |
| [setBevelContourSize(DoubleValue value)](#setBevelContourSize-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--) |
| [setBevelDepthColor(ColorValue value)](#setBevelDepthColor-com.aspose.diagram.ColorValue-) | For the description of this property, please see [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--) |
| [setBevelDepthSize(DoubleValue value)](#setBevelDepthSize-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--) |
| [setBevelLightingAngle(DoubleValue value)](#setBevelLightingAngle-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--) |
| [setBevelLightingType(BevelLightingType value)](#setBevelLightingType-com.aspose.diagram.BevelLightingType-) | Untuk deskripsi properti ini, silakan lihat [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--) |
| [setBevelMaterialType(BevelMaterialType value)](#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-) | Untuk deskripsi properti ini, silakan lihat [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--) |
| [setBevelTopHeight(DoubleValue value)](#setBevelTopHeight-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--) |
| [setBevelTopType(BevelType value)](#setBevelTopType-com.aspose.diagram.BevelType-) | Untuk deskripsi properti ini, silakan lihat [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--) |
| [setBevelTopWidth(DoubleValue value)](#setBevelTopWidth-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--) |
| [setDistanceFromGround(DoubleValue value)](#setDistanceFromGround-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--) |
| [setKeepTextFlat(BoolValue value)](#setKeepTextFlat-com.aspose.diagram.BoolValue-) | Untuk deskripsi properti ini, silakan lihat [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--) |
| [setPerspective(DoubleValue value)](#setPerspective-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--) |
| [setRotationType(RotationType value)](#setRotationType-com.aspose.diagram.RotationType-) | Untuk deskripsi properti ini, silakan lihat [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--) |
| [setRotationXAngle(DoubleValue value)](#setRotationXAngle-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--) |
| [setRotationYAngle(DoubleValue value)](#setRotationYAngle-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--) |
| [setRotationZAngle(DoubleValue value)](#setRotationZAngle-com.aspose.diagram.DoubleValue-) | Untuk deskripsi properti ini, silakan lihat [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objek | java.lang.Object |  |

**Returns:**
boolean -
### getBevelBottomHeight() {#getBevelBottomHeight--}
```
public DoubleValue getBevelBottomHeight()
```


Menentukan tinggi bevel bawah pada bentuk 3D.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelBottomType() {#getBevelBottomType--}
```
public BevelType getBevelBottomType()
```


Menentukan jenis bevel bawaan untuk bevel bawah pada bentuk 3D

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelBottomWidth() {#getBevelBottomWidth--}
```
public DoubleValue getBevelBottomWidth()
```


Menentukan lebar bevel bawah pada bentuk 3D.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelContourColor() {#getBevelContourColor--}
```
public ColorValue getBevelContourColor()
```


Menentukan warna garis luar pada bentuk 3D

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelContourSize() {#getBevelContourSize--}
```
public DoubleValue getBevelContourSize()
```


Menentukan ketebalan garis luar pada bentuk 3D

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelDepthColor() {#getBevelDepthColor--}
```
public ColorValue getBevelDepthColor()
```


Menentukan warna ekstrusi pada bentuk 3D

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getBevelDepthSize() {#getBevelDepthSize--}
```
public DoubleValue getBevelDepthSize()
```


Menentukan kedalaman ekstrusi pada bentuk 3D

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingAngle() {#getBevelLightingAngle--}
```
public DoubleValue getBevelLightingAngle()
```


Menentukan arah pencahayaan pada bentuk 3D.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelLightingType() {#getBevelLightingType--}
```
public BevelLightingType getBevelLightingType()
```


Menentukan jenis pencahayaan bawaan pada bentuk 3D

**Returns:**
[BevelLightingType](../../com.aspose.diagram/bevellightingtype)
### getBevelMaterialType() {#getBevelMaterialType--}
```
public BevelMaterialType getBevelMaterialType()
```


Menentukan tampilan permukaan bawaan pada bentuk 3D

**Returns:**
[BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype)
### getBevelTopHeight() {#getBevelTopHeight--}
```
public DoubleValue getBevelTopHeight()
```


Menentukan tinggi bevel atas pada bentuk 3D

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBevelTopType() {#getBevelTopType--}
```
public BevelType getBevelTopType()
```


Menentukan jenis bevel bawaan untuk bevel atas pada bentuk 3D

**Returns:**
[BevelType](../../com.aspose.diagram/beveltype)
### getBevelTopWidth() {#getBevelTopWidth--}
```
public DoubleValue getBevelTopWidth()
```


Menentukan lebar bevel atas pada bentuk 3D.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDistanceFromGround() {#getDistanceFromGround--}
```
public DoubleValue getDistanceFromGround()
```


Menentukan jarak yang sebuah bentuk dengan properti rotasi 3D

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public BoolValue getKeepTextFlat()
```


Menentukan apakah properti rotasi 3D diterapkan pada teks sebuah bentuk

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerspective() {#getPerspective--}
```
public DoubleValue getPerspective()
```


Menentukan sudut pandang untuk bentuk dengan properti rotasi 3D

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationType() {#getRotationType--}
```
public RotationType getRotationType()
```


Menentukan jenis proyeksi dari properti efek sebuah bentuk.

**Returns:**
[RotationType](../../com.aspose.diagram/rotationtype)
### getRotationXAngle() {#getRotationXAngle--}
```
public DoubleValue getRotationXAngle()
```


Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu y.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationYAngle() {#getRotationYAngle--}
```
public DoubleValue getRotationYAngle()
```


Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu x

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRotationZAngle() {#getRotationZAngle--}
```
public DoubleValue getRotationZAngle()
```


Menentukan sudut rotasi berlawanan arah jarum jam sebuah bentuk di sekitar sumbu z.

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




### setBevelBottomHeight(DoubleValue value) {#setBevelBottomHeight-com.aspose.diagram.DoubleValue-}
```
public void setBevelBottomHeight(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelBottomHeight()](../../com.aspose.diagram/threedformat\#getBevelBottomHeight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelBottomType(BevelType value) {#setBevelBottomType-com.aspose.diagram.BevelType-}
```
public void setBevelBottomType(BevelType value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelBottomType()](../../com.aspose.diagram/threedformat\#getBevelBottomType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelBottomWidth(DoubleValue value) {#setBevelBottomWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelBottomWidth(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelBottomWidth()](../../com.aspose.diagram/threedformat\#getBevelBottomWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelContourColor(ColorValue value) {#setBevelContourColor-com.aspose.diagram.ColorValue-}
```
public void setBevelContourColor(ColorValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelContourColor()](../../com.aspose.diagram/threedformat\#getBevelContourColor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelContourSize(DoubleValue value) {#setBevelContourSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelContourSize(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelContourSize()](../../com.aspose.diagram/threedformat\#getBevelContourSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelDepthColor(ColorValue value) {#setBevelDepthColor-com.aspose.diagram.ColorValue-}
```
public void setBevelDepthColor(ColorValue value)
```


For the description of this property, please see [getBevelDepthColor()](../../com.aspose.diagram/threedformat\#getBevelDepthColor--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setBevelDepthSize(DoubleValue value) {#setBevelDepthSize-com.aspose.diagram.DoubleValue-}
```
public void setBevelDepthSize(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelDepthSize()](../../com.aspose.diagram/threedformat\#getBevelDepthSize--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingAngle(DoubleValue value) {#setBevelLightingAngle-com.aspose.diagram.DoubleValue-}
```
public void setBevelLightingAngle(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelLightingAngle()](../../com.aspose.diagram/threedformat\#getBevelLightingAngle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelLightingType(BevelLightingType value) {#setBevelLightingType-com.aspose.diagram.BevelLightingType-}
```
public void setBevelLightingType(BevelLightingType value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelLightingType()](../../com.aspose.diagram/threedformat\#getBevelLightingType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BevelLightingType](../../com.aspose.diagram/bevellightingtype) |  |

### setBevelMaterialType(BevelMaterialType value) {#setBevelMaterialType-com.aspose.diagram.BevelMaterialType-}
```
public void setBevelMaterialType(BevelMaterialType value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelMaterialType()](../../com.aspose.diagram/threedformat\#getBevelMaterialType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BevelMaterialType](../../com.aspose.diagram/bevelmaterialtype) |  |

### setBevelTopHeight(DoubleValue value) {#setBevelTopHeight-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopHeight(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelTopHeight()](../../com.aspose.diagram/threedformat\#getBevelTopHeight--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBevelTopType(BevelType value) {#setBevelTopType-com.aspose.diagram.BevelType-}
```
public void setBevelTopType(BevelType value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelTopType()](../../com.aspose.diagram/threedformat\#getBevelTopType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BevelType](../../com.aspose.diagram/beveltype) |  |

### setBevelTopWidth(DoubleValue value) {#setBevelTopWidth-com.aspose.diagram.DoubleValue-}
```
public void setBevelTopWidth(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getBevelTopWidth()](../../com.aspose.diagram/threedformat\#getBevelTopWidth--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDistanceFromGround(DoubleValue value) {#setDistanceFromGround-com.aspose.diagram.DoubleValue-}
```
public void setDistanceFromGround(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getDistanceFromGround()](../../com.aspose.diagram/threedformat\#getDistanceFromGround--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setKeepTextFlat(BoolValue value) {#setKeepTextFlat-com.aspose.diagram.BoolValue-}
```
public void setKeepTextFlat(BoolValue value)
```


Untuk deskripsi properti ini, silakan lihat [getKeepTextFlat()](../../com.aspose.diagram/threedformat\#getKeepTextFlat--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerspective(DoubleValue value) {#setPerspective-com.aspose.diagram.DoubleValue-}
```
public void setPerspective(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getPerspective()](../../com.aspose.diagram/threedformat\#getPerspective--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationType(RotationType value) {#setRotationType-com.aspose.diagram.RotationType-}
```
public void setRotationType(RotationType value)
```


Untuk deskripsi properti ini, silakan lihat [getRotationType()](../../com.aspose.diagram/threedformat\#getRotationType--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RotationType](../../com.aspose.diagram/rotationtype) |  |

### setRotationXAngle(DoubleValue value) {#setRotationXAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationXAngle(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getRotationXAngle()](../../com.aspose.diagram/threedformat\#getRotationXAngle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationYAngle(DoubleValue value) {#setRotationYAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationYAngle(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getRotationYAngle()](../../com.aspose.diagram/threedformat\#getRotationYAngle--)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRotationZAngle(DoubleValue value) {#setRotationZAngle-com.aspose.diagram.DoubleValue-}
```
public void setRotationZAngle(DoubleValue value)
```


Untuk deskripsi properti ini, silakan lihat [getRotationZAngle()](../../com.aspose.diagram/threedformat\#getRotationZAngle--)

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

