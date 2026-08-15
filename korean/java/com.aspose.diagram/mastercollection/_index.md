---
title: MasterCollection
second_title: Aspose.Diagram for Java API 참조
description: Master 컬렉션.
type: docs
weight: 241
url: /ko/java/com.aspose.diagram/mastercollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class MasterCollection extends Collection
```

Master 컬렉션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Master master)](#add-com.aspose.diagram.Master-) | 컬렉션에 Master 객체를 추가합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 요소를 제거합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [getMaster(int ID)](#getMaster-int-) | Gets the element at the specified ID. |
| [getMasterByName(String name)](#getMasterByName-java.lang.String-) | 이름으로 마스터를 가져옵니다. |
| [getMasterShortcuts()](#getMasterShortcuts--) | MasterShortcut 컬렉션. |
| [getMaxRelID()](#getMaxRelID--) | 컬렉션에서 최대 rel id를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | 컬렉션에 항목이 존재합니다. |
| [isExist(String name)](#isExist-java.lang.String-) | 컬렉션에 마스터가 존재하는지 확인합니다. |
| [isExistRelId(String relID)](#isExistRelId-java.lang.String-) | 컬렉션에 마스터 rel id가 존재하는지 확인합니다. |
| [iterator()](#iterator--) | 비제네릭 컬렉션에 대한 간단한 반복을 지원합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Master master)](#remove-com.aspose.diagram.Master-) | 컬렉션에서 Master 객체를 제거합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Master master) {#add-com.aspose.diagram.Master-}
```
public int add(Master master)
```


컬렉션에 Master 객체를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| master | [Master](../../com.aspose.diagram/master) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


컬렉션에서 모든 요소를 제거합니다.

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
### get(int index) {#get-int-}
```
public Master get(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
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


컬렉션에 실제로 포함된 요소 수를 가져옵니다.

**Returns:**
int
### getMaster(int ID) {#getMaster-int-}
```
public Master getMaster(int ID)
```


Gets the element at the specified ID.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ID | int |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
### getMasterByName(String name) {#getMasterByName-java.lang.String-}
```
public Master getMasterByName(String name)
```


이름으로 마스터를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
### getMasterShortcuts() {#getMasterShortcuts--}
```
public MasterShortcutCollection getMasterShortcuts()
```


MasterShortcut 컬렉션.

**Returns:**
[MasterShortcutCollection](../../com.aspose.diagram/mastershortcutcollection)
### getMaxRelID() {#getMaxRelID--}
```
public int getMaxRelID()
```


컬렉션에서 최대 rel id를 가져옵니다.

**Returns:**
int -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


컬렉션에 항목이 존재합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 요소의 인덱스. |

**Returns:**
boolean -
### isExist(String name) {#isExist-java.lang.String-}
```
public boolean isExist(String name)
```


컬렉션에 마스터가 존재하는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
boolean -
### isExistRelId(String relID) {#isExistRelId-java.lang.String-}
```
public boolean isExistRelId(String relID)
```


컬렉션에 마스터 rel id가 존재하는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| relID | java.lang.String |  |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


비제네릭 컬렉션에 대한 간단한 반복을 지원합니다.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Master master) {#remove-com.aspose.diagram.Master-}
```
public void remove(Master master)
```


컬렉션에서 Master 객체를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| master | [Master](../../com.aspose.diagram/master) |  |

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

