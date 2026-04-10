---
title: MilestoneHelper
second_title: Aspose.Diagram for Java API リファレンス
description: マイルストーン シェイプのプロパティを設定する MilestoneHelper。
type: docs
weight: 246
url: /ja/java/com.aspose.diagram/milestonehelper/
---

**Inheritance:**
java.lang.Object
```
public class MilestoneHelper
```

マイルストーン シェイプのプロパティを設定する MilestoneHelper。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MilestoneHelper(Shape shape)](#MilestoneHelper-com.aspose.diagram.Shape-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMilestoneDate()](#getMilestoneDate--) | マイルストーン日付 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshMilestone(Shape timeline)](#refreshMilestone-com.aspose.diagram.Shape-) | マイルストーンを更新 |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | タイムライン上でマーカー（マイルストーン、間隔）が移動される際にデータを更新するかどうか |
|  | [setDateFormat(int value)](#setDateFormat-int-) | シェイプの DateFormat /// |

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatString(String value)](#setDateFormatString-java.lang.String-) | シェイプの DateFormat 文字列 |
| [setMilestoneDate(DateTime value)](#setMilestoneDate-com.aspose.diagram.DateTime-) |  |
| [setType(int value)](#setType-int-) | シェイプのタイプ |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MilestoneHelper(Shape shape) {#MilestoneHelper-com.aspose.diagram.Shape-}
```
public MilestoneHelper(Shape shape)
```


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


マイルストーン日付

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


マイルストーンを更新

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| timeline | [Shape](../../com.aspose.diagram/shape) |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


タイムライン上でマーカー（マイルストーン、間隔）が移動される際にデータを更新するかどうか

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setDateFormat(int value) {#setDateFormat-int-}
```
public void setDateFormat(int value)
```


シェイプの DateFormat ///

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDateFormatString(String value) {#setDateFormatString-java.lang.String-}
```
public void setDateFormatString(String value)
```


シェイプの DateFormat 文字列

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMilestoneDate(DateTime value) {#setMilestoneDate-com.aspose.diagram.DateTime-}
```
public void setMilestoneDate(DateTime value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


シェイプのタイプ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

