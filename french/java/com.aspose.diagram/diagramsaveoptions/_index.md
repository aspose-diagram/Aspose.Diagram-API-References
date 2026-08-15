---
title: DiagramSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Peut être utilisé pour spécifier des options supplémentaires lors de l'enregistrement d'un diagramme au format Visio VDXVSX.
type: docs
weight: 119
url: /fr/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Peut être utilisé pour spécifier des options supplémentaires lors de l'enregistrement d'un diagramme au format Visio (VDX\VSX). Pour le moment, il ne fournit que la propriété SaveFormat, mais d'autres options seront ajoutées à l'avenir.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un diagramme au format VDX. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un diagramme au format VDX ou VSX. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | Définit s'il faut agrandir la page pour adapter le contenu du dessin ou non. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel le diagramme rendu sera enregistré si cet objet d'options d'enregistrement est utilisé. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | Pour la description de cette propriété, veuillez consulter [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un diagramme au format VDX.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un diagramme au format VDX ou VSX.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveFormat | int |  |

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveFormat | int | Le Aspose.Diagram.SaveFileFormat pour lequel créer un objet d'options d'enregistrement. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


Définit s'il faut agrandir la page pour adapter le contenu du dessin ou non. La valeur par défaut est false.

**Returns:**
booléen
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. Définissez la DefaultFont, telle que MingLiu ou MS Gothic, pour afficher ces caractères.

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Spécifie le format dans lequel le diagramme rendu sera enregistré si cet objet d'options d'enregistrement est utilisé. Peut être Aspose.Diagram.SaveFileFormat ou Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


fonction de rappel d'avertissement.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setAutoFitPageToDrawingContent(boolean value) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

