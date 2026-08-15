---
title: DataColumn
second_title: Aspose.Diagram for Java API 참조
description: Visio 사용자 인터페이스의 외부 데이터 창에 데이터 열이 표시되는 방식을 정의하고, 데이터 유형 및 서식을 정의하여 열의 데이터를 지정합니다.
type: docs
weight: 108
url: /ko/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Visio 사용자 인터페이스의 외부 데이터 창에 데이터 열이 표시되는 방식을 정의하고, 데이터 유형 및 서식을 정의하여 열의 데이터를 지정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DataColumn()](#DataColumn--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | 데이터 열의 캘린더 ID. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | 데이터 열의 외부 이름. |
| [getCurrency()](#getCurrency--) | 데이터 열의 통화 ID. |
| [getDataType()](#getDataType--) | 데이터 열의 데이터 유형. |
| [getDegree()](#getDegree--) | 단위의 차수(거듭제곱)를 지정합니다. 예: 제곱 또는 세제곱. |
| [getDisplayOrder()](#getDisplayOrder--) | 외부 데이터 창에서 데이터 열의 표시 위치를 정의합니다. 가장 왼쪽 열(0)부터 가장 오른쪽 열(최대값)까지. |
| [getDisplayWidth()](#getDisplayWidth--) | 외부 데이터 창에서 데이터 열의 너비. |
| [getHyperlink()](#getHyperlink--) | 데이터에 연결된 도형에서 데이터 열이 하이퍼링크를 생성하는지 여부. |
| [getLabel()](#getLabel--) | 데이터 열의 레이블. |
| [getLangID()](#getLangID--) | 데이터 열의 언어 ID |
| [getMapped()](#getMapped--) | 열이 외부 데이터 창에 표시되는지 여부를 지정합니다. |
| [getName()](#getName--) | 데이터 열의 내부 이름. |
| [getOrigLabel()](#getOrigLabel--) | 기본 ADO 인터페이스에 의해 Visio에 반환되는 열 레이블입니다. |
| [getUnitType()](#getUnitType--) | 데이터 열에 있는 데이터의 단위 유형입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | 이 속성에 대한 설명은 \{@link DataColumn\#(getCalendar() & 0xFFFF)\}을(를) 참조하십시오. |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | 이 속성에 대한 설명은 [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)을(를) 참조하십시오. |
| [setCurrency(int value)](#setCurrency-int-) | 이 속성에 대한 설명은 \{@link DataColumn\#(getCurrency() & 0xFFFF)\}을(를) 참조하십시오. |
| [setDataType(int value)](#setDataType-int-) | 이 속성에 대한 설명은 \{@link DataColumn\#(getDataType() & 0xFFFF)\}을(를) 참조하십시오. |
| [setDegree(long value)](#setDegree-long-) | 이 속성에 대한 설명은 [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)을(를) 참조하십시오. |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | 이 속성에 대한 설명은 [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)을(를) 참조하십시오. |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | 이 속성에 대한 설명은 [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)을(를) 참조하십시오. |
| [setHyperlink(int value)](#setHyperlink-int-) | 이 속성에 대한 설명은 [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)을(를) 참조하십시오. |
| [setLabel(String value)](#setLabel-java.lang.String-) | 이 속성에 대한 설명은 [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)을(를) 참조하십시오. |
| [setLangID(long value)](#setLangID-long-) | 이 속성에 대한 설명은 [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)을(를) 참조하십시오. |
| [setMapped(int value)](#setMapped-int-) | 이 속성에 대한 설명은 [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/datacolumn\#getName--)을(를) 참조하십시오. |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | 이 속성에 대한 설명은 [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)을(를) 참조하십시오. |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | 이 속성에 대한 설명은 [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
```


생성자.

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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


데이터 열의 캘린더 ID.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


데이터 열의 외부 이름입니다. 외부 데이터 창의 헤더와 데이터 그래픽의 레이블에 표시됩니다.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


데이터 열의 통화 ID.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


데이터 열의 데이터 유형.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


단위의 차수(거듭제곱)를 지정합니다. 예를 들어 제곱 또는 세제곱입니다. 기본값(속성 없음)은 1입니다.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


외부 데이터 창에서 데이터 열의 표시 위치를 정의합니다. 가장 왼쪽 열(0)부터 가장 오른쪽 열(최대값)까지.

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


외부 데이터 창에서 데이터 열의 너비.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


데이터에 연결된 도형에서 데이터 열이 하이퍼링크를 생성하는지 여부.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


데이터 열의 레이블.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


데이터 열의 언어 ID

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


열이 외부 데이터 창에 표시되는지 여부를 지정합니다. 열이 표시되려면 True(1), 표시되지 않으려면 false(0)입니다. 기본값(속성 없음)은 열이 표시되는 것입니다.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


데이터 열의 내부 이름입니다. 도형이 데이터 행에 연결될 때 도형에 추가되는 shape-data 항목(사용자 정의 속성)의 행 이름으로 사용됩니다.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


기본 ADO 인터페이스에 의해 Visio에 반환되는 열 레이블입니다.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


데이터 열에 있는 데이터의 단위 유형입니다.

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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


이 속성에 대한 설명은 \{@link DataColumn\#(getCalendar() & 0xFFFF)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


이 속성에 대한 설명은 [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


이 속성에 대한 설명은 \{@link DataColumn\#(getCurrency() & 0xFFFF)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


이 속성에 대한 설명은 \{@link DataColumn\#(getDataType() & 0xFFFF)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


이 속성에 대한 설명은 [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


이 속성에 대한 설명은 [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


이 속성에 대한 설명은 [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


이 속성에 대한 설명은 [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


이 속성에 대한 설명은 [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


이 속성에 대한 설명은 [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


이 속성에 대한 설명은 [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/datacolumn\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


이 속성에 대한 설명은 [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


이 속성에 대한 설명은 [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

