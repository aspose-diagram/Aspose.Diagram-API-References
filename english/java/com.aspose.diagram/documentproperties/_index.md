---
title: DocumentProperties
second_title: Aspose.Diagram for Java API Reference
description: Contains document property elements such as the documents title author and so on.
type: docs
weight: 127
url: /java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

Contains document property elements such as the document's title, author, and so on.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | Specifies the alternate names for a document. |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | Contains the full build number of the instance used to create the document. |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | Contains the build number of the instance last used to edit the document. |
| [getCategory()](#getCategory--) | Specifies the descriptive text for the type of drawing, such as flowchart or office layout. |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | Contains user-entered information identifying the company creating the drawing or the company the drawing is being created for. |
| [getCreator()](#getCreator--) | Identifies who created or last updated the file. |
| [getCustomProps()](#getCustomProps--) | Collection of CustomProp. |
| [getDesc()](#getDesc--) | Contains a descriptive text string for a document. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Contains the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). |
| [getKeywords()](#getKeywords--) | Contains a text string that identifies topics or other important information about the file, such as project name, client name, or version number. |
| [getLanguage()](#getLanguage--) | Specifies the language |
| [getManager()](#getManager--) | Contains a user-entered text string identifying the person in charge of the project or department. |
| [getPreviewPicture()](#getPreviewPicture--) | Contains a metafile stream that serves as a preview of the document. |
| [getSubject()](#getSubject--) | Contains a user-defined text string that describes the contents of the document. |
| [getTemplate()](#getTemplate--) | Contains a string value specifying the file name of the template from which the document was created. |
| [getTimeCreated()](#getTimeCreated--) | Contains date and time value indicating when the document was created. |
| [getTimeEdited()](#getTimeEdited--) | Contains date and time value indicating when the document was last edited. |
| [getTimePrinted()](#getTimePrinted--) | Contains date and time value indicating when the document was last printed. |
| [getTimeSaved()](#getTimeSaved--) | Contains date and time value indicating when the document was last saved. |
| [getTitle()](#getTitle--) | Contains a user-defined text string that serves as a descriptive title for the document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | For the description of this property, please see [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--) |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | For the description of this property, please see [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--) |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | For the description of this property, please see [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--) |
| [setCategory(String value)](#setCategory-java.lang.String-) | For the description of this property, please see [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--) |
| [setCompany(String value)](#setCompany-java.lang.String-) | For the description of this property, please see [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--) |
| [setCreator(String value)](#setCreator-java.lang.String-) | For the description of this property, please see [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--) |
| [setDesc(String value)](#setDesc-java.lang.String-) | For the description of this property, please see [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--) |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | For the description of this property, please see [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--) |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | For the description of this property, please see [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--) |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | For the description of this property, please see [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--) |
| [setManager(String value)](#setManager-java.lang.String-) | For the description of this property, please see [getManager()](../../com.aspose.diagram/documentproperties\#getManager--) |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | For the description of this property, please see [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--) |
| [setSubject(String value)](#setSubject-java.lang.String-) | For the description of this property, please see [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--) |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | For the description of this property, please see [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--) |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--) |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--) |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--) |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | For the description of this property, please see [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


Specifies the alternate names for a document.

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


Contains the full build number of the instance used to create the document.

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


Contains the build number of the instance last used to edit the document.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


Specifies the descriptive text for the type of drawing, such as flowchart or office layout. This text can also be entered in the Microsoft Visio user interface in the Category box in the Properties dialog box.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


Contains user-entered information identifying the company creating the drawing or the company the drawing is being created for. Maximum length is 63 characters.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Identifies who created or last updated the file. The maximum length is 63 characters.

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


Collection of CustomProp.

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


Contains a descriptive text string for a document. Use this element to store important information about the document, such as its purpose, recent changes, or pending changes. The maximum is 191 characters.

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


Contains the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). By default, a hyperlink path is relative to the current document unless a different path is specified in this element. Maximum length is 256 characters.

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Contains a text string that identifies topics or other important information about the file, such as project name, client name, or version number. The maximum string length is 63 characters.

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


Specifies the language

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


Contains a user-entered text string identifying the person in charge of the project or department. The maximum length is 63 characters.

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


Contains a metafile stream that serves as a preview of the document.

**Returns:**
byte[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


Contains a user-defined text string that describes the contents of the document. Maximum length is 63 characters.

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


Contains a string value specifying the file name of the template from which the document was created.

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


Contains date and time value indicating when the document was created.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


Contains date and time value indicating when the document was last edited.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


Contains date and time value indicating when the document was last printed.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


Contains date and time value indicating when the document was last saved.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


Contains a user-defined text string that serves as a descriptive title for the document. Maximum length is 63 characters.

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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


For the description of this property, please see [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


For the description of this property, please see [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


For the description of this property, please see [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


For the description of this property, please see [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


For the description of this property, please see [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


For the description of this property, please see [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


For the description of this property, please see [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


For the description of this property, please see [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


For the description of this property, please see [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


For the description of this property, please see [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


For the description of this property, please see [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


For the description of this property, please see [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


For the description of this property, please see [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


For the description of this property, please see [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


For the description of this property, please see [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


For the description of this property, please see [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


For the description of this property, please see [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


For the description of this property, please see [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


For the description of this property, please see [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

