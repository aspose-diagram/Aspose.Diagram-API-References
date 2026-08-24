---
title: StreamProviderOptions
second_title: Справочник API Aspose.Diagram for Java
description: Представляет параметры потока.
type: docs
weight: 390
url: /ru/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

Представляет параметры потока.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | Путь по умолчанию (URL), сохраняемый в сгенерированном HTML‑файле для указанного источника. |
| [getStream()](#getStream--) | Получает/устанавливает выходной поток для записи сохранённых данных |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | Пользовательский путь (URL), сохраняемый в сгенерированном HTML‑файле для указанного источника. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | Для описания этого свойства, пожалуйста, см. [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


Путь по умолчанию (URL), сохраняемый в сгенерированном HTML‑файле для указанного источника. Например, данные листа сохраняются в xxx\_files/sheet001.htm, URL, используемый в основном HTML‑файле, должен выглядеть так "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


Получает/устанавливает выходной поток для записи сохранённых данных

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


Пользовательский путь (URL), сохраняемый в сгенерированном HTML‑файле для указанного источника. Если пользователь не задает его, будет использован DefaultPath. Например, данные листа будут сохранены пользователем в d:/sheet001.htm, URL, используемый в основном HTML‑файле, должен быть "d:/sheet001.htm" или другой допустимый относительный путь, доступный из основного HTML‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


Для описания этого свойства, пожалуйста, см. [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.OutputStream |  |

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

