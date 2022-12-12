---
title: Διαχείριση μεταδεδομένων αρχείων Excel μέσω C++

description: Προβολή, προσθήκη, επεξεργασία, κατάργηση ή εξαγωγή μεταδεδομένων αρχείων Excel χρησιμοποιώντας τη βιβλιοθήκη C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση Μεταδεδομένων Εγγράφων Microsoft<sup>&reg;</sup> Excel μέσω C++" h2="Προβολή, εισαγωγή, ενημέρωση, κατάργηση ή εξαγωγή προσαρμοσμένων και ενσωματωμένων ιδιοτήτων εγγράφου Excel σε εφαρμογές C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
Μεταδεδομένα στο Excel - Τρόπος προβολής, εισαγωγής και κατάργησης μεταδεδομένων αρχείου excel. [C++ Βιβλιοθήκη Excel](/cells/cpp/) διευκολύνει με εύκολο τρόπο υποστηρίζοντας τις ενσωματωμένες/καθορισμένες από το σύστημα ιδιότητες, όπως όνομα συντάκτη, τίτλος, στατιστικά εγγράφου κ.λπ. που απαιτούνται κάποια στιγμή, όπως για να ελέγξετε πότε τροποποιήθηκε ή αποθηκεύτηκε τελευταία το αρχείο μαζί με προσαρμοσμένες/καθορισμένες από το χρήστη ιδιότητες με τη μορφή ζεύγη ονόματος/τιμής. Για την αυτοματοποίηση της διαδικασίας, η βιβλιοθήκη υποστηρίζει τη δημιουργία και τη διατήρηση μεγάλων αρχείων Excel μεταδεδομένων. [Μέθοδος CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) του [Εργοστασιακή Κατηγορία](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Ανοίξτε ένα Βιβλίο Εργασίας κατά διαδρομή, κατά ροή και με ειδικό FileFormatType. Φορτώστε λοιπόν το αρχείο με την κατάλληλη μέθοδο για περαιτέρω επεξεργασία. Λίγες από τις δυνατότητες που αναφέρονται παρακάτω και οι προγραμματιστές μπορούν εύκολα να βελτιώσουν τον κώδικά τους σύμφωνα με τις απαιτήσεις της εφαρμογής. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαβάστε και ενημερώστε τις ενσωματωμένες ιδιότητες" %}}

Για την αυτοματοποίηση των ενσωματωμένων ιδιοτήτων, το API παρέχει [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) μέθοδος που επιστρέφει μια συλλογή DocumentProperties που αντιπροσωπεύει όλες τις ενσωματωμένες ιδιότητες εγγράφου του υπολογιστικού φύλλου. Αφού αποκτήσετε πρόσβαση σε όλες τις ενσωματωμένες ιδιότητες, αποκτήστε πρόσβαση στις σχετικές ιδιότητες χρησιμοποιώντας τη σχετική μέθοδο, όπως GetTitle(), GetSubject() κ.λπ. Για να ενημερώσετε τις ιδιότητες, το API παρέχει μεθόδους όπως SetTitle, SetSubject, SetAuthor, SetComments κ.λπ. [συλλογή ιδιοτήτων ενσωματωμένου εγγράφου](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) για την απαιτούμενη λειτουργία.

{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για ανάγνωση ιδιοτήτων που καθορίζονται από το σύστημα" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για ενημέρωση ενσωματωμένων ιδιοτήτων" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Προβολή και προσθήκη Προσαρμοσμένων Ιδιοτήτων" %}}

Για το χειρισμό προσαρμοσμένων ιδιοτήτων, το API παρέχει [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) που επιστρέφει όλη τη συλλογή ιδιοτήτων προσαρμοσμένου εγγράφου του υπολογιστικού φύλλου. Αρχικά, έχοντας πρόσβαση στις προσαρμοσμένες ιδιότητες μέσω αυτής της μεθόδου, οι προγραμματιστές μπορούν να χρησιμοποιήσουν σχετικές μεθόδους για να προσθέσουν ιδιότητες όπως AddIDocumentProperty, AddLinkToContentProperty και παρομοίως να χρησιμοποιήσουν τα UpdateLinkedPropertyValue, UpdateLinkedRange για να ενημερώσουν την τιμή ιδιότητας προσαρμοσμένου εγγράφου που συνδέεται με το περιεχόμενο και τη συνδεδεμένη περιοχή αντίστοιχα. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν τη σχετική μέθοδο από [συλλογή προσαρμοσμένων ιδιοτήτων εγγράφου](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Κωδικός για προβολή προσαρμοσμένων ιδιοτήτων" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για προσθήκη μεταδεδομένων στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
