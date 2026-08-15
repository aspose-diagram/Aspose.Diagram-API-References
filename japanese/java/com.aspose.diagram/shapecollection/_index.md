---
title: ShapeCollection
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプのコレクション。
type: docs
weight: 356
url: /ja/java/com.aspose.diagram/shapecollection/
---

**Inheritance:**
java.lang.Object、[com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class ShapeCollection extends Collection
```

シェイプのコレクション。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(Shape item)](#add-com.aspose.diagram.Shape-) | コレクションにシェイプを追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | 指定されたインデックスの要素を取得します。 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [getShape(String name)](#getShape-java.lang.String-) | 指定された名前の要素を取得します。 |
| [getShape(long ID)](#getShape-long-) | 指定された ID の要素を取得します。 |
| [getShapeIncludingChild(int id)](#getShapeIncludingChild-int-) | 指定された ID の子シェイプを含む要素を取得します。 |
| [getShapeIncludingChild(String name)](#getShapeIncludingChild-java.lang.String-) | 指定された名前の子シェイプを含む要素を取得します。 |
| [group(Shape[] groupItems)](#group-com.aspose.diagram.Shape---) | シェイプをグループ化します。 |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | コレクションに項目が存在するかどうかを確認します。 |
| [iterator()](#iterator--) | ジェネリックではないコレクションに対するシンプルな反復をサポートします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Shape item)](#remove-com.aspose.diagram.Shape-) | Remove the shape from the collection. |
| [removeDependsOn(Shape item)](#removeDependsOn-com.aspose.diagram.Shape-) | Remove the shapes including DEPENDSON shapes from the collection. |
| [toString()](#toString--) |  |
| [unGroup(Shape groupShape)](#unGroup-com.aspose.diagram.Shape-) | UnGroup the shape. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Shape item) {#add-com.aspose.diagram.Shape-}
```
public int add(Shape item)
```


コレクションにシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int - ID
### clear() {#clear--}
```
public void clear()
```


コレクションからすべての要素を削除します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Shape get(int index)
```


指定されたインデックスの要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
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


コレクションに実際に含まれる要素数を取得します。

**Returns:**
int
### getShape(String name) {#getShape-java.lang.String-}
```
public Shape getShape(String name)
```


指定された名前の要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShape(long ID) {#getShape-long-}
```
public Shape getShape(long ID)
```


指定された ID の要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ID | long |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(int id) {#getShapeIncludingChild-int-}
```
public Shape getShapeIncludingChild(int id)
```


指定された ID の子シェイプを含む要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | int |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### getShapeIncludingChild(String name) {#getShapeIncludingChild-java.lang.String-}
```
public Shape getShapeIncludingChild(String name)
```


指定された名前の子シェイプを含む要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - 
### group(Shape[] groupItems) {#group-com.aspose.diagram.Shape---}
```
public Shape group(Shape[] groupItems)
```


Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| groupItems | [Shape\[\]](../../com.aspose.diagram/shape) | the group items. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Return the group shape.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


コレクションに項目が存在するかどうかを確認します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | 要素のインデックス。 |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


ジェネリックではないコレクションに対するシンプルな反復をサポートします。

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Shape item) {#remove-com.aspose.diagram.Shape-}
```
public void remove(Shape item)
```


Remove the shape from the collection.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### removeDependsOn(Shape item) {#removeDependsOn-com.aspose.diagram.Shape-}
```
public void removeDependsOn(Shape item)
```


Remove the shapes including DEPENDSON shapes from the collection.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [Shape](../../com.aspose.diagram/shape) | Shape |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unGroup(Shape groupShape) {#unGroup-com.aspose.diagram.Shape-}
```
public void unGroup(Shape groupShape)
```


UnGroup the shape.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| groupShape | [Shape](../../com.aspose.diagram/shape) | the group shape. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

