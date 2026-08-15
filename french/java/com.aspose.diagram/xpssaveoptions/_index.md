---
title: XPSSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en XPS.
type: docs
weight: 453
url: /fr/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en XPS.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Définit s'il faut exporter la page cachée ou non. |
| [getPageCount()](#getPageCount--) | le nombre de pages à rendre en XPS. |
| [getPageIndex()](#getPageIndex--) | l'index basé sur zéro de la première page à rendre. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Spécifie si toutes les pages seront enregistrées en image ou uniquement le premier plan. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d'options d'enregistrement est utilisé. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
```


Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat.

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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Définit s'il faut exporter la page cachée ou non. La valeur par défaut est vraie.

**Returns:**
booléen
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


le nombre de pages à rendre en XPS. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


l'index basé sur zéro de la première page à rendre. La valeur par défaut est 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Spécifie si toutes les pages seront enregistrées dans l'image ou seulement le premier plan. Si true - seules les pages de premier plan sont rendues (avec l’arrière‑plan si présent). Si false - les pages de premier plan sont rendues (avec l’arrière‑plan si présent) puis les pages d’arrière‑plan vides. Peut renvoyer true uniquement lorsque PageCount > 1. La valeur par défaut est false.

**Returns:**
booléen
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d’options d’enregistrement est utilisé. Ne peut être que Aspose.Diagram.SaveFileFormat.

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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)

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

