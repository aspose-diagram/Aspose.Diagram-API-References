---
title: HTMLSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε HTML.
type: docs
weight: 3240
url: /el/net/aspose.diagram.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε HTML.

```csharp
public class HTMLSaveOptions : RenderingSaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στο[`HTML`](../../aspose.diagram/savefileformat/) μορφή. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Λαμβάνει ή ορίζει την περιοχή των σχημάτων που θα αποθηκευτούν . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Όταν οι χαρακτήρες στο διάγραμμα είναι unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανίζονται ως μπλοκ σε pdf, εικόνα ή XPS. Ορίστε την Προεπιλεγμένη Γραμματοσειρά όπως MingLiu ή MS Gothic για να εμφανίζονται χαρακτήρες. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Ρύθμιση για την απόδοση του μετααρχείου Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Καθορίζει αν θα γίνει μεγέθυνση της σελίδας . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Καθορίζει εάν χρειάζεται ή όχι εξαγωγή των σχημάτων οδηγών. |
| [ExportHiddenPage](../../aspose.diagram.saving/htmlsaveoptions/exporthiddenpage/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή της κρυφής σελίδας ή όχι. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή των σχολίων ή όχι. |
| [PageCount](../../aspose.diagram.saving/htmlsaveoptions/pagecount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σελίδων για απόδοση σε HTML. Η προεπιλογή είναι MaxValue που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν. |
| [PageIndex](../../aspose.diagram.saving/htmlsaveoptions/pageindex/) { get; set; } | Λαμβάνει ή ορίζει το ευρετήριο με βάση το 0 της πρώτης σελίδας για απόδοση. Η προεπιλογή είναι 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος σελίδας για τις εικόνες που δημιουργούνται. Μπορεί να[`PageSize`](../pagesize/) ή null. |
| [Resolution](../../aspose.diagram.saving/htmlsaveoptions/resolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση για το html που δημιουργείται, σε κουκκίδες ανά ίντσα. |
| [SaveAsSingleFile](../../aspose.diagram.saving/htmlsaveoptions/saveassinglefile/) { get; set; } | Υποδεικνύει εάν αποθηκεύεται η html ως μεμονωμένο αρχείο. Η προεπιλεγμένη τιμή είναι false. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/htmlsaveoptions/saveforegroundpagesonly/) { get; set; } | Καθορίζει εάν όλες οι σελίδες θα αποθηκεύονται σε εικόνα ή μόνο σε πρώτο πλάνο. |
| override [SaveFormat](../../aspose.diagram.saving/htmlsaveoptions/saveformat/) { get; set; } | Καθορίζει τη μορφή με την οποία θα αποθηκευτούν οι σελίδες του διαγράμματος που έχουν αποδοθεί εάν χρησιμοποιείται αυτό το αντικείμενο επιλογών αποθήκευσης. Μπορεί να[`HTML`](../../aspose.diagram/savefileformat/) μόνο. |
| [SaveTitle](../../aspose.diagram.saving/htmlsaveoptions/savetitle/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή του τίτλου ή όχι. |
| [SaveToolBar](../../aspose.diagram.saving/htmlsaveoptions/savetoolbar/) { get; set; } | Καθορίζει εάν η αποθήκευση της γραμμής εργαλείων Η προεπιλεγμένη τιμή είναι αληθής. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Λαμβάνει ή ορίζει σχήματα για απόδοση. Το προεπιλεγμένο πλήθος είναι 0. |
| [StreamProvider](../../aspose.diagram.saving/htmlsaveoptions/streamprovider/) { get; set; } | Λαμβάνει ή ορίζει τον IStreamProvider για την εξαγωγή αντικειμένων. |
| [Title](../../aspose.diagram.saving/htmlsaveoptions/title/) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του διαγράμματος για απόδοση σε HTML. Εάν ο τίτλος είναι μηδενικός Diagram.DocumentProperties.Title[`DocumentProperties`](../../aspose.diagram/documentproperties/) θα χρησιμοποιηθεί ως Title. Εάν το Diagram.DocumentProperties.Title είναι μηδενικό ή κενό, το όνομα του αρχείου του Διαγράμματος θα χρησιμοποιηθεί ως Title. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Λαμβάνει ή ορίζει προειδοποιητική επανάκληση. |

### Δείτε επίσης

* class [RenderingSaveOptions](../renderingsaveoptions/)
* χώρος ονομάτων [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
