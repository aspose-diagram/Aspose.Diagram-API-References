---
title: DocumentSettings
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, задающие настройки документа.
type: docs
weight: 126
url: /ru/java/com.aspose.diagram/documentsettings/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSettings
```

Содержит элементы, задающие настройки документа.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachedToolbars()](#getAttachedToolbars--) | Файл пользовательского интерфейса Microsoft Visio (VSU), закодированный в MIME (Multipurpose Internet Mail Extensions), представляющий пользовательские панели инструментов. |
| [getClass()](#getClass--) |  |
| [getCustomMenusFile()](#getCustomMenusFile--) | Содержит имя файла пользовательского интерфейса Microsoft Visio (.vsu), определяющего пользовательские меню и ускорители для документа. |
| [getCustomToolbarsFile()](#getCustomToolbarsFile--) | Содержит имя файла пользовательского интерфейса Microsoft Visio (.vsu), определяющего пользовательские панели инструментов и строки состояния для документа. |
| [getDefaultFillStyle()](#getDefaultFillStyle--) | Указывает ID элемента StyleSheet. |
| [getDefaultGuideStyle()](#getDefaultGuideStyle--) | Указывает ID элемента StyleSheet. |
| [getDefaultLineStyle()](#getDefaultLineStyle--) | Указывает ID элемента StyleSheet. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Указывает ID элемента StyleSheet. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Указывает, включена ли функция динамической сетки для документа или окна. |
| [getGlueSettings()](#getGlueSettings--) | Указывает объекты, к которым фигуры привязываются, когда клей включён в документе. |
| [getProtectBkgnds()](#getProtectBkgnds--) | Указывает, запрещено ли пользователю удалять или изменять фоновые страницы. |
| [getProtectMasters()](#getProtectMasters--) | Указывает, запрещено ли пользователю создавать, изменять или удалять шаблоны. |
| [getProtectShapes()](#getProtectShapes--) | Указывает, запрещено ли пользователю выбирать фигуры, у которых элемент LockSelect установлен в 1. |
| [getProtectStyles()](#getProtectStyles--) | Указывает, запрещено ли пользователю создавать или изменять стили. |
| [getSnapAngles()](#getSnapAngles--) | Содержит коллекцию элементов SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Указывает, включена ли конкретная настройка расширения привязки для активного окна. |
| [getSnapSettings()](#getSnapSettings--) | Указывает объекты, к которым фигуры привязываются, когда привязка активна в окне. |
| [getTopPage()](#getTopPage--) | Указывает идентификатор страницы, которая должна отображаться при открытии документа в Microsoft Visio. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachedToolbars(byte[] value)](#setAttachedToolbars-byte---) | Для описания этого свойства, пожалуйста, смотрите [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--) |
| [setCustomMenusFile(String value)](#setCustomMenusFile-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--) |
| [setCustomToolbarsFile(String value)](#setCustomToolbarsFile-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--) |
| [setDefaultFillStyle(int value)](#setDefaultFillStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--) |
| [setDefaultGuideStyle(int value)](#setDefaultGuideStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--) |
| [setDefaultLineStyle(int value)](#setDefaultLineStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--) |
| [setDefaultTextStyle(int value)](#setDefaultTextStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Для описания этого свойства, пожалуйста, смотрите [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Для описания этого свойства, пожалуйста, смотрите [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--) |
| [setProtectBkgnds(int value)](#setProtectBkgnds-int-) | Для описания этого свойства, пожалуйста, смотрите [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--) |
| [setProtectMasters(int value)](#setProtectMasters-int-) | Для описания этого свойства, пожалуйста, смотрите [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--) |
| [setProtectShapes(int value)](#setProtectShapes-int-) | Для описания этого свойства, пожалуйста, смотрите [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--) |
| [setProtectStyles(int value)](#setProtectStyles-int-) | Для описания этого свойства, пожалуйста, смотрите [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--) |
| [setSnapAngles(FloatPointNumCollection value)](#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-) | Для описания этого свойства, пожалуйста, смотрите [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Для описания этого свойства, пожалуйста, смотрите [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Для описания этого свойства, пожалуйста, смотрите [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--) |
| [setTopPage(int value)](#setTopPage-int-) | Для описания этого свойства, пожалуйста, смотрите [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAttachedToolbars() {#getAttachedToolbars--}
```
public byte[] getAttachedToolbars()
```


Файл пользовательского интерфейса Microsoft Visio (VSU), закодированный в MIME (Multipurpose Internet Mail Extensions), представляющий пользовательские панели инструментов.

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMenusFile() {#getCustomMenusFile--}
```
public String getCustomMenusFile()
```


Содержит имя файла пользовательского интерфейса Microsoft Visio (.vsu), определяющего пользовательские меню и ускорители для документа.

**Returns:**
java.lang.String
### getCustomToolbarsFile() {#getCustomToolbarsFile--}
```
public String getCustomToolbarsFile()
```


Содержит имя файла пользовательского интерфейса Microsoft Visio (.vsu), определяющего пользовательские панели инструментов и строки состояния для документа.

**Returns:**
java.lang.String
### getDefaultFillStyle() {#getDefaultFillStyle--}
```
public int getDefaultFillStyle()
```


Указывает идентификатор элемента StyleSheet. При следующем создании пользователем фигуры с помощью инструмента рисования, фигура наследует стиль заливки от указанного элемента StyleSheet.

**Returns:**
int
### getDefaultGuideStyle() {#getDefaultGuideStyle--}
```
public int getDefaultGuideStyle()
```


Указывает идентификатор элемента StyleSheet. При следующем создании пользователем направляющей, направляющая наследует свой стиль направляющей от указанного элемента StyleSheet.

**Returns:**
int
### getDefaultLineStyle() {#getDefaultLineStyle--}
```
public int getDefaultLineStyle()
```


Указывает идентификатор элемента StyleSheet. При следующем создании пользователем фигуры с помощью инструмента рисования, фигура наследует стиль линии от указанного элемента StyleSheet.

**Returns:**
int
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public int getDefaultTextStyle()
```


