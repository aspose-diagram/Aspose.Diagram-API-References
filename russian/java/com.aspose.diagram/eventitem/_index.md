---
title: EventItem
second_title: Справочник API Aspose.Diagram for Java
description: Инкапсулирует код события.
type: docs
weight: 145
url: /ru/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Инкапсулирует код события. Элемент EventItem может вызывать два типа действий: он может запускать надстройку или отправлять уведомление о событии вызывающей программе.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EventItem()](#EventItem--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Указывает код действия родительского элемента EventItem. Чтобы элемент EventItem был сохранён в файле DatadiagramML, он должен быть сохраняемым. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Представляет флаг, указывающий, включено ли событие или отключено. |
| [getEventCode()](#getEventCode--) | Код, указывающий событие, которое запускает надстройку. |
| [getID()](#getID--) | Идентификатор события. |
| [getTarget()](#getTarget--) | Указывает цель события. |
| [getTargetArgs()](#getTargetArgs--) | Указывает строку, содержащую аргументы, которые будут отправлены цели события. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Для описания этого свойства, пожалуйста, смотрите [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Для описания этого свойства, пожалуйста, смотрите [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Для описания этого свойства, пожалуйста, смотрите [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


Конструктор.

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
### getAction() {#getAction--}
```
public int getAction()
```


Указывает код действия родительского элемента EventItem. Чтобы элемент EventItem был сохранён в файле DatadiagramML, он должен быть сохраняемым. В настоящее время единственный допустимый код действия сохраняемого события — 1 (ONEVENT_ACT_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Представляет флаг, указывающий, включено ли событие или отключено.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Код, указывающий событие, которое запускает надстройку. Для получения дополнительной информации о кодах событий см. «Event Codes» в справочнике Microsoft Visio 2007 Automation Reference.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Идентификатор события.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Указывает цель события.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Указывает строку, содержащую аргументы, которые будут отправлены цели события.

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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

