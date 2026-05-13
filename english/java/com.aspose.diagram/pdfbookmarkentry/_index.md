---
title: PdfBookmarkEntry
second_title: Aspose.Diagram for Java API Reference
description: PdfBookmarkEntry is an entry in pdf bookmark.
type: docs
weight: 292
url: /java/com.aspose.diagram/pdfbookmarkentry/
---

**Inheritance:**
java.lang.Object
```
public class PdfBookmarkEntry
```

PdfBookmarkEntry is an entry in pdf bookmark. if Text property of current instance is null or "", current instance will be hidden and children will be inserted on current level.

```
Diagram diagram = new Diagram("temp.vsdx");
         PdfSaveOptions options = new PdfSaveOptions();
         PdfBookmarkEntry pbeRoot = new PdfBookmarkEntry();
         pbeRoot.setText("1.vsdx");
         pbeRoot.setDestination(diagram.getPages().get(0));
         pbeRoot.setSubEntry(new ArrayList());
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfBookmarkEntry()](#PdfBookmarkEntry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | The page to which the bookmark link. |
| [getSubEntry()](#getSubEntry--) | SubEntry of a bookmark. |
| [getText()](#getText--) | Title of a bookmark. |
| [hashCode()](#hashCode--) |  |
| [isCollapse()](#isCollapse--) | When this property is true, the bookmarkentry will collapse, otherwise it will expand. |
| [isOpen()](#isOpen--) | When this property is true, the bookmarkentry will expand, otherwise it will collapse. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCollapse(boolean value)](#setCollapse-boolean-) | For the description of this property, please see [isCollapse()](../../com.aspose.diagram/pdfbookmarkentry\#isCollapse--) |
| [setDestination(Page value)](#setDestination-com.aspose.diagram.Page-) | For the description of this property, please see [getDestination()](../../com.aspose.diagram/pdfbookmarkentry\#getDestination--) |
| [setOpen(boolean value)](#setOpen-boolean-) | For the description of this property, please see [isOpen()](../../com.aspose.diagram/pdfbookmarkentry\#isOpen--) |
| [setSubEntry(ArrayList value)](#setSubEntry-java.util.ArrayList-) | For the description of this property, please see [getSubEntry()](../../com.aspose.diagram/pdfbookmarkentry\#getSubEntry--) |
| [setText(String value)](#setText-java.lang.String-) | For the description of this property, please see [getText()](../../com.aspose.diagram/pdfbookmarkentry\#getText--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfBookmarkEntry() {#PdfBookmarkEntry--}
```
public PdfBookmarkEntry()
```


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
### getDestination() {#getDestination--}
```
public Page getDestination()
```


The page to which the bookmark link.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getSubEntry() {#getSubEntry--}
```
public ArrayList getSubEntry()
```


SubEntry of a bookmark.

**Returns:**
java.util.ArrayList
### getText() {#getText--}
```
public String getText()
```


Title of a bookmark.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCollapse() {#isCollapse--}
```
public boolean isCollapse()
```


When this property is true, the bookmarkentry will collapse, otherwise it will expand.

**Returns:**
boolean
### isOpen() {#isOpen--}
```
public boolean isOpen()
```


When this property is true, the bookmarkentry will expand, otherwise it will collapse.

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




### setCollapse(boolean value) {#setCollapse-boolean-}
```
public void setCollapse(boolean value)
```


For the description of this property, please see [isCollapse()](../../com.aspose.diagram/pdfbookmarkentry\#isCollapse--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDestination(Page value) {#setDestination-com.aspose.diagram.Page-}
```
public void setDestination(Page value)
```


For the description of this property, please see [getDestination()](../../com.aspose.diagram/pdfbookmarkentry\#getDestination--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


For the description of this property, please see [isOpen()](../../com.aspose.diagram/pdfbookmarkentry\#isOpen--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSubEntry(ArrayList value) {#setSubEntry-java.util.ArrayList-}
```
public void setSubEntry(ArrayList value)
```


For the description of this property, please see [getSubEntry()](../../com.aspose.diagram/pdfbookmarkentry\#getSubEntry--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.ArrayList |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


For the description of this property, please see [getText()](../../com.aspose.diagram/pdfbookmarkentry\#getText--)

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

