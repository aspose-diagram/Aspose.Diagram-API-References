---
title: Window
second_title: Aspose.Diagram for .NET API Reference
description: Αντιπροσωπεύει ένα ανοιχτό παράθυρο σε μια παρουσία του Microsoft Visio. Αυτό το στοιχείο περιέχει πληροφορίες που είναι απαραίτητες για την ακριβή εκ νέου δημιουργία ενός παραθύρου διεπαφής χρήστη στον χώρο εργασίας της εφαρμογής όταν το αρχείο DatadiagramML ανοίγει αρχικά από το Visio.
type: docs
weight: 4390
url: /el/net/aspose.diagram/window/
---
## Window class

Αντιπροσωπεύει ένα ανοιχτό παράθυρο σε μια παρουσία του Microsoft Visio. Αυτό το στοιχείο περιέχει πληροφορίες που είναι απαραίτητες για την ακριβή εκ νέου δημιουργία ενός παραθύρου διεπαφής χρήστη στον χώρο εργασίας της εφαρμογής όταν το αρχείο DatadiagramML ανοίγει αρχικά από το Visio.

```csharp
public class Window
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Window](window/)() | Κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | Αναγνωριστικό κοντέινερ: Σελίδα, Φύλλο ή Κύριο. Σχετικό και απαραίτητο μόνο εάν έχει καθοριστεί ContainerType. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Μπορεί να είναι μία από τις ακόλουθες τιμές: Document, Page ή Master. Σχετικό μόνο όταν το WindowType έχει καθοριστεί ως Σχέδιο ή Φύλλο. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Διαδρομή αρχείου του εγγράφου που εμφανίζεται σε αυτό το παράθυρο. Αυτό το χαρακτηριστικό είναι σχετικό για παράθυρα των οποίων το WindowType έχει οριστεί ως Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Καθορίζει εάν η δυνατότητα δυναμικού πλέγματος είναι ενεργοποιημένη για ένα έγγραφο ή παράθυρο. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Καθορίζει τα αντικείμενα στα οποία διαμορφώνεται η κόλλα όταν είναι ενεργοποιημένη η κόλλα στο έγγραφο. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | Το μοναδικό αναγνωριστικό του στοιχείου μέσα στο γονικό του στοιχείο. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Κύριο αναγνωριστικό εάν αυτό το παράθυρο εμφανίζει κύριο. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | Αναγνωριστικό σελίδας εάν αυτό το παράθυρο εμφανίζει μια σελίδα. Σχετικό μόνο όταν το WindowType έχει οριστεί ως Drawing και το ContainerType ως Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | Αναγνωριστικό του παραθύρου στο οποίο περιέχεται αυτό το παράθυρο στένσιλ. Σχετικό μόνο όταν το WindowType έχει οριστεί ως Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Επισήμανση μόνο για ανάγνωση εάν αυτό το στένσιλ δεν είναι στένσιλ εγγράφου. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | Αναγνωριστικό φύλλου σε κοντέινερ. Σχετικό μόνο όταν το κοντέινερ έχει καθοριστεί ως Φύλλο. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Καθορίζει εάν τα σημεία σύνδεσης θα εμφανίζονται σε ένα παράθυρο. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Καθορίζει εάν ένα πλέγμα εμφανίζεται στο παράθυρο σχεδίασης. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Καθορίζει εάν οι οδηγοί θα εμφανίζονται στο παράθυρο σχεδίασης. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Καθορίζει εάν οι αλλαγές σελίδας εμφανίζονται σε ένα παράθυρο. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Καθορίζει εάν οι χάρακες εμφανίζονται στο παράθυρο σχεδίασης. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Περιέχει μια συλλογή στοιχείων SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Καθορίζει εάν μια συγκεκριμένη ρύθμιση επέκτασης snap είναι ενεργοποιημένη ή απενεργοποιημένη για το ενεργό παράθυρο. Η τιμή μπορεί να είναι ένα άθροισμα των τιμών του παρακάτω πίνακα. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Καθορίζει τα αντικείμενα στα οποία προσαρμόζονται τα σχήματα όταν το snap είναι ενεργό στο παράθυρο. Η τιμή μπορεί να είναι ένα άθροισμα των τιμών του παρακάτω πίνακα. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Καθορίζει την ομάδα των συγχωνευμένων παραθύρων με στένσιλ της οποίας το παράθυρο είναι μέλος. Αυτό το χαρακτηριστικό είναι σχετικό μόνο για στοιχεία παραθύρου των οποίων το χαρακτηριστικό WindowType είναι Stencil και μόνο εάν το παράθυρο στένσιλ είναι μέρος μιας συγχωνευμένης ομάδας παραθύρων με στένσιλ. Όλα τα παράθυρα στένσιλ που αποτελούν μέρος της ίδιας συγχωνευμένης ομάδας έχουν την ίδια τιμή στοιχείου StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Περιέχει έναν ακέραιο που καθορίζει τη σχετική θέση ενός στένσιλ μέσα σε μια ομάδα σε ένα παράθυρο. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Καθορίζει το πλάτος του στοιχείου ελέγχου καρτέλας σελίδας ενός παραθύρου σχεδίασης (ως κλάσμα του συνολικού πλάτους του παραθύρου σχεδίασης). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Προαιρετικό διπλό. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Προαιρετικό διπλό. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Προαιρετικό διπλό. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Ύψος ορθογωνίου παραθύρου. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Αριστερή συντεταγμένη του παραλληλογράμμου παραθύρου. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Αυτό το χαρακτηριστικό μπορεί να είναι άθροισμα των παρακάτω τιμών. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Επάνω συντεταγμένη του ορθογωνίου παραθύρου. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Μια απαριθμημένη τιμή που μπορεί να είναι μία από τις ακόλουθες: Σχέδιο, φύλλο, στένσιλ ή εικονίδιο. Ένα στοιχείο παραθύρου του WindowType='Stencil' πρέπει να εμφανίζεται μετά το παράθυρο γονικού σχεδίου του (WindowType='Σχέδιο') και πριν από οποιοδήποτε άλλο παράθυρο σχεδίασης στοιχεία. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Πλάτος ορθογωνίου παραθύρου. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Diagram](../../aspose.diagram/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
