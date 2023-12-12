---
title: Master
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that define a master for the document.
type: docs
weight: 242
url: /java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Contains elements that define a master for the document. A master is a shape on a stencil that you use repeatedly to create drawings. When you drag a shape from a stencil onto the drawing page, the shape becomes an instance of that master, and a local copy of the master is included in the document.
## Constructors

| Constructor | Description |
| --- | --- |
| [Master()](#Master--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Specifies whether the master's text in the stencil window is aligned left, right, or center. |
| [getBaseID()](#getBaseID--) | A GUID (globally unique identifier) that identifies the master across documents. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contains a Connect element for each connection between two shapes in a drawing. |
| [getHidden()](#getHidden--) | Specifies whether the master is hidden in the user interface. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getIcon()](#getIcon--) | Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShortcut element in a document. |
| [getIconSize()](#getIconSize--) | The size of the element's icon. |
| [getIconUpdate()](#getIconUpdate--) | Specifies whether the icon is automatically generated from the master itself. |
| [getMatchByName()](#getMatchByName--) | The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instance of a master is dropped on the drawing page. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getPageSheet()](#getPageSheet--) | Contains elements that define the page sheet for a Page or Master element. |
| [getPatternFlags()](#getPatternFlags--) | The PatternFlags attribute determines whether a master behaves as a custom pattern. |
| [getPrompt()](#getPrompt--) | The status bar and tool tip prompt for the element. |
| [getShapes()](#getShapes--) | Collection of Shape objects. |
| [getUniqueID()](#getUniqueID--) | A GUID that identifies the master within the document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | For the description of this property, please see [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | For the description of this property, please see [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | For the description of this property, please see [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | For the description of this property, please see [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | For the description of this property, please see [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | For the description of this property, please see [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | For the description of this property, please see [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | For the description of this property, please see [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | For the description of this property, please see [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates deep copy of this instance.

**Returns:**
java.lang.Object - 
### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Specifies whether the master's text in the stencil window is aligned left, right, or center.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


A GUID (globally unique identifier) that identifies the master across documents.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contains a Connect element for each connection between two shapes in a drawing.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Specifies whether the master is hidden in the user interface.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


The unique ID of the element within its parent element.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShortcut element in a document.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


The size of the element's icon.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Specifies whether the icon is automatically generated from the master itself.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instance of a master is dropped on the drawing page. It allows changes made to a document master to apply to new instances of the master, even if the instances are dragged from a stand-alone stencil file.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


The name of the element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


The universal name of the element.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contains elements that define the page sheet for a Page or Master element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


The PatternFlags attribute determines whether a master behaves as a custom pattern.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


The status bar and tool tip prompt for the element.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Collection of Shape objects.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


A GUID that identifies the master within the document.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


For the description of this property, please see [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


For the description of this property, please see [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


For the description of this property, please see [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


For the description of this property, please see [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


For the description of this property, please see [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


For the description of this property, please see [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


For the description of this property, please see [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


For the description of this property, please see [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


For the description of this property, please see [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

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