Указывает идентификатор элемента StyleSheet. При следующем создании пользователем фигуры с помощью инструмента рисования, фигура наследует стиль текста от указанного элемента StyleSheet.

**Returns:**
int
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Указывает, включена ли функция динамической сетки для документа или окна.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Указывает объекты, к которым фигуры привязываются, когда клей включён в документе.

**Returns:**
int
### getProtectBkgnds() {#getProtectBkgnds--}
```
public int getProtectBkgnds()
```


Указывает, запрещено ли пользователю удалять или изменять фоновые страницы.

**Returns:**
int
### getProtectMasters() {#getProtectMasters--}
```
public int getProtectMasters()
```


Specifies whether the user is prevented from creating, editing, or deleting masters. Regardless of this setting, the user can still create instances of masters.

**Returns:**
int
### getProtectShapes() {#getProtectShapes--}
```
public int getProtectShapes()
```


Указывает, запрещено ли пользователю выбирать фигуры, у которых элемент LockSelect установлен в 1.

**Returns:**
int
### getProtectStyles() {#getProtectStyles--}
```
public int getProtectStyles()
```


Specifies whether the user is prevented from creating or editing styles. However, regardless of this setting, the user can still apply styles.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Содержит коллекцию элементов SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Указывает, включена ли конкретная настройка расширения привязки для активного окна.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Указывает объекты, к которым фигуры привязываются, когда привязка активна в окне.

**Returns:**
int
### getTopPage() {#getTopPage--}
```
public int getTopPage()
```


Указывает идентификатор страницы, которая должна отображаться при открытии документа в Microsoft Visio.

**Returns:**
int
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




### setAttachedToolbars(byte[] value) {#setAttachedToolbars-byte---}
```
public void setAttachedToolbars(byte[] value)
```


Для описания этого свойства, пожалуйста, смотрите [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setCustomMenusFile(String value) {#setCustomMenusFile-java.lang.String-}
```
public void setCustomMenusFile(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCustomToolbarsFile(String value) {#setCustomToolbarsFile-java.lang.String-}
```
public void setCustomToolbarsFile(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDefaultFillStyle(int value) {#setDefaultFillStyle-int-}
```
public void setDefaultFillStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDefaultGuideStyle(int value) {#setDefaultGuideStyle-int-}
```
public void setDefaultGuideStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDefaultLineStyle(int value) {#setDefaultLineStyle-int-}
```
public void setDefaultLineStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDefaultTextStyle(int value) {#setDefaultTextStyle-int-}
```
public void setDefaultTextStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setProtectBkgnds(int value) {#setProtectBkgnds-int-}
```
public void setProtectBkgnds(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setProtectMasters(int value) {#setProtectMasters-int-}
```
public void setProtectMasters(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setProtectShapes(int value) {#setProtectShapes-int-}
```
public void setProtectShapes(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setProtectStyles(int value) {#setProtectStyles-int-}
```
public void setProtectStyles(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSnapAngles(FloatPointNumCollection value) {#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-}
```
public void setSnapAngles(FloatPointNumCollection value)
```


Для описания этого свойства, пожалуйста, смотрите [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection) |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTopPage(int value) {#setTopPage-int-}
```
public void setTopPage(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--)

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

