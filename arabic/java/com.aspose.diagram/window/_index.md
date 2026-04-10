---
title: Window
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل نافذة مفتوحة في نسخة Microsoft Visio.
type: docs
weight: 444
url: /ar/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

يمثل نافذة مفتوحة في نسخة من Microsoft Visio. يحتوي هذا العنصر على المعلومات اللازمة لإعادة إنشاء نافذة واجهة المستخدم بدقة في مساحة عمل التطبيق عندما يتم فتح ملف DatadiagramML مبدئياً بواسطة Visio.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Window()](#Window--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | معرّف الحاوية: صفحة، ورقة، أو قالب رئيسي. |
| [getContainerType()](#getContainerType--) | يمكن أن يكون أحد القيم التالية: Document أو Page أو Master. |
| [getDocument()](#getDocument--) | مسار الملف للمستند المعروض في هذه النافذة. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | يحدد ما إذا كانت ميزة الشبكة الديناميكية مفعلة لمستند أو نافذة. |
| [getGlueSettings()](#getGlueSettings--) | يحدد الكائنات التي تلصق إليها الأشكال عندما يكون اللصق مفعلاً في المستند. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getMaster()](#getMaster--) | معرّف القالب إذا كانت هذه النافذة تعرض قالبًا رئيسيًا. |
| [getPage()](#getPage--) | معرّف الصفحة إذا كانت هذه النافذة تعرض صفحة. |
| [getParentWindow()](#getParentWindow--) | معرّف النافذة التي تحتوي على نافذة القالب هذه. |
| [getReadOnly()](#getReadOnly--) | علامة القراءة فقط إذا لم يكن هذا القالب قالب مستند. |
| [getSheet()](#getSheet--) | معرّف الورقة في الحاوية. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | يحدد ما إذا كانت نقاط الاتصال معروضة في النافذة. |
| [getShowGrid()](#getShowGrid--) | يحدد ما إذا كان هناك شبكة معروضة في نافذة الرسم. |
| [getShowGuides()](#getShowGuides--) | يحدد ما إذا كانت الأدلة معروضة في نافذة الرسم. |
| [getShowPageBreaks()](#getShowPageBreaks--) | يحدد ما إذا كانت فواصل الصفحات معروضة في النافذة. |
| [getShowRulers()](#getShowRulers--) | يحدد ما إذا كانت المساطر معروضة في نافذة الرسم. |
| [getSnapAngles()](#getSnapAngles--) | يحتوي على مجموعة من عناصر SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | يحدد ما إذا كان إعداد امتداد الالتقاط المحدد مفعلاً أو معطلاً للنافذة النشطة. |
| [getSnapSettings()](#getSnapSettings--) | يحدد الكائنات التي يلتقط إليها الأشكال عندما يكون الالتقاط مفعلاً في النافذة. |
| [getStencilGroup()](#getStencilGroup--) | يحدد مجموعة نوافذ القوالب المدمجة التي تكون النافذة عضوًا فيها. |
| [getStencilGroupPos()](#getStencilGroupPos--) | يحتوي على عدد صحيح يحدد الموضع النسبي لقالب داخل مجموعة في نافذة. |
| [getTabSplitterPos()](#getTabSplitterPos--) | يحدد عرض تبويب الصفحة في نافذة الرسم (كنسبة من إجمالي عرض نافذة الرسم). |
| [getViewCenterX()](#getViewCenterX--) | قيمة مزدوجة اختيارية. |
| [getViewCenterY()](#getViewCenterY--) | قيمة مزدوجة اختيارية. |
| [getViewScale()](#getViewScale--) | قيمة مزدوجة اختيارية. |
| [getWindowHeight()](#getWindowHeight--) | ارتفاع مستطيل النافذة. |
| [getWindowLeft()](#getWindowLeft--) | الإحداثي الأيسر لمستطيل النافذة. |
| [getWindowState()](#getWindowState--) | يمكن أن يكون هذا السمة مجموعًا للقيم التالية. |
| [getWindowTop()](#getWindowTop--) | الإحداثي العلوي لمستطيل النافذة. |
| [getWindowType()](#getWindowType--) | قيمة تعداد قد تكون واحدة من القيم التالية: Drawing, Sheet, Stencil, أو Icon. يجب أن يظهر عنصر النافذة WindowType='Stencil' بعد نافذة الرسم الأصلية (WindowType='Drawing') وقبل أي عناصر نافذة رسم أخرى. |
| [getWindowWidth()](#getWindowWidth--) | عرض مستطيل النافذة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | لوصف هذه الخاصية، يرجى الاطلاع على [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | لوصف هذه الخاصية، يرجى الاطلاع على [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | لوصف هذه الخاصية، يرجى الاطلاع على [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | لوصف هذه الخاصية، يرجى الاطلاع على [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | لوصف هذه الخاصية، يرجى الاطلاع على [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | لوصف هذه الخاصية، يرجى الاطلاع على [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


منشئ.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
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


معرّف الحاوية: صفحة، ورقة، أو رئيسية. ذو صلة فقط وضروري إذا تم تحديد ContainerType.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


مسار الملف للمستند المعروض في هذه النافذة. هذه الخاصية ذات صلة بالنوافذ التي تم تحديد WindowType لها كـ Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


يحدد ما إذا كانت ميزة الشبكة الديناميكية مفعلة لمستند أو نافذة.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


يحدد الكائنات التي تلصق إليها الأشكال عندما يكون اللصق مفعلاً في المستند.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


معرّف القالب إذا كانت هذه النافذة تعرض قالبًا رئيسيًا.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


معرّف الصفحة إذا كانت هذه النافذة تعرض صفحة. ذات صلة فقط عندما يكون WindowType محددًا كـ Drawing وContainerType محددًا كـ Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


معرّف النافذة التي تحتوي على نافذة القالب هذه. ذات صلة فقط عندما يكون WindowType محددًا كـ Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


علامة القراءة فقط إذا لم يكن هذا القالب قالب مستند.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


معرّف الورقة في الحاوية. ذات صلة فقط عندما تكون Container محددة كـ Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


يحدد ما إذا كانت نقاط الاتصال معروضة في النافذة.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


يحدد ما إذا كان هناك شبكة معروضة في نافذة الرسم.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


يحدد ما إذا كانت الأدلة معروضة في نافذة الرسم.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


يحدد ما إذا كانت فواصل الصفحات معروضة في النافذة.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


يحدد ما إذا كانت المساطر معروضة في نافذة الرسم.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


يحتوي على مجموعة من عناصر SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


يحدد ما إذا كان إعداد امتداد الإلتقاط المحدد مفعلاً أو معطلاً للنافذة النشطة. يمكن أن تكون القيمة مجموع القيم في الجدول التالي.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


يحدد الكائنات التي تُلصق إليها الأشكال عندما يكون اللصق نشطًا في النافذة. قد تكون القيمة مجموعًا للقيم في الجدول التالي.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


يحدد مجموعة نوافذ القالب المدمجة التي تكون النافذة عضوًا فيها. هذه الخاصية ذات صلة فقط بعناصر Window التي تكون خاصية WindowType لها هي Stencil، وفقط إذا كانت نافذة القالب جزءًا من مجموعة مدمجة من نوافذ القالب. جميع نوافذ القالب التي هي جزء من نفس المجموعة المدمجة لها نفس قيمة عنصر StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


يحتوي على عدد صحيح يحدد الموضع النسبي لقالب داخل مجموعة في نافذة.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


يحدد عرض تبويب الصفحة في نافذة الرسم (كنسبة من إجمالي عرض نافذة الرسم).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


قيمة مزدوجة اختيارية.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


قيمة مزدوجة اختيارية.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


قيمة مزدوجة اختيارية.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


ارتفاع مستطيل النافذة.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


الإحداثي الأيسر لمستطيل النافذة.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


يمكن أن يكون هذا السمة مجموعًا للقيم التالية.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


الإحداثي العلوي لمستطيل النافذة.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


قيمة تعداد قد تكون واحدة من القيم التالية: Drawing, Sheet, Stencil, أو Icon. يجب أن يظهر عنصر النافذة WindowType='Stencil' بعد نافذة الرسم الأصلية (WindowType='Drawing') وقبل أي عناصر نافذة رسم أخرى.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


عرض مستطيل النافذة.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

