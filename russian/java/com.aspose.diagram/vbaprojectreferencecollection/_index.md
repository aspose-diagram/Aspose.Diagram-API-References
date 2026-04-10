---
title: VbaProjectReferenceCollection
second_title: Справочник API Aspose.Diagram for Java
description: Представляет все ссылки проекта VBA.
type: docs
weight: 435
url: /ru/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

Представляет все ссылки проекта VBA.
## Методы

| Метод | Описание |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Добавляет элемент в экземпляр CollectionBase. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Добавить ссылку на модифицированную типовую библиотеку и её расширенную типовую библиотеку. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | Добавить ссылку на внешний проект VBA. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Добавить ссылку на типовую библиотеку Automation. |
| [clear()](#clear--) | Удаляет все объекты из экземпляра CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | Возвращает, содержит ли экземпляр этот объект. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | Получить ссылку из списка по индексу. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество элементов, содержащихся в экземпляре CollectionBase. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | Определяет индекс конкретного элемента в экземпляре CollectionBase. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы экземпляра CollectionBase. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


Добавляет элемент в экземпляр CollectionBase.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Объект, который нужно добавить в экземпляр CollectionBase. |

**Returns:**
int - Позиция, в которую был вставлен новый элемент.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


Добавить ссылку на модифицированную типовую библиотеку и её расширенную типовую библиотеку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя ссылки. |
| libid | java.lang.String | Идентификатор типовой библиотеки Automation. |
| twiddledlibid | java.lang.String | Идентификатор модифицированной типовой библиотеки. |
| extendedLibid | java.lang.String | Идентификатор расширенной библиотеки типов |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


Добавить ссылку на внешний проект VBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя ссылки. |
| absoluteLibid | java.lang.String | Идентификатор ссылочного проекта VBA\u9225\u6a9a с абсолютным путем. |
| relativeLibid | java.lang.String | Идентификатор ссылочного проекта VBA\u9225\u6a9a с относительным путем. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Добавить ссылку на типовую библиотеку Automation.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя ссылки. |
| libid | java.lang.String | Идентификатор типовой библиотеки Automation. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Удаляет все объекты из экземпляра CollectionBase.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


Возвращает, содержит ли экземпляр этот объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | тестовый объект |

**Returns:**
boolean - Содержит ли экземпляр этот объект
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


Получить ссылку из списка по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int | Индекс. |

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


Получает количество элементов, содержащихся в экземпляре CollectionBase.

**Returns:**
int - Количество элементов, содержащихся в экземпляре CollectionBase.
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


Определяет индекс конкретного элемента в экземпляре CollectionBase.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Определяет индекс конкретного элемента в экземпляре CollectionBase. |

**Returns:**
int - Индекс значения, если найдено в списке; иначе -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


Возвращает перечислитель, который перебирает элементы экземпляра CollectionBase.

**Returns:**
java.util.Iterator - Итератор для экземпляра CollectionBase.
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


Удаляет элемент по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента, который нужно удалить. |

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

