---
title: Window
second_title: Справочник API Aspose.Diagram for Java
description: Представляет открытое окно в экземпляре Microsoft Visio.
type: docs
weight: 444
url: /ru/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Представляет открытое окно в экземпляре Microsoft Visio. Этот элемент содержит информацию, необходимую для точного воссоздания окна пользовательского интерфейса в рабочем пространстве приложения при первоначальном открытии файла DatadiagramML в Visio.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Window()](#Window--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Идентификатор контейнера: Page, Sheet или Master. |
| [getContainerType()](#getContainerType--) | Может принимать одно из следующих значений: Document, Page или Master. |
| [getDocument()](#getDocument--) | Путь к файлу документа, отображаемого в этом окне. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Указывает, включена ли функция динамической сетки для документа или окна. |
| [getGlueSettings()](#getGlueSettings--) | Указывает объекты, к которым фигуры привязываются, когда клей включён в документе. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getMaster()](#getMaster--) | Идентификатор мастера, если это окно отображает мастер. |
| [getPage()](#getPage--) | Идентификатор страницы, если это окно отображает страницу. |
| [getParentWindow()](#getParentWindow--) | Идентификатор окна, в котором содержится это окно шаблона. |
| [getReadOnly()](#getReadOnly--) | Флаг только для чтения, если этот шаблон не является шаблоном документа. |
| [getSheet()](#getSheet--) | Идентификатор листа в контейнере. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Указывает, отображаются ли точки соединения в окне. |
| [getShowGrid()](#getShowGrid--) | Указывает, отображается ли сетка в окне чертежа. |
| [getShowGuides()](#getShowGuides--) | Указывает, отображаются ли направляющие в окне чертежа. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Указывает, отображаются ли разрывы страниц в окне. |
| [getShowRulers()](#getShowRulers--) | Указывает, отображаются ли линейки в окне чертежа. |
| [getSnapAngles()](#getSnapAngles--) | Содержит коллекцию элементов SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Указывает, включена ли конкретная настройка расширения привязки для активного окна. |
| [getSnapSettings()](#getSnapSettings--) | Указывает объекты, к которым фигуры привязываются, когда привязка активна в окне. |
| [getStencilGroup()](#getStencilGroup--) | Указывает группу объединённых окон шаблонов, членом которой является данное окно. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Содержит целое число, определяющее относительное положение шаблона внутри группы в окне. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Указывает ширину вкладки страницы окна чертежа (в виде доли от общей ширины окна чертежа). |
| [getViewCenterX()](#getViewCenterX--) | Необязательное значение типа double. |
| [getViewCenterY()](#getViewCenterY--) | Необязательное значение типа double. |
| [getViewScale()](#getViewScale--) | Необязательное значение типа double. |
| [getWindowHeight()](#getWindowHeight--) | Высота прямоугольника окна. |
| [getWindowLeft()](#getWindowLeft--) | Координата левого края прямоугольника окна. |
| [getWindowState()](#getWindowState--) | Этот атрибут может быть суммой следующих значений. |
| [getWindowTop()](#getWindowTop--) | Координата верхнего края прямоугольника окна. |
| [getWindowType()](#getWindowType--) | Перечислимое значение, которое может быть одним из следующих: Drawing, Sheet, Stencil или Icon. Элемент Window с WindowType='Stencil' должен располагаться после родительского окна чертежа (WindowType='Drawing') и перед любыми другими элементами окон чертежа. |
| [getWindowWidth()](#getWindowWidth--) | Ширина прямоугольника окна. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Для описания этого свойства, пожалуйста, см. [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Для описания этого свойства, пожалуйста, см. [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Для описания этого свойства, пожалуйста, смотрите [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Для описания этого свойства, пожалуйста, смотрите [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Для описания этого свойства, пожалуйста, смотрите [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Для описания этого свойства, пожалуйста, смотрите [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Для описания этого свойства, пожалуйста, смотрите [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Для описания этого свойства, пожалуйста, смотрите [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Для описания этого свойства, пожалуйста, смотрите [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Для описания этого свойства, пожалуйста, смотрите [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Для описания этого свойства, пожалуйста, смотрите [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Для описания этого свойства, пожалуйста, смотрите [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Для описания этого свойства, пожалуйста, смотрите [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Для описания этого свойства, пожалуйста, смотрите [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Для описания этого свойства, пожалуйста, смотрите [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Для описания этого свойства, пожалуйста, смотрите [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Для описания этого свойства, пожалуйста, смотрите [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Для описания этого свойства, пожалуйста, смотрите [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Для описания этого свойства, пожалуйста, смотрите [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


Идентификатор контейнера: Page, Sheet или Master. Имеет значение и необходим только если указано ContainerType.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Может быть одним из следующих значений: Document, Page или Master. Имеет значение только когда WindowType указано как Drawing или Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Путь к файлу документа, отображаемого в этом окне. Этот атрибут имеет значение для окон, у которых WindowType указано как Stencil.

**Returns:**
java.lang.String
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
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Идентификатор мастера, если это окно отображает мастер.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Идентификатор страницы, если это окно отображает страницу. Имеет значение только когда WindowType указано как Drawing и ContainerType указано как Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


Идентификатор окна, в котором содержится это окно-стенсил. Имеет значение только когда WindowType указано как Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Флаг только для чтения, если этот шаблон не является шаблоном документа.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


Идентификатор листа в контейнере. Имеет значение только когда Container указано как Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Указывает, отображаются ли точки соединения в окне.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Указывает, отображается ли сетка в окне чертежа.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Указывает, отображаются ли направляющие в окне чертежа.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Указывает, отображаются ли разрывы страниц в окне.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Указывает, отображаются ли линейки в окне чертежа.

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


Указывает, включена ли конкретная настройка расширения привязки для активного окна или отключена. Значение может быть суммой значений в следующей таблице.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Указывает объекты, к которым привязываются фигуры, когда привязка активна в окне. Значение может быть суммой значений из следующей таблицы.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Указывает группу объединённых окон-стенсилов, членом которой является данное окно. Этот атрибут имеет значение только для элементов Window, у которых атрибут WindowType равен Stencil, и только если окно-стенсил является частью объединённой группы окон-стенсилов. Все окна-стенсилы, входящие в одну и ту же объединённую группу, имеют одинаковое значение элемента StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Содержит целое число, определяющее относительное положение шаблона внутри группы в окне.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Указывает ширину вкладки страницы окна чертежа (в виде доли от общей ширины окна чертежа).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Необязательное значение типа double.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Необязательное значение типа double.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Необязательное значение типа double.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Высота прямоугольника окна.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Координата левого края прямоугольника окна.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Этот атрибут может быть суммой следующих значений.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Координата верхнего края прямоугольника окна.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Перечислимое значение, которое может быть одним из следующих: Drawing, Sheet, Stencil или Icon. Элемент Window с WindowType='Stencil' должен располагаться после родительского окна чертежа (WindowType='Drawing') и перед любыми другими элементами окон чертежа.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Ширина прямоугольника окна.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


Для описания этого свойства, пожалуйста, см. [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Для описания этого свойства, пожалуйста, см. [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Для описания этого свойства, пожалуйста, смотрите [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Для описания этого свойства, пожалуйста, смотрите [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Для описания этого свойства, пожалуйста, смотрите [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

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

