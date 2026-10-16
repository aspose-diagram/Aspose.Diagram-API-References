---
title: ContainerProperties
second_title: Aspose.Diagram for Java API Reference
description: ContainerProperties for shape.
type: docs
weight: 87
url: /java/com.aspose.diagram/containerproperties/
---

**Inheritance:**
java.lang.Object
```
public class ContainerProperties
```

ContainerProperties for shape. Implements the Microsoft Visio structured-diagram container model:

    | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | /// Container identity, style and behavior are stored in User-defined cells: /// msvStructureType ("Container" / "List"), msvSDContainerStyle, msvSDHeadingStyle, /// msvSDContainerMargin, msvSDContainerLocked, msvSDContainerResize. ///                                                                   |
    | /// Membership is stored in the Layout section's Relationships cell, exactly as Microsoft /// Visio persists it: the container keeps SUM(DEPENDSON(1, Sheet.N!SheetRef(),...)) /// (category 2 for lists) and each member keeps SUM(DEPENDSON(4, Sheet.N!SheetRef())) /// pointing back to the container. /// |

    |
## Constructors

| Constructor | Description |
| --- | --- |
| [ContainerProperties(Shape parentShape)](#ContainerProperties-com.aspose.diagram.Shape-) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [addMember(Shape shape)](#addMember-com.aspose.diagram.Shape-) | Add Member to container Writes the same Relationships cells Microsoft Visio writes when a shape is dropped onto a container: DEPENDSON(4, Sheet.N! |
| [clearMembers()](#clearMembers--) | clear members Removes the container's member references and the matching DEPENDSON(4,...) reference on every member. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainerStyle()](#getContainerStyle--) | ContainerStyle The value of the msvSDContainerStyle cell. |
| [getContainerType()](#getContainerType--) | ContainerType Stored in the msvStructureType cell as "Container" or "List", so the type survives save/reload. |
| [getHeadingStyle()](#getHeadingStyle--) | HeadingStyle The value of the msvSDHeadingStyle cell: 0 = no heading, 1 - 4 = heading styles. |
| [getLockMembership()](#getLockMembership--) | LockMembership The value of the msvSDContainerLocked cell. |
| [getMargin()](#getMargin--) | ContainerMargin The value of the msvSDContainerMargin cell. |
| [getMemberShapes()](#getMemberShapes--) | get member shapes Reads the container's own DEPENDSON(1,...) references (DEPENDSON(2,...) for lists). |
| [getResizeAsNeeded()](#getResizeAsNeeded--) | ResizeAsNeeded The value of the msvSDContainerResize cell: false = do not resize the container to fit its members, true = resize as needed. |
| [getShape()](#getShape--) | Parent shape |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeMember(Shape shape)](#removeMember-com.aspose.diagram.Shape-) | RemoveMember |
| [setContainerStyle(int value)](#setContainerStyle-int-) | For the description of this property, please see [getContainerStyle()](../../com.aspose.diagram/containerproperties\#getContainerStyle--) |
| [setContainerType(int value)](#setContainerType-int-) | For the description of this property, please see [getContainerType()](../../com.aspose.diagram/containerproperties\#getContainerType--) |
| [setHeadingStyle(int value)](#setHeadingStyle-int-) | For the description of this property, please see [getHeadingStyle()](../../com.aspose.diagram/containerproperties\#getHeadingStyle--) |
| [setLockMembership(boolean value)](#setLockMembership-boolean-) | For the description of this property, please see [getLockMembership()](../../com.aspose.diagram/containerproperties\#getLockMembership--) |
| [setMargin(double value)](#setMargin-double-) | For the description of this property, please see [getMargin()](../../com.aspose.diagram/containerproperties\#getMargin--) |
| [setResizeAsNeeded(boolean value)](#setResizeAsNeeded-boolean-) | For the description of this property, please see [getResizeAsNeeded()](../../com.aspose.diagram/containerproperties\#getResizeAsNeeded--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContainerProperties(Shape parentShape) {#ContainerProperties-com.aspose.diagram.Shape-}
```
public ContainerProperties(Shape parentShape)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentShape | [Shape](../../com.aspose.diagram/shape) |  |

### addMember(Shape shape) {#addMember-com.aspose.diagram.Shape-}
```
public void addMember(Shape shape)
```


Add Member to container Writes the same Relationships cells Microsoft Visio writes when a shape is dropped onto a container: DEPENDSON(4, Sheet.N!SheetRef()) on the member and DEPENDSON(1, Sheet.N!SheetRef()) on the container (DEPENDSON(2,...) for lists). A shape belongs to a single container in Visio, so existing container membership is removed first, unless the previous container is locked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape to add |

### clearMembers() {#clearMembers--}
```
public void clearMembers()
```


clear members Removes the container's member references and the matching DEPENDSON(4,...) reference on every member. Does nothing when LockMembership is set.

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
### getContainerStyle() {#getContainerStyle--}
```
public int getContainerStyle()
```


ContainerStyle The value of the msvSDContainerStyle cell. Microsoft Visio itself only stores this number; the visual appearance is calculated by the container master's formulas when the document is opened in Visio, so no shape re-creation is required on change.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


ContainerType Stored in the msvStructureType cell as "Container" or "List", so the type survives save/reload. When the type changes, existing membership references are moved between the container category (1) and the list category (2) of the Relationships cell.

**Returns:**
int
### getHeadingStyle() {#getHeadingStyle--}
```
public int getHeadingStyle()
```


HeadingStyle The value of the msvSDHeadingStyle cell: 0 = no heading, 1 - 4 = heading styles.

**Returns:**
int
### getLockMembership() {#getLockMembership--}
```
public boolean getLockMembership()
```


LockMembership The value of the msvSDContainerLocked cell. When set, AddMember, RemoveMember and ClearMembers do nothing, matching the behavior of Microsoft Visio, which prevents membership changes on a locked container.

**Returns:**
boolean
### getMargin() {#getMargin--}
```
public double getMargin()
```


ContainerMargin The value of the msvSDContainerMargin cell. The unit is defined by the cell's unit attribute; the value is written as a plain number.

**Returns:**
double
### getMemberShapes() {#getMemberShapes--}
```
public ShapeCollection getMemberShapes()
```


get member shapes Reads the container's own DEPENDSON(1,...) references (DEPENDSON(2,...) for lists). Unlike the DependsOnShapes inverse lookup this resolves shape names with spaces and parentheses, so it also works for documents written by Microsoft Visio.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection) - shapecollection
### getResizeAsNeeded() {#getResizeAsNeeded--}
```
public boolean getResizeAsNeeded()
```


ResizeAsNeeded The value of the msvSDContainerResize cell: false = do not resize the container to fit its members, true = resize as needed.

**Returns:**
boolean
### getShape() {#getShape--}
```
public Shape getShape()
```


Parent shape

**Returns:**
[Shape](../../com.aspose.diagram/shape)
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




### removeMember(Shape shape) {#removeMember-com.aspose.diagram.Shape-}
```
public void removeMember(Shape shape)
```


RemoveMember

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape to remove |

### setContainerStyle(int value) {#setContainerStyle-int-}
```
public void setContainerStyle(int value)
```


For the description of this property, please see [getContainerStyle()](../../com.aspose.diagram/containerproperties\#getContainerStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


For the description of this property, please see [getContainerType()](../../com.aspose.diagram/containerproperties\#getContainerType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeadingStyle(int value) {#setHeadingStyle-int-}
```
public void setHeadingStyle(int value)
```


For the description of this property, please see [getHeadingStyle()](../../com.aspose.diagram/containerproperties\#getHeadingStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLockMembership(boolean value) {#setLockMembership-boolean-}
```
public void setLockMembership(boolean value)
```


For the description of this property, please see [getLockMembership()](../../com.aspose.diagram/containerproperties\#getLockMembership--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMargin(double value) {#setMargin-double-}
```
public void setMargin(double value)
```


For the description of this property, please see [getMargin()](../../com.aspose.diagram/containerproperties\#getMargin--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setResizeAsNeeded(boolean value) {#setResizeAsNeeded-boolean-}
```
public void setResizeAsNeeded(boolean value)
```


For the description of this property, please see [getResizeAsNeeded()](../../com.aspose.diagram/containerproperties\#getResizeAsNeeded--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

