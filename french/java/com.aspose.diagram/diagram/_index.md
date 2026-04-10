---
title: Diagramme
second_title: Référence API d'Aspose.Diagram pour Java
description: Élément racine de la hiérarchie des objets Visio.
type: docs
weight: 117
url: /fr/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Élément racine de la hiérarchie des objets Visio.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Constructeur public de classe, charge le diagramme depuis le fichier. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Constructeur public de classe, charge le diagramme depuis le flux. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Constructeur public de classe, charge le diagramme depuis le flux en utilisant le format prédéfini. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Constructeur public de classe, charge le diagramme depuis le flux en utilisant les options de chargement de fichier prédéfinies. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Constructeur public de classe, charge le diagramme depuis le fichier en utilisant le format prédéfini. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Constructeur public de classe, charge le diagramme depuis le fichier en utilisant les options de chargement de fichier prédéfinies. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Ajoute le master au diagramme à partir du diagramme source par le Nom ou NameU du master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Ajoute le master au diagramme à partir du flux de modèle par l'ID du master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Ajoute le master au diagramme à partir du flux de modèle par le Nom ou NameU du master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Ajoute le master au diagramme à partir du fichier de modèle par l'ID du master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Ajoute le master au diagramme à partir du fichier de modèle par le Nom ou NameU du master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Ajoute une forme créée par le maître à une page spécifique. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Ajoute une forme créée par le maître sur la page avec PinX,PinY, largeur et hauteur définis. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Ajoute une forme créée par le maître sur la page avec PinX et PinY définis. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Combine un autre objet Diagramme. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Copie le thème d'un diagramme source. |
| [dispose()](#dispose--) | Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exporte le diagramme d'un flux vsd vers le format de flux vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exporte le diagramme d'un flux vsd vers le format de fichier *.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exporte le diagramme d'un fichier vsd vers le format de flux vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exporte le diagramme de vsd vers le format vdw. |
| [getActivePage()](#getActivePage--) | Spécifie la page active |
| [getBuildnum()](#getBuildnum--) | Le numéro de build de l'instance Visio utilisée pour créer le document. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Contient la table de couleurs du document. |
| [getDataConnections()](#getDataConnections--) | Contient les éléments DataConnection du document. |
| [getDataRecordSets()](#getDataRecordSets--) | La collection d'objets DataRecordset associés à un objet Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Obtenir le chemin du dossier des polices par défaut |
| [getDocLangID()](#getDocLangID--) | L'ID unique de la langue de l'interface utilisateur que l'utilisateur a spécifiée dans les préférences linguistiques de Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Contient des éléments de propriétés du document tels que le titre du document, l'auteur, etc. |
| [getDocumentSettings()](#getDocumentSettings--) | Contient des éléments qui spécifient les paramètres du document. |
| [getDocumentSheet()](#getDocumentSheet--) | Spécifie la structure ShapeSheet d'un document. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Contient un bordereau d'acheminement d'e-mail MAPI encodé en MIME (Multipurpose Internet Mail Extensions) pour le document. |
| [getEventItems()](#getEventItems--) | Contient un élément EventItem pour chaque événement auquel un objet doit répondre. |
| [getFonts()](#getFonts--) | Contient une collection d'éléments Font |
| [getHeaderFooter()](#getHeaderFooter--) | Contient les éléments d’en-tête et de pied de page d’un document. |
| [getInterruptMonitor()](#getInterruptMonitor--) | le moniteur d'interruption. |
| [getKey()](#getKey--) | Indique si le document a été modifié en dehors de Visio. |
| [getMasters()](#getMasters--) | Collection d'objets Master. |
| [getMetric()](#getMetric--) | Indique s'il faut utiliser des unités métriques dans le dessin. |
| [getPages()](#getPages--) | Collection d'objets Page. |
| [getRibbonX()](#getRibbonX--) | La chaîne XML du ruban qui est transmise au document pour personnaliser l'interface utilisateur du ruban. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Valeur XML. |
| [getStart()](#getStart--) | Indique si le document a été modifié en dehors de Visio. |
| [getStyleSheets()](#getStyleSheets--) | Collection d'objets StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Obtenir les styles inutilisés |
| [getUserCustomUI()](#getUserCustomUI--) | La chaîne XML du ruban qui est transmise au document pour personnaliser la barre d'accès rapide ou le ruban. |
| [getValidation()](#getValidation--) | Stocke des informations sur la validation du diagramme pour le document. |
| [getVbProjectData()](#getVbProjectData--) | Contient les données du projet Microsoft Visual Basic for Applications au format encodé MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Obtient le VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Le numéro de version de l'instance Visio. |
| [getWindows()](#getWindows--) | Contient les éléments Window d'un document. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Indique si ce diagramme contient des informations cachées. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Dispose les formes et/ou redirige les connecteurs pour toutes les pages du diagramme. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Imprime le document complet sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (sans interface utilisateur). |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Imprime le document complet sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (sans interface utilisateur). |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Imprime le document, en utilisant le contrôleur d'impression standard (sans interface utilisateur) et un nom de document. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Imprime le document, en utilisant le contrôleur d'impression standard (sans interface utilisateur) et un nom de document. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Supprimer les informations inutilisées |
| [removeMacro()](#removeMacro--) | Supprime le VBA/macro de ce diagramme. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Enregistre le diagramme dans le flux. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre le diagramme dans le flux. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Enregistre le document dans un fichier en utilisant les options d'enregistrement spécifiées. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Enregistre les données du diagramme dans le fichier. |
| [setBuildnum(long value)](#setBuildnum-long-) | Pour la description de cette propriété, veuillez consulter [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Pour la description de cette propriété, veuillez consulter [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Pour la description de cette propriété, veuillez consulter [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Indique le chemin du dossier Fonts |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Pour la description de cette propriété, veuillez consulter [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Pour la description de cette propriété, veuillez consulter [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Pour la description de cette propriété, veuillez consulter [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Pour la description de cette propriété, veuillez consulter [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Constructeur public de classe, charge le diagramme depuis le fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Constructeur public de classe, charge le diagramme depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de données. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Constructeur public de classe, charge le diagramme depuis le flux en utilisant le format prédéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de données. |
| format | int | Les données Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Constructeur public de classe, charge le diagramme depuis le flux en utilisant les options de chargement de fichier prédéfinies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de données. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Les données [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Constructeur public de classe, charge le diagramme depuis le fichier en utilisant le format prédéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier. |
| format | int | Le format de fichier. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Constructeur public de classe, charge le diagramme depuis le fichier en utilisant les options de chargement de fichier prédéfinies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Les données [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Ajoute le master au diagramme à partir du diagramme source par le Nom ou NameU du master.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | diagramme source. |
| masterName | java.lang.String | Nom du maître ou NameU. |

**Returns:**
int - L'ID unique du maître dans la collection des maîtres de ce diagramme.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Ajoute le master au diagramme à partir du flux de modèle par l'ID du master.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templateStream | java.io.InputStream | flux du modèle. |
| masterID | int | L'ID unique du maître dans la collection des maîtres du modèle. |

**Returns:**
int - L'ID unique du maître dans la collection des maîtres de ce diagramme.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Ajoute le master au diagramme à partir du flux de modèle par le Nom ou NameU du master.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templateStream | java.io.InputStream | flux du modèle. |
| masterName | java.lang.String | Nom du maître ou NameU. |

**Returns:**
int - L'ID unique du maître dans la collection des maîtres de ce diagramme.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Ajoute le master au diagramme à partir du fichier de modèle par l'ID du master.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templateFilePath | java.lang.String | Chemin du fichier modèle (peut être au format vdx, vst ou vsd). |
| masterID | int | L'ID unique du maître dans la collection des maîtres du modèle. |

**Returns:**
int - L'ID unique du maître dans la collection des maîtres de ce diagramme.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Ajoute le master au diagramme à partir du fichier de modèle par le Nom ou NameU du master.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templateFilePath | java.lang.String | Chemin du fichier modèle (peut être au format vdx, vst ou vsd). |
| masterName | java.lang.String | Nom du maître ou NameU. |

**Returns:**
int - L'ID unique du maître dans la collection des maîtres de ce diagramme.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Ajoute une forme créée par le maître à une page spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nouvel objet forme[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nom du maître. |
| pageNumber | int | Index de la page. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Ajoute une forme créée par le maître sur la page avec PinX,PinY, largeur et hauteur définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme en pouces. |
| hauteur | double | Spécifie la hauteur de la forme en pouces. |
| masterName | java.lang.String | Nom du maître. |
| pageNumber | int | Index de la page. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Ajoute une forme créée par le maître sur la page avec PinX et PinY définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| masterName | java.lang.String | Nom du maître. |
| pageNumber | int | Index de la page. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Combine un autre objet Diagramme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Un autre objet Diagram. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Copie le thème d'un diagramme source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | diagramme source. |

### dispose() {#dispose--}
```
public void dispose()
```


Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exporte le diagramme du flux vsd vers le format de flux vdw. Pas encore implémenté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputVsd | java.io.InputStream | flux vsd. |
| outputVdw | java.io.InputStream | flux vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exporte le diagramme du flux vsd vers le format de fichier \*.vdw. Pas encore implémenté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Nom de fichier \*.vsd. |
| outputVdw | java.lang.String | flux vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exporte le diagramme du fichier vsd vers le format de flux vdw. Pas encore implémenté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputVsd | java.lang.String | Nom de fichier \*.vsd. |
| outputVdw | java.io.InputStream | flux vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exporte le diagramme de vsd vers le format vdw. Pas encore implémenté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputVsd | java.lang.String | Nom de fichier \*.vsd. |
| outputVdw | java.lang.String | Nom de fichier \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Spécifie la page active

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Le numéro de build de l'instance Visio utilisée pour créer le document.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Contient la table des couleurs du document. Chaque document contient une seule table des couleurs, qui répertorie les 24 couleurs standard disponibles pour être appliquées aux objets tels que les formes, le texte et les calques du document.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Contient les éléments DataConnection du document.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


La collection d'objets DataRecordset associés à un objet Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Obtenir le chemin du dossier des polices par défaut

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


L'ID unique de la langue de l'interface utilisateur que l'utilisateur a spécifiée dans les préférences linguistiques de Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Contient des éléments de propriétés du document tels que le titre du document, l'auteur, etc.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Contient des éléments qui spécifient les paramètres du document.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Spécifie la structure ShapeSheet d'un document.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Contient un bordereau d'acheminement d'e-mail MAPI encodé en MIME (Multipurpose Internet Mail Extensions) pour le document.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Contient un élément EventItem pour chaque événement auquel un objet doit répondre.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Contient une collection d'éléments Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Contient les éléments d’en-tête et de pied de page d’un document.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


le moniteur d'interruption.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Indique si le document a été modifié en dehors de Visio. Si présent, Visio testera entièrement le contenu du fichier. Omettre pour les fichiers créés en dehors de Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Collection d'objets Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Indique s'il faut utiliser des unités métriques dans le dessin. Définissez cet attribut à True (1) pour utiliser les unités métriques ; définissez-le à False (0) pour utiliser les unités anglaises.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Collection d'objets Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


La chaîne XML du ruban qui est transmise au document pour personnaliser l'interface utilisateur du ruban.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Valeur XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Indique si le document a été modifié en dehors de Visio. Si présent, Visio testera entièrement le contenu du fichier. Omettre pour les fichiers créés en dehors de Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Collection d'objets StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Obtenir les styles inutilisés

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


La chaîne XML du ruban qui est transmise au document pour personnaliser la barre d'accès rapide ou le ruban.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Stocke des informations sur la validation du diagramme pour le document.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Contient les données du projet Microsoft Visual Basic for Applications au format encodé MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Obtient le VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Le numéro de version de l'instance Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Contient les éléments Window d'un document.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Indique si ce diagramme contient des informations cachées.

**Returns:**
booléen
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Dispose les formes et/ou redirige les connecteurs pour toutes les pages du diagramme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Utilisation de [LayoutOptions](../../com.aspose.diagram/layoutoptions) pour configurer les options de mise en page. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Imprime le document complet sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (sans interface utilisateur). Si printerName est Null ou vide, l'imprimante par défaut sera utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | Le nom de l'imprimante. Peut être Null |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Imprime le document complet sur l'imprimante spécifiée, en utilisant le contrôleur d'impression standard (sans interface utilisateur). Si printerName est Null ou vide, l'imprimante par défaut sera utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | Le nom de l'imprimante. Peut être Null |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Les options d'impression. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Imprime le document, en utilisant le contrôleur d'impression standard (sans interface utilisateur) et un nom de document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | Le nom de l'imprimante. Peut être Null |
| documentName | java.lang.String | Le nom du document à afficher (par exemple, dans une boîte de dialogue d'état d'impression ou dans la file d'attente de l'imprimante) lors de l'impression du document. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Imprime le document, en utilisant le contrôleur d'impression standard (sans interface utilisateur) et un nom de document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | Le nom de l'imprimante. Peut être Null |
| documentName | java.lang.String | Le nom du document à afficher (par exemple, dans une boîte de dialogue d'état d'impression ou dans la file d'attente de l'imprimante) lors de l'impression du document. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Les options d'impression. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Supprimer les informations inutilisées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | int | Supprimer l'élément d'information cachée. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Supprime le VBA/macro de ce diagramme.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Enregistre le diagramme dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux de fichier. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Les options d'enregistrement. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Enregistre le diagramme dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux de fichier. |
| format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Enregistre le document dans un fichier en utilisant les options d'enregistrement spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) options d'enregistrement du diagramme. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Enregistre les données du diagramme dans le fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Le nom du fichier. |
| format | int | Aspose.Diagram.SaveFileFormat format de fichier d'enregistrement. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Pour la description de cette propriété, veuillez consulter [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Pour la description de cette propriété, veuillez consulter [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Indique le chemin du dossier Fonts

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Pour la description de cette propriété, veuillez consulter [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Pour la description de cette propriété, veuillez consulter [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Pour la description de cette propriété, veuillez consulter [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Pour la description de cette propriété, veuillez consulter [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Pour la description de cette propriété, veuillez consulter [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Pour la description de cette propriété, veuillez consulter [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Pour la description de cette propriété, veuillez consulter [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

