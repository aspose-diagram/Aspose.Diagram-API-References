---
title: PdfPermissions
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Spécifie les autorisations utilisateur pour le document PDF.
type: docs
weight: 3400
url: /fr/net/aspose.diagram.saving/pdfpermissions/
---
## PdfPermissions enumeration

Spécifie les autorisations utilisateur pour le document PDF.

```csharp
[Flags]
public enum PdfPermissions
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| DisallowAll | `0` | Interdit toutes les opérations sur le document PDF. Ceci est la valeur par défault. |
| Printing | `4` | Permet d'imprimer le document. |
| ModifyContents | `8` | Permet de modifier le contenu du document. |
| ContentCopy | `10` | Permet de copier ou d'extraire du texte et des graphiques du document, y compris l'extraction à des fins d'accessibilité. |
| ModifyAnnotations | `20` | Permet d'ajouter ou de modifier des annotations de texte. Lors de l'utilisation du cryptage RC4 40 bits, cette option permet également de remplir les champs du formulaire. |
| FillIn | `100` | Permet de remplir des formulaires et de signer le document. Lors de l'utilisation du cryptage RC4 40 bits, cette option est ignorée et le remplissage du formulaire est autorisé chaque fois que ModifyAnnotations est défini. |
| ContentCopyForAccessibility | `200` | Permet d'extraire du texte et des graphiques à l'appui de l'accessibilité aux utilisateurs handicapés ou à d'autres fins. Lors de l'utilisation du cryptage RC4 40 bits, cette option est ignorée et l'accessibilité est autorisée chaque fois que ContentCopy est défini. |
| DocumentAssembly | `400` | Permet d'assembler le document : insérer, faire pivoter ou supprimer des pages et créer des éléments de navigation tels que des signets ou des vignettes. Lors de l'utilisation du cryptage RC4 40 bits, cette option est ignorée et l'assemblage de documents est autorisé lorsque ModifyContents est défini. |
| HighResolutionPrinting | `804` | Permet d'imprimer le document à la résolution la plus élevée possible. Lors de l'utilisation du cryptage RC4 40 bits, cette option est ignorée et l'impression haute résolution est autorisée lorsque l'impression est définie. |
| AllowAll | `FFFF` | Autorise toutes les opérations sur le document PDF. |

### Voir également

* espace de noms [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
