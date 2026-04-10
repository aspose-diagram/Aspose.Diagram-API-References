---
title: Issue
second_title: Справочник API Aspose.Diagram for Java
description: Представляет одну проблему проверки в документе.
type: docs
weight: 208
url: /ru/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Представляет одну проблему проверки в документе.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Issue()](#Issue--) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Указывает уникальный идентификатор проблемы валидации. |
| [getIgnored()](#getIgnored--) | Указывает, игнорируется ли в данный момент проблема валидации. |
| [getIssueTarget()](#getIssueTarget--) | В зависимости от цели родительской validation issue, указывает либо страницу, либо и страницу, и форму, с которыми связана родительская validation issue. |
| [getRuleInfo()](#getRuleInfo--) | Указывает информацию о правиле проверки, к которому относится родительская проблема проверки. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Для описания этого свойства см. [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Для описания этого свойства см. [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Конструктор

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
### getID() {#getID--}
```
public long getID()
```


Указывает уникальный идентификатор проблемы валидации.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Указывает, игнорируется ли в данный момент проблема валидации. По умолчанию — False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


В зависимости от цели родительской проблемы проверки указывает либо страницу, либо и страницу, и фигуру, с которыми связана родительская проблема проверки. Если целью родительской проблемы проверки является документ, IssueTarget не указывает ни страницу, ни фигуру.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Указывает информацию о правиле проверки, к которому относится родительская проблема проверки.

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


Для описания этого свойства см. [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Для описания этого свойства см. [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

