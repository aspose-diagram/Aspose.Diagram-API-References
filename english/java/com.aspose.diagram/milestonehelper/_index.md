---
title: MilestoneHelper
second_title: Aspose.Diagram for Java API Reference
description: MilestoneHelper to set property of milestone shape.
type: docs
weight: 266
url: /java/com.aspose.diagram/milestonehelper/
---

**Inheritance:**
java.lang.Object
```
public class MilestoneHelper
```

MilestoneHelper to set property of milestone shape. Compatibility shell over [MilestoneProperties](../../com.aspose.diagram/milestoneproperties): the public API is unchanged (plus getters for the previously write-only properties), the cell access is delegated to the properties class, and [refreshMilestone(Shape)](../../com.aspose.diagram/milestonehelper\#refreshMilestone-Shape-) is rewritten:

    | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | /// Children without a master no longer crash the refresh (the old code dereferenced /// child.MasterShape unconditionally). ///                                                                                                                                              |
    | /// An existing local date field is updated in place; the old code appended a new /// field on every refresh. ///                                                                                                                                                             |
    | /// Positioning reads the timeline's left edge from XForm (the old code read /// XForm1D.BeginX, which does not exist on a 2-D group shape) and sorts the dated /// children with two parallel arrays instead of the SortedStringList, which has no /// Java counterpart. /// |

    |
## Constructors

| Constructor | Description |
| --- | --- |
| [MilestoneHelper(Shape shape)](#MilestoneHelper-com.aspose.diagram.Shape-) | MilestoneHelper. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateFormat()](#getDateFormat--) | DateFormat of shape (0 - 30) |
| [getMilestoneDate()](#getMilestoneDate--) | Milestone date |
| [getType()](#getType--) | Type of shape (0 = Circle ... 8 = Pin) |
| [hashCode()](#hashCode--) |  |
| [isAutoUpdate()](#isAutoUpdate--) | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshMilestone(Shape timeline)](#refreshMilestone-com.aspose.diagram.Shape-) | Refresh milestone |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | For the description of this property, please see [isAutoUpdate()](../../com.aspose.diagram/milestonehelper\#isAutoUpdate--) |
| [setDateFormat(int value)](#setDateFormat-int-) | For the description of this property, please see [getDateFormat()](../../com.aspose.diagram/milestonehelper\#getDateFormat--) |
| [setMilestoneDate(DateTime value)](#setMilestoneDate-com.aspose.diagram.DateTime-) | For the description of this property, please see [getMilestoneDate()](../../com.aspose.diagram/milestonehelper\#getMilestoneDate--) |
| [setType(int value)](#setType-int-) | For the description of this property, please see [getType()](../../com.aspose.diagram/milestonehelper\#getType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MilestoneHelper(Shape shape) {#MilestoneHelper-com.aspose.diagram.Shape-}
```
public MilestoneHelper(Shape shape)
```


MilestoneHelper.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
### getDateFormat() {#getDateFormat--}
```
public int getDateFormat()
```


DateFormat of shape (0 - 30)

**Returns:**
int
### getMilestoneDate() {#getMilestoneDate--}
```
public DateTime getMilestoneDate()
```


Milestone date

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getType() {#getType--}
```
public int getType()
```


Type of shape (0 = Circle ... 8 = Pin)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoUpdate() {#isAutoUpdate--}
```
public boolean isAutoUpdate()
```


whether to update data for markers (milestones, intervals) as they are moved on timeline

**Returns:**
boolean
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


Refresh milestone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeline | [Shape](../../com.aspose.diagram/shape) |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


For the description of this property, please see [isAutoUpdate()](../../com.aspose.diagram/milestonehelper\#isAutoUpdate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDateFormat(int value) {#setDateFormat-int-}
```
public void setDateFormat(int value)
```


For the description of this property, please see [getDateFormat()](../../com.aspose.diagram/milestonehelper\#getDateFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMilestoneDate(DateTime value) {#setMilestoneDate-com.aspose.diagram.DateTime-}
```
public void setMilestoneDate(DateTime value)
```


For the description of this property, please see [getMilestoneDate()](../../com.aspose.diagram/milestonehelper\#getMilestoneDate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


For the description of this property, please see [getType()](../../com.aspose.diagram/milestonehelper\#getType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

