---
title: ForeignData
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient un BLOB encodé en MIME Multipurpose Internet Mail Extensions de données d'image telles qu'un bitmap de métafichier Windows ou des données OLE.
type: docs
weight: 164
url: /fr/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE.
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Cet attribut n'a de sens que si les données étrangères sont un objet externe basé sur le raster, tel qu'un fichier DIB, JPG, PNG, TIFF ou GIF. |
| [getCompressionType()](#getCompressionType--) | Cet attribut n'a de sens que si les données étrangères sont un objet externe basé sur le raster, tel qu'un fichier DIB, JPG, PNG, TIFF ou GIF. |
| [getExtentX()](#getExtentX--) | Cet attribut n'a de sens que si les données étrangères sont un métafichier. |
| [getExtentY()](#getExtentY--) | Cet attribut n'a de sens que si les données étrangères sont un métafichier. |
| [getForeignType()](#getForeignType--) | Type de données. |
| [getImageData()](#getImageData--) | Représente l'image d'un objet ole sous forme de tableau d'octets. |
| [getMappingMode()](#getMappingMode--) | Cet attribut n'a de sens que si les données étrangères sont un métafichier. |
| [getObjectData()](#getObjectData--) | Représente les données d'objet ole incorporées sous forme de tableau d'octets. |
| [getObjectHeight()](#getObjectHeight--) | Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Renvoie le nom complet source du fichier source pour l'objet OLE lié. |
| [getObjectType()](#getObjectType--) | Si l'attribut ForeignType est "Object", l'élément ForeignData doit également posséder un attribut ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré. |
| [getShowAsIcon()](#getShowAsIcon--) | Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré. |
| [getValue()](#getValue--) | Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Pour la description de cette propriété, veuillez consulter [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Pour la description de cette propriété, veuillez consulter [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Pour la description de cette propriété, veuillez consulter [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Pour la description de cette propriété, veuillez consulter [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Pour la description de cette propriété, veuillez consulter [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Pour la description de cette propriété, veuillez consulter [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Pour la description de cette propriété, veuillez consulter [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Pour la description de cette propriété, veuillez consulter [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Pour la description de cette propriété, veuillez consulter [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Pour la description de cette propriété, veuillez consulter [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Pour la description de cette propriété, veuillez consulter [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Pour la description de cette propriété, veuillez consulter [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Pour la description de cette propriété, veuillez consulter [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie profonde de cette instance.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


Cet attribut n'a de sens que si les données étrangères sont un objet étranger basé sur le raster, tel qu'un fichier DIB, JPG, PNG, TIFF ou GIF. La valeur indique le niveau de compression appliqué au fichier. Le niveau de compression est mesuré en centièmes de pour cent.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Cet attribut n'a de sens que si les données étrangères sont un objet étranger basé sur le raster, tel qu'un fichier DIB, JPG, PNG, TIFF ou GIF. La valeur indique le type de compression appliqué au fichier.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Cet attribut n'a de sens que si les données étrangères sont un métafichier. La valeur indique l'étendue horizontale du métafichier.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Cet attribut n'a de sens que si les données étrangères sont un métafichier. La valeur indique l'étendue verticale du métafichier.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Type de données.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Représente l'image d'un objet ole sous forme de tableau d'octets.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Cet attribut n'a de sens que si les données étrangères sont un métafichier. La valeur indique le mode de cartographie du métafichier.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Représente les données d'objet ole incorporées sous forme de tableau d'octets.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré. La valeur indique la hauteur de l'objet en unités de page.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Renvoie le nom complet source du fichier source pour l'objet OLE lié. Ne prend en charge la définition du nom complet source que lorsque le type de fichier est OleFileType.Unknown. Par exemple les fichiers wav, avi, etc.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Si l'attribut ForeignType est "Object", l'élément ForeignData doit également posséder un attribut ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré. La valeur indique la largeur de l'objet en unités de page.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Cet attribut n'a de sens que si les données étrangères sont un objet OLE2 intégré.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE.

**Returns:**
byte[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


Pour la description de cette propriété, veuillez consulter [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Pour la description de cette propriété, veuillez consulter [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Pour la description de cette propriété, veuillez consulter [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Pour la description de cette propriété, veuillez consulter [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Pour la description de cette propriété, veuillez consulter [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Pour la description de cette propriété, veuillez consulter [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Pour la description de cette propriété, veuillez consulter [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Pour la description de cette propriété, veuillez consulter [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Pour la description de cette propriété, veuillez consulter [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

