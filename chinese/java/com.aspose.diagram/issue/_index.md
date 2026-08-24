---
title: Issue
second_title: Aspose.Diagram for Java API 参考
description: 表示文档中的单个验证问题。
type: docs
weight: 208
url: /zh/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

表示文档中的单个验证问题。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Issue()](#Issue--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | 指定验证问题的唯一标识符。 |
| [getIgnored()](#getIgnored--) | 指定验证问题当前是否被忽略。 |
| [getIssueTarget()](#getIssueTarget--) | 根据父验证问题的目标，指定该父验证问题关联的页面，或页面和形状两者。 |
| [getRuleInfo()](#getRuleInfo--) | 指定父验证问题所涉及的验证规则信息。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | 有关此属性的描述，请参见 [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | 有关此属性的描述，请参见 [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


构造函数

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getID() {#getID--}
```
public long getID()
```


指定验证问题的唯一标识符。

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


指定验证问题当前是否被忽略。默认值为 False。

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


根据父验证问题的目标，指定父验证问题关联的页面，或页面和形状两者。如果父验证问题的目标是文档，则 IssueTarget 既不指定页面也不指定形状。

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


指定父验证问题所涉及的验证规则信息。

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


有关此属性的描述，请参见 [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


有关此属性的描述，请参见 [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

