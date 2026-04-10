---
title: ForeignData
second_title: Aspose.Diagram for Java API 참조
description: Windows 메타파일 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME Multipurpose Internet Mail Extensions 인코딩 BLOB을 포함합니다.
type: docs
weight: 164
url: /ko/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | 이 속성은 외부 데이터가 DIB, JPG, PNG, TIFF 또는 GIF 파일과 같은 래스터 기반 외부 객체인 경우에만 의미가 있습니다. |
| [getCompressionType()](#getCompressionType--) | 이 속성은 외부 데이터가 DIB, JPG, PNG, TIFF 또는 GIF 파일과 같은 래스터 기반 외부 객체인 경우에만 의미가 있습니다. |
| [getExtentX()](#getExtentX--) | 이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. |
| [getExtentY()](#getExtentY--) | 이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. |
| [getForeignType()](#getForeignType--) | 데이터 유형. |
| [getImageData()](#getImageData--) | OLE 객체의 이미지를 바이트 배열로 나타냅니다. |
| [getMappingMode()](#getMappingMode--) | 이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. |
| [getObjectData()](#getObjectData--) | 임베드된 OLE 객체 데이터를 바이트 배열로 나타냅니다. |
| [getObjectHeight()](#getObjectHeight--) | 이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | 연결된 OLE 객체에 대한 원본 파일의 전체 이름을 반환합니다. |
| [getObjectType()](#getObjectType--) | ForeignType 속성이 "Object"인 경우, ForeignData 요소에도 ObjectType 속성이 있어야 합니다. |
| [getObjectWidth()](#getObjectWidth--) | 이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다. |
| [getShowAsIcon()](#getShowAsIcon--) | 이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다. |
| [getValue()](#getValue--) | Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | 이 속성에 대한 설명은 [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)을(를) 참조하십시오. |
| [setCompressionType(int value)](#setCompressionType-int-) | 이 속성에 대한 설명은 [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)을(를) 참조하십시오. |
| [setExtentX(double value)](#setExtentX-double-) | 이 속성에 대한 설명은 [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)을(를) 참조하십시오. |
| [setExtentY(double value)](#setExtentY-double-) | 이 속성에 대한 설명은 [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)을(를) 참조하십시오. |
| [setForeignType(int value)](#setForeignType-int-) | 이 속성에 대한 설명은 [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)을(를) 참조하십시오. |
| [setImageData(byte[] value)](#setImageData-byte---) | 이 속성에 대한 설명은 [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)을(를) 참조하십시오. |
| [setMappingMode(int value)](#setMappingMode-int-) | 이 속성에 대한 설명은 [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)을(를) 참조하십시오. |
| [setObjectData(byte[] value)](#setObjectData-byte---) | 이 속성에 대한 설명은 [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)을(를) 참조하십시오. |
| [setObjectHeight(double value)](#setObjectHeight-double-) | 이 속성에 대한 설명은 [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)을(를) 참조하십시오. |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | 이 속성에 대한 설명은 [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)을(를) 참조하십시오. |
| [setObjectType(int value)](#setObjectType-int-) | 이 속성에 대한 설명은 [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)을(를) 참조하십시오. |
| [setObjectWidth(double value)](#setObjectWidth-double-) | 이 속성에 대한 설명은 [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)을(를) 참조하십시오. |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | 이 속성에 대한 설명은 [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)을(를) 참조하십시오. |
| [setValue(byte[] value)](#setValue-byte---) | 이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
java.lang.Object -
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
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


이 속성은 외부 데이터가 DIB, JPG, PNG, TIFF 또는 GIF 파일과 같은 래스터 기반 외부 객체인 경우에만 의미가 있습니다. 값은 파일에 적용된 압축 수준을 나타냅니다. 압축 수준은 백분율의 백분의 일 단위로 측정됩니다.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


이 속성은 외부 데이터가 DIB, JPG, PNG, TIFF 또는 GIF 파일과 같은 래스터 기반 외부 객체인 경우에만 의미가 있습니다. 값은 파일에 적용된 압축 유형을 나타냅니다.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. 값은 메타파일의 가로 범위를 나타냅니다.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. 값은 메타파일의 세로 범위를 나타냅니다.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


데이터 유형.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


OLE 객체의 이미지를 바이트 배열로 나타냅니다.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


이 속성은 외부 데이터가 메타파일인 경우에만 의미가 있습니다. 값은 메타파일의 매핑 모드를 나타냅니다.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


임베드된 OLE 객체 데이터를 바이트 배열로 나타냅니다.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다. 값은 페이지 단위로 객체의 높이를 나타냅니다.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


연결된 OLE 객체에 대한 원본 파일의 전체 이름을 반환합니다. 파일 유형이 OleFileType.Unknown인 경우에만 전체 이름 설정을 지원합니다. 예: wav 파일, avi 파일 등.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


ForeignType 속성이 "Object"인 경우, ForeignData 요소에도 ObjectType 속성이 있어야 합니다.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다. 값은 페이지 단위로 객체의 너비를 나타냅니다.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


이 속성은 외부 데이터가 OLE2 임베디드 객체인 경우에만 의미가 있습니다.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다.

**Returns:**
byte[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


이 속성에 대한 설명은 [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


이 속성에 대한 설명은 [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


이 속성에 대한 설명은 [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


이 속성에 대한 설명은 [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


이 속성에 대한 설명은 [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


이 속성에 대한 설명은 [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


이 속성에 대한 설명은 [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


이 속성에 대한 설명은 [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


이 속성에 대한 설명은 [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


이 속성에 대한 설명은 [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


이 속성에 대한 설명은 [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


이 속성에 대한 설명은 [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


이 속성에 대한 설명은 [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

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

