---
title: VbaProjectReferenceCollection
second_title: Aspose.Diagram for Java API 참조
description: VBA 프로젝트의 모든 참조를 나타냅니다.
type: docs
weight: 435
url: /ko/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

VBA 프로젝트의 모든 참조를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | CollectionBase 인스턴스에 항목을 추가합니다. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | twiddled 타입 라이브러리와 해당 확장 타입 라이브러리에 대한 참조를 추가합니다. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | 외부 VBA 프로젝트에 대한 참조를 추가합니다. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Automation 타입 라이브러리에 대한 참조를 추가합니다. |
| [clear()](#clear--) | CollectionBase 인스턴스에서 모든 객체를 제거합니다. |
| [contains(Object o)](#contains-java.lang.Object-) | 인스턴스가 이 객체를 포함하는지 여부를 반환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | 인덱스로 목록에서 참조를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | CollectionBase 인스턴스에 포함된 요소 수를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | CollectionBase 인스턴스에서 특정 항목의 인덱스를 결정합니다. |
| [iterator()](#iterator--) | CollectionBase 인스턴스를 순회하는 열거자를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 항목을 제거합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


CollectionBase 인스턴스에 항목을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | CollectionBase 인스턴스에 추가할 객체입니다. |

**Returns:**
int - 새 요소가 삽입된 위치입니다.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


twiddled 타입 라이브러리와 해당 확장 타입 라이브러리에 대한 참조를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 참조의 이름. |
| libid | java.lang.String | Automation 타입 라이브러리의 식별자. |
| twiddledlibid | java.lang.String | twiddled 타입 라이브러리의 식별자 |
| extendedLibid | java.lang.String | 확장된 타입 라이브러리의 식별자 |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


외부 VBA 프로젝트에 대한 참조를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 참조의 이름. |
| absoluteLibid | java.lang.String | 절대 경로를 가진 참조된 VBA 프로젝트\u9225\u6a9a 식별자. |
| relativeLibid | java.lang.String | 상대 경로를 가진 참조된 VBA 프로젝트\u9225\u6a9a 식별자. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Automation 타입 라이브러리에 대한 참조를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 참조의 이름. |
| libid | java.lang.String | Automation 타입 라이브러리의 식별자. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


CollectionBase 인스턴스에서 모든 객체를 제거합니다.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


인스턴스가 이 객체를 포함하는지 여부를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | 테스트 객체 |

**Returns:**
boolean - 인스턴스가 이 객체를 포함하는지 여부
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


인덱스로 목록에서 참조를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | int | 인덱스. |

**Returns:**
[VbaProjectReference](../../com.aspose.diagram/vbaprojectreference) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


CollectionBase 인스턴스에 포함된 요소 수를 가져옵니다.

**Returns:**
int - CollectionBase 인스턴스에 포함된 요소 수.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```


CollectionBase 인스턴스에서 특정 항목의 인덱스를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | CollectionBase 인스턴스에서 특정 항목의 인덱스를 결정합니다. |

**Returns:**
int - 리스트에서 값을 찾은 경우 해당 인덱스; 찾지 못하면 -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


CollectionBase 인스턴스를 순회하는 열거자를 반환합니다.

**Returns:**
java.util.Iterator - CollectionBase 인스턴스용 반복자.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


지정된 인덱스에 있는 항목을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 제거할 항목의 0부터 시작하는 인덱스. |

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

