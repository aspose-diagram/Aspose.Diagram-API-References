---
title: VbaProject
second_title: Aspose.Diagram for Java API Reference
description: Represents the VBA project.
type: docs
weight: 455
url: /java/com.aspose.diagram/vbaproject/
---

**Inheritance:**
java.lang.Object
```
public class VbaProject
```

Represents the VBA project.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getModules()](#getModules--) | Gets all [VbaModule](../../com.aspose.diagram/vbamodule) objects. |
| [getName()](#getName--) | the name of the VBA project. |
| [getReferences()](#getReferences--) | Gets all references of VBA project. |
| [hashCode()](#hashCode--) |  |
| [isProtected()](#isProtected--) | Indicates whether this VBA project is protected. |
| [isSigned()](#isSigned--) | Indicates whether VBAcode is signed or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [protect(boolean islockedForViewing, String password)](#protect-boolean-java.lang.String-) | Protects or unprotects this VBA project. |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/vbaproject\#getName--) |
| [toString()](#toString--) |  |
| [validatePassword(String password)](#validatePassword-java.lang.String-) | Validates protection password. |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getModules() {#getModules--}
```
public VbaModuleCollection getModules()
```


Gets all [VbaModule](../../com.aspose.diagram/vbamodule) objects.

**Returns:**
[VbaModuleCollection](../../com.aspose.diagram/vbamodulecollection)
### getName() {#getName--}
```
public String getName()
```


the name of the VBA project.

**Returns:**
java.lang.String
### getReferences() {#getReferences--}
```
public VbaProjectReferenceCollection getReferences()
```


Gets all references of VBA project.

**Returns:**
[VbaProjectReferenceCollection](../../com.aspose.diagram/vbaprojectreferencecollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isProtected() {#isProtected--}
```
public boolean isProtected()
```


Indicates whether this VBA project is protected.

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Indicates whether VBAcode is signed or not.

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




### protect(boolean islockedForViewing, String password) {#protect-boolean-java.lang.String-}
```
public void protect(boolean islockedForViewing, String password)
```


Protects or unprotects this VBA project. If islockedForViewing is true, the password could not be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| islockedForViewing | boolean | indicates whether locks project for viewing. |
| password | java.lang.String | If the value is null, unprotects this VBA project, otherwise protect this VBA project. |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/vbaproject\#getName--)

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
### validatePassword(String password) {#validatePassword-java.lang.String-}
```
public boolean validatePassword(String password)
```


Validates protection password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | the password |

**Returns:**
boolean - Whether password is the protection password of this VBA project
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

