---
title: MilestoneHelper
second_title: Aspose.Diagram for Java API 참조
description: MilestoneHelper를 사용하여 마일스톤 도형의 속성을 설정합니다.
type: docs
weight: 246
url: /ko/java/com.aspose.diagram/milestonehelper/
---

**Inheritance:**
java.lang.Object
```
public class MilestoneHelper
```

MilestoneHelper를 사용하여 마일스톤 도형의 속성을 설정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MilestoneHelper(Shape shape)](#MilestoneHelper-com.aspose.diagram.Shape-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMilestoneDate()](#getMilestoneDate--) | 마일스톤 날짜 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshMilestone(Shape timeline)](#refreshMilestone-com.aspose.diagram.Shape-) | 마일스톤 새로 고침 |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | 타임라인에서 마커(마일스톤, 구간)를 이동할 때 데이터를 업데이트할지 여부 |
|  | [setDateFormat(int value)](#setDateFormat-int-) | 모양의 DateFormat /// |

| ----------------------- | ------------------------------- |
| **값**\u9286\u20ac | **형식 문자열**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatString(String value)](#setDateFormatString-java.lang.String-) | 모양의 DateFormat 문자열 |
| [setMilestoneDate(DateTime value)](#setMilestoneDate-com.aspose.diagram.DateTime-) |  |
| [setType(int value)](#setType-int-) | 모양의 유형 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MilestoneHelper(Shape shape) {#MilestoneHelper-com.aspose.diagram.Shape-}
```
public MilestoneHelper(Shape shape)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

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
### getMilestoneDate() {#getMilestoneDate--}
```
public DateTime getMilestoneDate()
```


마일스톤 날짜

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




### refreshMilestone(Shape timeline) {#refreshMilestone-com.aspose.diagram.Shape-}
```
public void refreshMilestone(Shape timeline)
```


마일스톤 새로 고침

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| timeline | [Shape](../../com.aspose.diagram/shape) |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


타임라인에서 마커(마일스톤, 구간)를 이동할 때 데이터를 업데이트할지 여부

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setDateFormat(int value) {#setDateFormat-int-}
```
public void setDateFormat(int value)
```


모양의 DateFormat ///

| ----------------------- | ------------------------------- |
| **값**\u9286\u20ac | **형식 문자열**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.-d                       |
| 5                       | d MMMM yyyy                     |
| 6                       | yy-M                            |
| 7                       | MMM-yy                          |
| 8                       | MMMM d, yyyy                    |
| 9                       | MMM d, yyyy                     |
| 10                      | M-d-yy                          |
| 11                      | M-d                             |
| 12                      | d MMMM, yyyy                    |
| 13                      | d MMM, yyyy                     |
| 14                      | d-M-yy                          |
| 15                      | d-M                             |
| 16                      | yy-M-d                          |
| 17                      | yyyy-M-d                        |
| 18                      | M-yy                            |
| 19                      | M-yyyy                          |
| 20                      | MMMM yyyy                       |
| 21                      | MMMM yy                         |
| 22                      | MMM yyyy                        |
| 23                      | MMM yy                          |
| 24                      | yy                              |
| 25                      | yyyy                            |
| 26                      | d                               |
| 27                      | MMMM                            |
| 28                      | MMM                             |
| 29                      | M                               |
| 30                      | MM/dd/yyyy                      |

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDateFormatString(String value) {#setDateFormatString-java.lang.String-}
```
public void setDateFormatString(String value)
```


모양의 DateFormat 문자열

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMilestoneDate(DateTime value) {#setMilestoneDate-com.aspose.diagram.DateTime-}
```
public void setMilestoneDate(DateTime value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


모양의 유형

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

