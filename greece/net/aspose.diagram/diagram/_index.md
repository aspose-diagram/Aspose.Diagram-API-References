---
title: Diagram
second_title: Aspose.Diagram for .NET API Reference
description: Στοιχείο ρίζας της ιεραρχίας αντικειμένων του Visio.
type: docs
weight: 1170
url: /el/net/aspose.diagram/diagram/
---
## Diagram class

Στοιχείο ρίζας της ιεραρχίας αντικειμένων του Visio.

```csharp
public class Diagram : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Diagram](diagram/#constructor)() | Ο προεπιλεγμένος κατασκευαστής. |
| [Diagram](diagram/#constructor_1)(Stream) | Κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από τη ροή. |
| [Diagram](diagram/#constructor_4)(string) | Κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από το αρχείο. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Ο κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένη μορφή. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένες επιλογές αρχείου φόρτωσης. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Ο κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένη μορφή. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Ο κατασκευαστής δημόσιας κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένες επιλογές φόρτωσης αρχείου. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Καθορίζει την ενεργή σελίδα |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Ο αριθμός έκδοσης της παρουσίας του Visio που χρησιμοποιήθηκε για τη δημιουργία του εγγράφου. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Περιέχει τον πίνακα χρωμάτων του εγγράφου. Κάθε έγγραφο περιέχει έναν ενιαίο πίνακα χρωμάτων, , ο οποίος παραθέτει τα 24 τυπικά χρώματα που είναι διαθέσιμα για εφαρμογή σε αντικείμενα όπως σχήματα, κείμενο και επίπεδα στο έγγραφο. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Περιέχει τα στοιχεία DataConnection για το έγγραφο. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Η συλλογή αντικειμένων DataRecordset που σχετίζονται με ένα αντικείμενο Document. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | Το μοναδικό αναγνωριστικό της γλώσσας διεπαφής χρήστη που έχει καθορίσει ο χρήστης στις Προτιμήσεις γλώσσας του Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Περιέχει στοιχεία ιδιοτήτων του εγγράφου, όπως ο τίτλος του εγγράφου, ο συγγραφέας και ούτω καθεξής. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις του εγγράφου. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Καθορίζει τη δομή ShapeSheet ενός εγγράφου. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Περιέχει ένα δελτίο δρομολόγησης μηνυμάτων ηλεκτρονικού ταχυδρομείου MAPI για το έγγραφο MIME (Πολλαπλών χρήσεων Internet Mail Extensions). |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Περιέχει ένα στοιχείο EventItem για κάθε συμβάν στο οποίο ένα αντικείμενο πρέπει να ανταποκρίνεται. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Υποδεικνύει τη διαδρομή του φακέλου Fonts |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Περιέχει μια συλλογή από στοιχεία γραμματοσειράς |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Περιέχει στοιχεία για την κεφαλίδα και το υποσέλιδο ενός εγγράφου. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Λήψη και ρύθμιση της οθόνης διακοπής. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Υποδεικνύει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. Εάν υπάρχει, το Visio θα ελέγξει πλήρως τα περιεχόμενα του αρχείου. Παράλειψη για αρχεία που δημιουργείτε εκτός Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Κύρια αντικείμενα συλλογής. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Εάν θα χρησιμοποιηθούν μετρικές μονάδες στο σχέδιο. Ορίστε αυτό το χαρακτηριστικό σε True (1) για να χρησιμοποιήσετε μετρικές μονάδες. ορίστε το σε False (0) για να χρησιμοποιήσετε αγγλικές μονάδες. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Αντικείμενα σελίδας συλλογής. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | Η συμβολοσειρά Ribbon XML που μεταβιβάζεται στο έγγραφο για την προσαρμογή της διεπαφής χρήστη της κορδέλας. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | Τιμή XML. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Υποδεικνύει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. Εάν υπάρχει, το Visio θα ελέγξει πλήρως τα περιεχόμενα του αρχείου. Παράλειψη για αρχεία που δημιουργείτε εκτός Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Αντικείμενα φύλλου στυλ συλλογής. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | Η συμβολοσειρά XML της Κορδέλας που μεταβιβάζεται στο έγγραφο για την προσαρμογή της γραμμής εργαλείων γρήγορης πρόσβασης ή της κορδέλας. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Αποθηκεύει πληροφορίες σχετικά με την επικύρωση διαγράμματος για το έγγραφο. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Λαμβάνει το VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Περιέχει τα δεδομένα έργου της Microsoft Visual Basic for Applications σε κωδικοποιημένη μορφή MIME (Επεκτάσεις αλληλογραφίας πολλαπλών χρήσεων Internet). |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Ο αριθμός έκδοσης της παρουσίας του Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Περιέχει τα στοιχεία του παραθύρου για ένα έγγραφο. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Προσθέτει master στο διάγραμμα από διάγραμμα πηγής κατά Όνομα πλοιάρχου ή Όνομα U. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Προσθέτει master στο διάγραμμα από τη ροή προτύπου κατά αναγνωριστικό κύριου. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Προσθέτει master στο διάγραμμα από τη ροή προτύπου κατά Όνομα πλοιάρχου ή Όνομα U. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Προσθέτει master στο διάγραμμα από αρχείο προτύπου κατά αναγνωριστικό master. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Προσθέτει master στο διάγραμμα από αρχείο προτύπου κατά Όνομα πλοιάρχου ή Όνομα U. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο σε συγκεκριμένη σελίδα. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο στη σελίδα με καθορισμένα PinX και PinY. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο στη σελίδα με καθορισμένα PinX, PinY, Πλάτος και Ύψος. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Συνδυάζει ένα άλλο αντικείμενο διαγράμματος. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Αντιγράφει το θέμα από μια πηγή Διάγραμμα. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Εκτελεί εργασίες που καθορίζονται από την εφαρμογή που σχετίζονται με την απελευθέρωση, την απελευθέρωση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Λήψη της διαδρομής του φακέλου Προεπιλεγμένες γραμματοσειρές |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Λήψη αχρησιμοποίητων στυλ |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Υποδεικνύει εάν αυτό το διάγραμμα έχει κρυφές πληροφορίες. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Απεικονίζει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για όλες τις σελίδες του διαγράμματος. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Εκτυπώνει ολόκληρο το έγγραφο στον προεπιλεγμένο εκτυπωτή. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Εκτυπώνει το έγγραφο σύμφωνα με τις καθορισμένες ρυθμίσεις εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Εκτυπώνει ολόκληρο το έγγραφο στον προεπιλεγμένο εκτυπωτή. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Εκτυπώστε ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Εκτυπώνει το έγγραφο σύμφωνα με τις καθορισμένες ρυθμίσεις εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Εκτυπώνει το έγγραφο σύμφωνα με τις καθορισμένες ρυθμίσεις εκτυπωτή, χρησιμοποιώντας τον τυπικό ελεγκτή εκτύπωσης (χωρίς διεπαφή χρήστη) και ένα όνομα εγγράφου. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Εκτυπώστε ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Εκτυπώνει το έγγραφο σύμφωνα με τις καθορισμένες ρυθμίσεις εκτυπωτή, χρησιμοποιώντας τον τυπικό ελεγκτή εκτύπωσης (χωρίς διεπαφή χρήστη) και ένα όνομα εγγράφου. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Καλεί τη μέθοδο ανανέωσης για όλα τα DataRecordSet στο Διάγραμμα. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Αφαίρεση αχρησιμοποίητων πληροφοριών |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Αφαιρεί το VBA/macro από αυτό το διάγραμμα. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Αποθηκεύει τα δεδομένα του διαγράμματος στη ροή. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Αποθηκεύει το διάγραμμα σε μια ροή χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Αποθηκεύει τα δεδομένα του διαγράμματος στο αρχείο. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Αποθηκεύει το έγγραφο σε αρχείο χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Εξάγει το διάγραμμα από τη μορφή ροής vsd σε μορφή ροής vdw. Δεν έχει εφαρμοστεί ακόμα. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Εξάγει το διάγραμμα από ροή vsd σε μορφή αρχείου *.vdw. Δεν έχει εφαρμοστεί ακόμα. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Εξάγει το διάγραμμα από αρχείο vsd σε μορφή ροής vdw. Δεν έχει εφαρμοστεί ακόμα. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Εξάγει το διάγραμμα από μορφή vsd σε vdw. Δεν έχει εφαρμοστεί ακόμα. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Diagram](../../aspose.diagram/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
