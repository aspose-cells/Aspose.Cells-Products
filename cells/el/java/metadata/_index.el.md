---
title: Διαχείριση μεταδεδομένων αρχείου Excel via Java
description: Προβολή, προσθήκη, επεξεργασία, αφαίρεση ή εξαγωγή μεταδεδομένων αρχείων Excel με λίγες μόνο γραμμές κώδικα Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση Microsoft<sup>&reg;</sup> Μεταδεδομένα αρχείου Excel via Java" h2="Προβάλετε, προσθέστε, ενημερώστε, διαγράψτε ή εξαγάγετε προσαρμοσμένες και ενσωματωμένες ιδιότητες αρχείου Excel χρησιμοποιώντας API από την πλευρά του διακομιστή Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/el/java/) υποστηρίζει τη διαχείριση ενσωματωμένων ιδιοτήτων (καθορισμένες από το σύστημα) όπως τίτλος, όνομα συγγραφέα, στατιστικά εγγράφων κ.λπ. καθώς και προσαρμοσμένες (καθορισμένες από το χρήστη) ιδιότητες με τη μορφή ζεύγους ονόματος/τιμής. Υπάρχει[Τάξη βιβλίου εργασίας](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) για να φορτώσετε τα αρχεία και[Συλλογή φύλλου εργασίας](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) ασχολείται με τη συλλογή φύλλων εργασίας καθώς και[Τάξη φύλλου εργασίας](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) για την αναπαράσταση μεμονωμένου φύλλου εργασίας. Για πρόσβαση σε ενσωματωμένες και προσαρμοσμένες ιδιότητες, τα BuiltInDocumentProperties, CustomDocumentProperties κάνουν τη διαδικασία απλή για τη διαχείριση μεταδεδομένων.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαχείριση ιδιοτήτων που καθορίζονται από το σύστημα" %}}

 Για τη διαχείριση ενσωματωμένων ιδιοτήτων, το API παρέχει[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) , και οι προγραμματιστές μπορούν εύκολα να αποκτήσουν πρόσβαση σε μια ενσωματωμένη ιδιότητα και να ενημερώσουν την τιμή της. Ανάλογα με τις απαιτήσεις της εφαρμογής, οι προγραμματιστές μπορούν να χρησιμοποιήσουν το ευρετήριο ή το όνομα ιδιότητας από το[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Κωδικός για τη διαχείριση ιδιοτήτων που καθορίζονται από το σύστημα" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Προσθήκη και αφαίρεση προσαρμοσμένων μεταδεδομένων" %}}

Για το χειρισμό προσαρμοσμένων ιδιοτήτων, το API παρέχει[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , και οι προγραμματιστές μπορούν εύκολα να έχουν πρόσβαση σε υπάρχουσες ιδιότητες, καθώς και να προσθέτουν νέες ιδιότητες χρησιμοποιώντας[μέθοδος προσθήκης](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) του[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) Η κλάση προσθέτει την ιδιότητα και επιστρέφει μια αναφορά για τη νέα ιδιότητα ως an[Ιδιότητες.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) αντικείμενο. Η κλάση DocumentProperty χρησιμοποιείται για την ανάκτηση του ονόματος, της τιμής και του τύπου της ιδιότητας εγγράφου ως[DocumentProperty.Όνομα](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) που επιστρέφει ένα από τα[Τύπος ιδιοκτησίας](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) τιμές απαρίθμησης.
 
{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για προσθήκη μεταδεδομένων στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Κωδικός για διαγραφή προσαρμοσμένης ιδιότητας στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
