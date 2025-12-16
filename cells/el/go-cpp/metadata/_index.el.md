---
title: Διαχείριση μεταδεδομένων αρχείων Excel με το Go μέσω C++
description: Προβολή, προσθήκη, επεξεργασία, κατάργηση ή εξαγωγή μεταδεδομένων αρχείων Excel χρησιμοποιώντας τη βιβλιοθήκη Go via C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση μεταδεδομένων εγγράφου Excel Microsoft<sup>&reg;</sup> μέσω Go μέσω C++" h2="Προβολή, εισαγωγή, ενημέρωση, κατάργηση ή εξαγωγή προσαρμοσμένων και ενσωματωμένων ιδιοτήτων εγγράφων Excel σε εφαρμογές C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Μεταδεδομένα στο Excel - Πώς να προβάλετε, να εισαγάγετε και να καταργήσετε μεταδεδομένα αρχείου excel.[Μεταβείτε στη Βιβλιοθήκη Excel C++](/cells/el/go-cpp/)Η διευκόλυνση γίνεται με εύκολο τρόπο, υποστηρίζοντας τις ενσωματωμένες/οριζόμενες από το σύστημα ιδιότητες, όπως το όνομα του συγγραφέα, τον τίτλο, τα στατιστικά στοιχεία του εγγράφου κ.λπ., που απαιτούνται μερικές φορές, όπως για να ελεγχθεί πότε τροποποιείται ή αποθηκεύεται τελικά ένα αρχείο, μαζί με προσαρμοσμένες/οριζόμενες από τον χρήστη ιδιότητες με τη μορφή ζευγών ονόματος/τιμής. Για την αυτοματοποίηση της διαδικασίας, η βιβλιοθήκη υποστηρίζει τη δημιουργία και τη συντήρηση μεγάλων αρχείων μεταδεδομένων Excel.[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/go-cpp/workbook/) Η κλάση ανοίγει ένα βιβλίο εργασίας κατά διαδρομή, κατά ροή και κατά ειδικό τύπο μορφής αρχείου. Επομένως, φορτώστε το αρχείο με την κατάλληλη μέθοδο για περαιτέρω επεξεργασία. Μερικές από τις δυνατότητες που αναφέρονται παρακάτω και οι προγραμματιστές μπορούν εύκολα να βελτιώσουν τον κώδικά τους σύμφωνα με τις απαιτήσεις της εφαρμογής.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ανάγνωση και ενημέρωση ενσωματωμένων ιδιοτήτων" %}}

 Για την αυτοματοποίηση των ενσωματωμένων ιδιοτήτων, το API παρέχει[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)μέθοδος που επιστρέφει μια συλλογή DocumentProperties που αντιπροσωπεύει όλες τις ενσωματωμένες ιδιότητες εγγράφου του υπολογιστικού φύλλου. Αφού αποκτήσετε πρόσβαση σε όλες τις ενσωματωμένες ιδιότητες, αποκτήστε πρόσβαση στις σχετικές ιδιότητες χρησιμοποιώντας τη σχετική μέθοδο όπως GetTitle(), GetSubject() κ.λπ. Για να ενημερώσετε τις ιδιότητες, το API παρέχει μέθοδο όπως SetTitle, SetSubject, SetAuthor, SetComments κ.λπ. Δείτε το[ενσωματωμένη συλλογή ιδιοτήτων εγγράφων](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) για την απαιτούμενη λειτουργία.

{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στον κωδικό C++ για να διαβάσετε τις ιδιότητες που ορίζονται από το σύστημα" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στον κωδικό C++ για να ενημερώσετε τις ενσωματωμένες ιδιότητες" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Προβολή και προσθήκη προσαρμοσμένων καθορισμένων ιδιοτήτων" %}}

 Για τη διαχείριση προσαρμοσμένων ιδιοτήτων, το API παρέχει[Βιβλίο εργασίας::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)που επιστρέφει όλη τη συλλογή ιδιοτήτων προσαρμοσμένου εγγράφου του υπολογιστικού φύλλου. Αρχικά, αποκτώντας πρόσβαση στις προσαρμοσμένες ιδιότητες μέσω αυτής της μεθόδου, οι προγραμματιστές μπορούν να χρησιμοποιήσουν σχετικές μεθόδους για να προσθέσουν ιδιότητες όπως AddIDocumentProperty, AddLinkToContentProperty και ομοίως να χρησιμοποιήσουν τις UpdateLinkedPropertyValue, UpdateLinkedRange για να ενημερώσουν την τιμή της ιδιότητας προσαρμοσμένου εγγράφου που συνδέεται με το περιεχόμενο και με το συνδεδεμένο εύρος αντίστοιχα. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν τη σχετική μέθοδο από[συλλογή προσαρμοσμένων ιδιοτήτων εγγράφου](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Μεταβείτε μέσω του κωδικού C++ για να δείτε τα προσαρμοσμένα ακίνητα" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Μεταβείτε στον κώδικα C++ για να προσθέσετε μεταδεδομένα σε αρχείο Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}