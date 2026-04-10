---
title: CollectionBase
second_title: Aspose.Diagram for Java API 참조
description: 강력히 형식화된 컬렉션을 위한 추상 기본 클래스를 제공합니다.
type: docs
weight: 50
url: /ko/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

강력히 형식화된 컬렉션을 위한 추상 기본 클래스를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | CollectionBase 클래스의 새 인스턴스를 기본 초기 용량으로 초기화합니다. |
| [CollectionBase(int capacity)](#CollectionBase-int-) | CollectionBase 클래스의 새 인스턴스를 지정된 용량으로 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | CollectionBase 인스턴스에 항목을 추가합니다. |
| [clear()](#clear--) | CollectionBase 인스턴스에서 모든 객체를 제거합니다. |
| [contains(Object o)](#contains-java.lang.Object-) | 인스턴스가 이 객체를 포함하는지 여부를 반환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 지정된 위치의 항목을 가져옵니다. |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


CollectionBase 클래스의 새 인스턴스를 기본 초기 용량으로 초기화합니다.

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


CollectionBase 클래스의 새 인스턴스를 지정된 용량으로 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 용량 | int | 새 목록이 처음에 저장할 수 있는 요소 수입니다. |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


지정된 위치의 항목을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 지정된 위치 인덱스. |

**Returns:**
java.lang.Object - 지정된 위치의 항목.
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

