---
title: Διαχειριστείτε τα Μεταδεδομένα Αρχείο Excel μέσω του C++
description: Προβολή, προσθήκη, επεξεργασία, αφαίρεση ή εξαγωγή μεταδεδομένων αρχείων Excel χρησιμοποιώντας τη βιβλιοθήκη C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση Microsoft<sup>&reg;</sup> Μεταδεδομένα εγγράφου Excel μέσω C++" h2="Προβολή, εισαγωγή, ενημέρωση, κατάργηση ή εξαγωγή προσαρμοσμένων και ενσωματωμένων ιδιοτήτων εγγράφου Excel μέσα σε C++ εφαρμογές." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Μεταδεδομένα στο Excel - Τρόπος προβολής, εισαγωγής και κατάργησης μεταδεδομένων αρχείου excel.[C++ Βιβλιοθήκη Excel](/cells/el/cpp/) διευκολύνει με εύκολο τρόπο υποστηρίζοντας τις ενσωματωμένες/καθορισμένες από το σύστημα ιδιότητες, όπως όνομα συντάκτη, τίτλος, στατιστικά εγγράφου κ.λπ. που απαιτούνται κάποια στιγμή, όπως για να ελέγξετε πότε τροποποιήθηκε ή αποθηκεύτηκε τελευταία το αρχείο μαζί με προσαρμοσμένες/καθορισμένες από το χρήστη ιδιότητες με τη μορφή ζεύγη ονόματος/τιμής. Για την αυτοματοποίηση της διαδικασίας, η βιβλιοθήκη υποστηρίζει τη δημιουργία και τη διατήρηση μεγάλων αρχείων Excel μεταδεδομένων.[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Ανοίγει ένα βιβλίο εργασίας κατά διαδρομή, κατά ροή και κατά ειδικό FileFormatType. Φορτώστε λοιπόν το αρχείο με την κατάλληλη μέθοδο για περαιτέρω επεξεργασία. Λίγες από τις δυνατότητες που αναφέρονται παρακάτω και οι προγραμματιστές μπορούν εύκολα να βελτιώσουν τον κώδικά τους σύμφωνα με τις απαιτήσεις της εφαρμογής.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαβάστε και ενημερώστε τις ενσωματωμένες ιδιότητες" %}}

 Για την αυτοματοποίηση των ενσωματωμένων ιδιοτήτων, παρέχει το API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) μέθοδος που επιστρέφει μια συλλογή DocumentProperties που αντιπροσωπεύει όλες τις ενσωματωμένες ιδιότητες εγγράφου του υπολογιστικού φύλλου. Αφού αποκτήσετε πρόσβαση σε όλες τις ενσωματωμένες ιδιότητες, αποκτήστε πρόσβαση στις σχετικές ιδιότητες χρησιμοποιώντας σχετική μέθοδο όπως GetTitle(), GetSubject() κ.λπ. Για να ενημερώσετε τις ιδιότητες, το API παρέχει μεθόδους όπως SetTitle, SetSubject, SetAuthor, SetComments κ.λπ.[συλλογή ιδιοτήτων ενσωματωμένου εγγράφου](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) για την απαιτούμενη λειτουργία.

{{% blocks/products/pf/feature-page-code h3="C++ Κωδικός για ανάγνωση ιδιοτήτων που καθορίζονται από το σύστημα" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Κωδικός για ενημέρωση ενσωματωμένων ιδιοτήτων" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Προβολή και προσθήκη Προσαρμοσμένων Ιδιοτήτων" %}}

Για το χειρισμό προσαρμοσμένων ιδιοτήτων, το API παρέχει[Βιβλίο εργασίας::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) που επιστρέφει όλη τη συλλογή ιδιοτήτων προσαρμοσμένου εγγράφου του υπολογιστικού φύλλου. Αρχικά, έχοντας πρόσβαση στις προσαρμοσμένες ιδιότητες μέσω αυτής της μεθόδου, οι προγραμματιστές μπορούν να χρησιμοποιήσουν σχετικές μεθόδους για να προσθέσουν ιδιότητες όπως AddIDocumentProperty, AddLinkToContentProperty και παρομοίως να χρησιμοποιήσουν τα UpdateLinkedPropertyValue, UpdateLinkedRange για να ενημερώσουν την τιμή ιδιότητας προσαρμοσμένου εγγράφου που συνδέεται με το περιεχόμενο και τη συνδεδεμένη περιοχή αντίστοιχα. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν τη σχετική μέθοδο από[συλλογή προσαρμοσμένων ιδιοτήτων εγγράφου](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Κωδικός για προβολή προσαρμοσμένων ιδιοτήτων" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για προσθήκη μεταδεδομένων στο αρχείο Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
