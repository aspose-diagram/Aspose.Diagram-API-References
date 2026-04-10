---
title: DataRecordSet
second_title: Aspose.Diagram for Java API 참조
description: Microsoft Visio에서 데이터베이스에서 쿼리된 데이터를 저장하고, 형식을 새로 고치며, 노출합니다.
type: docs
weight: 113
url: /ko/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Microsoft Visio에서 데이터베이스에 질의한 데이터를 저장, 서식 지정, 새로 고침 및 노출합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | ADO 레코드셋에 대한 ADO 클래식 XML 스키마에 부합하고 데이터 레코드셋의 데이터를 설명하는 XML을 포함합니다. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | 사용자 인터페이스에서 수행된 마지막 성공적인 자동 연결 작업의 도형 데이터 항목과 상위 DataRecordset 요소의 열을 비교하는 규칙을 정의합니다. |
| [getChecksum()](#getChecksum--) | Visio에서 생성된 체크섬 값이며, data-recordset 속성을 기반으로 합니다. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 데이터 소스에서 데이터를 쿼리하는 데 사용되는 명령 문자열입니다. |
| [getConnectionID()](#getConnectionID--) | 연관된 DataConnection 객체의 연결 ID입니다. |
| [getDataColumns()](#getDataColumns--) | 데이터 레코드셋에 포함된 모든 DataColumn 요소를 포함합니다. |
| [getID()](#getID--) | 문서 내에서 고유한 데이터 레코드셋 ID입니다. |
| [getName()](#getName--) | 데이터 레코드셋의 표시(또는 \"친숙한\") 이름입니다. |
| [getNextRowID()](#getNextRowID--) | 다음 사용 가능한 Visio 행 ID입니다. |
| [getOptions()](#getOptions--) | 데이터 레코드셋에 적용할 옵션입니다. |
| [getPrimaryKeys()](#getPrimaryKeys--) | 데이터 레코드셋에서 하나 이상의 기본 키 열을 식별합니다. |
| [getRefreshConflicts()](#getRefreshConflicts--) | 데이터 레코드셋이 새로 고쳐진 후 충돌이 발생한 모양에 연결된 데이터 레코드셋의 행을 나타냅니다. |
| [getRefreshInterval()](#getRefreshInterval--) | Visio가 데이터 레코드셋을 자동으로 새로 고치는 빈도(분)입니다. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | 데이터 조정 사용자 인터페이스를 비활성화해야 하는지 여부입니다. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | 데이터 레코드셋이 새로 고쳐질 때 데이터에 연결된 모양의 모양 데이터 항목에 대한 사용자 변경을 덮어쓸지 여부입니다. |
| [getReplaceLinks()](#getReplaceLinks--) | 모양을 복사하거나 잘라낼 때 shape-data 링크가 처리되는 방식을 정의합니다. 대상 모양의 기존 링크를 교체하려면 1, 기존 링크를 유지하려면 0을 사용합니다. |
| [getRowMaps()](#getRowMaps--) | 데이터 레코드셋 행을 모양에 매핑합니다. |
| [getRowOrder()](#getRowOrder--) | 데이터 레코드셋의 행 순서를 기본 키로 사용할지 여부입니다. |
| [getTimeRefreshed()](#getTimeRefreshed--) | 데이터 레코드셋이 마지막으로 새로 고쳐진 날짜와 시간입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | 연결된 (XML 기반이 아닌) DataRecordset과 연관된 쿼리 문자열을 실행하고, 쿼리에서 반환된 데이터 소스의 새 데이터로 연결된 모양을 업데이트합니다. |
| [setADOData(String value)](#setADOData-java.lang.String-) | 이 속성에 대한 설명은 [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)을(를) 참조하십시오. |
| [setChecksum(long value)](#setChecksum-long-) | 이 속성에 대한 설명은 \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}을(를) 참조하십시오. |
| [setCommand(String value)](#setCommand-java.lang.String-) | 이 속성에 대한 설명은 [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)을(를) 참조하십시오. |
| [setConnectionID(long value)](#setConnectionID-long-) | 이 속성에 대한 설명은 \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}을(를) 참조하십시오. |
| [setID(long value)](#setID-long-) | 이 속성에 대한 설명은 \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/datarecordset\#getName--)을(를) 참조하십시오. |
| [setNextRowID(long value)](#setNextRowID-long-) | 이 속성에 대한 설명은 \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}을(를) 참조하십시오. |
| [setOptions(int value)](#setOptions-int-) | 이 속성에 대한 설명은 [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)을(를) 참조하십시오. |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | 이 속성에 대한 설명은 \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}을(를) 참조하십시오. |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | 이 속성에 대한 설명은 [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)을(를) 참조하십시오. |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | 이 속성에 대한 설명은 [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)을(를) 참조하십시오. |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | 이 속성에 대한 설명은 [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)을(를) 참조하십시오. |
| [setRowOrder(int value)](#setRowOrder-int-) | 이 속성에 대한 설명은 [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)을(를) 참조하십시오. |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | 이 속성에 대한 설명은 [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
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
### getADOData() {#getADOData--}
```
public String getADOData()
```


ADO 레코드셋에 대한 ADO 클래식 XML 스키마에 부합하고 데이터 레코드셋의 데이터를 설명하는 XML을 포함합니다.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


사용자 인터페이스에서 수행된 마지막 성공적인 자동 연결 작업의 도형 데이터 항목과 상위 DataRecordset 요소의 열을 비교하는 규칙을 정의합니다.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Visio에서 생성된 체크섬 값이며 data-recordset 속성을 기반으로 합니다. 이 속성을 0으로 설정하십시오; Visio는 런타임에 이 값을 다시 계산합니다.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


데이터 소스에서 데이터를 쿼리하는 데 사용되는 명령 문자열입니다.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


연관된 DataConnection 객체의 연결 ID입니다. XML 데이터 소스에는 존재하지 않습니다.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


데이터 레코드셋에 포함된 모든 DataColumn 요소를 포함합니다.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


문서 내에서 고유한 데이터 레코드셋 ID입니다.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


데이터 레코드셋의 표시(또는 \"친숙한\") 이름입니다.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


다음 사용 가능한 Visio 행 ID입니다.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


데이터 레코드셋에 적용할 옵션입니다. 가능한 값은 아래 표에 표시된 하나 이상의 옵션을 조합한 것이 될 수 있습니다.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


데이터 레코드셋에서 하나 이상의 기본 키 열을 식별합니다.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


데이터 레코드셋이 새로 고쳐진 후 충돌이 발생한 도형에 연결된 레코드셋 행을 나타냅니다. RowID - 데이터 레코드셋이 새로 고쳐진 후 충돌이 발생한 도형에 연결된 레코드셋 행을 나타냅니다. ShapeID - 충돌에 연관된 도형의 Shape ID입니다. PageID - 충돌에 연관된 도형의 Page ID입니다.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Visio가 데이터 레코드셋을 자동으로 새로 고치는 빈도(분)입니다. 이 값은 1 이상이어야 합니다.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


데이터 조정 사용자 인터페이스를 비활성화할지 여부입니다. 사용자 인터페이스(UI)를 비활성화하려면 True(1)를, 활성화하려면 False(0)를 사용하십시오.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


데이터 레코드셋이 새로 고쳐질 때 데이터에 연결된 모양의 모양 데이터 항목에 대한 사용자 변경을 덮어쓸지 여부입니다.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


도형을 복사하거나 잘라낼 때 shape-data 링크가 어떻게 처리되는지를 정의합니다. 대상 도형의 기존 링크를 교체하려면 1, 기존 링크를 유지하려면 0을 사용합니다. 이 속성이 없으면 Visio는 복사 또는 잘라내기 시 링크를 교체할지 사용자에게 묻습니다.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


데이터 레코드셋 행을 도형에 매핑합니다. RowID - 데이터 레코드셋 내에서 고유한 행의 Row ID입니다. ShapeID - RowID로 식별된 데이터 레코드셋 행의 데이터에 연결된 도형의 Shape ID입니다. PageID - RowID로 식별된 데이터 레코드셋 행의 데이터에 연결된 도형의 Page ID입니다.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


데이터 레코드셋의 행 순서를 기본 키로 사용할지 여부입니다. 행 ID가 행 순서에 의해 결정되면 True(1), 데이터 레코드셋의 기본 키 열 값에 의해 결정되면 False(0)를 사용합니다.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


데이터 레코드셋이 마지막으로 새로 고쳐진 날짜와 시간입니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


연결된 (XML 기반이 아닌) DataRecordset과 연관된 쿼리 문자열을 실행하고, 쿼리에서 반환된 데이터 소스의 새 데이터로 연결된 모양을 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| connectionType | int | 연결에 사용될 공급자 유형은 Aspose.Diagram.Manipulation.DataConnectionType입니다. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


이 속성에 대한 설명은 [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


이 속성에 대한 설명은 \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


이 속성에 대한 설명은 [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


이 속성에 대한 설명은 \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


이 속성에 대한 설명은 \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/datarecordset\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


이 속성에 대한 설명은 \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


이 속성에 대한 설명은 [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


이 속성에 대한 설명은 \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


이 속성에 대한 설명은 [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


이 속성에 대한 설명은 [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


이 속성에 대한 설명은 [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


이 속성에 대한 설명은 [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


이 속성에 대한 설명은 [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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

