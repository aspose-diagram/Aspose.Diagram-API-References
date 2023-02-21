---
title: PdfSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε PDF.
type: docs
weight: 3410
url: /el/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στο[`Pdf`](../../aspose.diagram/savefileformat/) μορφή. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Λαμβάνει ή ορίζει την περιοχή των σχημάτων που θα αποθηκευτούν . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Επιθυμητό επίπεδο συμμόρφωσης για το έγγραφο PDF που δημιουργήθηκε. Η προεπιλογή είναιPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Όταν οι χαρακτήρες στο διάγραμμα είναι unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανίζονται ως μπλοκ σε pdf, εικόνα ή XPS. Ορίστε την Προεπιλεγμένη Γραμματοσειρά όπως MingLiu ή MS Gothic για να εμφανίζονται χαρακτήρες. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Λαμβάνει ή ορίζει λεπτομέρειες ψηφιακής υπογραφής. Εάν δεν έχει οριστεί, τότε δεν θα πραγματοποιηθεί υπογραφή. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Ρύθμιση για την απόδοση του μετααρχείου Emf. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Λαμβάνει ή ορίζει λεπτομέρειες κρυπτογράφησης. Εάν δεν έχει οριστεί, τότε δεν θα εκτελεστεί κρυπτογράφηση. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Καθορίζει αν θα γίνει μεγέθυνση της σελίδας . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Καθορίζει εάν χρειάζεται ή όχι εξαγωγή των σχημάτων οδηγών. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή της κρυφής σελίδας ή όχι. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση για τις εικόνες που δημιουργούνται, σε κουκκίδες ανά ίντσα. Εφαρμόζει τη μέθοδο δημιουργίας εικόνας εκτός από τις εικόνες σε μορφή Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή των σχολίων ή όχι. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Καθορίζει την ποιότητα συμπίεσης JPEG για εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). Η προεπιλογή είναι 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σελίδων για απόδοση σε PDF. Η προεπιλογή είναι MaxValue που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Λαμβάνει ή ορίζει το ευρετήριο με βάση το 0 της πρώτης σελίδας για απόδοση. Η προεπιλογή είναι 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Έλεγχος/Ενδειξη προόδου της διαδικασίας αποθήκευσης σελίδας. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος σελίδας για τις εικόνες που δημιουργούνται. Μπορεί να[`PageSize`](../pagesize/) ή null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Καθορίζει εάν όλες οι σελίδες θα αποθηκεύονται σε εικόνα ή μόνο σε πρώτο πλάνο. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Καθορίζει τη μορφή με την οποία θα αποθηκευτούν οι σελίδες του διαγράμματος που έχουν αποδοθεί εάν χρησιμοποιείται αυτό το αντικείμενο επιλογών αποθήκευσης. Μπορεί να[`PDF`](../../aspose.diagram/savefileformat/) μόνο. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Λαμβάνει ή ορίζει σχήματα για απόδοση. Το προεπιλεγμένο πλήθος είναι 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Καθορίζει εάν το διάγραμμα χωρίζεται σε πολλές σελίδες σύμφωνα με τη ρύθμιση της σελίδας. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιείται για όλες τις ροές περιεχομένου εκτός από τις εικόνες. Η προεπιλογή είναιFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη ανάλυση για τις εικόνες που δημιουργούνται, σε κουκκίδες ανά ίντσα. Εφαρμόζει τη μέθοδο δημιουργίας εικόνας εκτός από την εικόνα σε μορφή Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Λαμβάνει ή ορίζει προειδοποιητική επανάκληση. |

### Δείτε επίσης

* class [RenderingSaveOptions](../renderingsaveoptions/)
* χώρος ονομάτων [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
