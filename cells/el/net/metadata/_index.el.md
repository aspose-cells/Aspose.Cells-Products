---
title: Διαχείριση μεταδεδομένων αρχείων Excel μέσω .NET C#

description: Προβάλετε, προσθέστε, επεξεργαστείτε, αφαιρέστε ή εξαγάγετε μεταδεδομένα αρχείων Excel με λίγες μόνο γραμμές κώδικα C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση Μεταδεδομένων αρχείου Microsoft<sup>&reg;</sup> Excel μέσω .NET" h2="Προβάλετε, προσθέστε, ενημερώστε, αφαιρέστε ή εξαγάγετε ενσωματωμένες και προσαρμοσμένες ιδιότητες αρχείου Excel χρησιμοποιώντας τα API της πλευράς διακομιστή .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) υποστηρίζει τη διαχείριση ιδιοτήτων που καθορίζονται από το σύστημα (ενσωματωμένες) όπως τίτλος, όνομα συντάκτη, στατιστικά εγγράφων κ.λπ. καθώς και ιδιοτήτων που ορίζονται από τον χρήστη (προσαρμοσμένες) με τη μορφή ζεύγους ονόματος-τιμής. Υπάρχει [Τάξη βιβλίου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/workbook) για να φορτώσετε τα αρχεία και [Συλλογή φύλλου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) ασχολείται με τη συλλογή φύλλων εργασίας καθώς και [Τάξη φύλλου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/worksheet) για την αναπαράσταση μεμονωμένου φύλλου εργασίας. Μαζί με αυτές τις κλάσεις, τα BuiltInDocumentProperties, CustomDocumentProperties κάνουν τη διαδικασία απλή για τη διαχείριση μεταδεδομένων. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαχείριση Ενσωματωμένων Ιδιοτήτων" %}}

Για τη διαχείριση ιδιοτήτων που καθορίζονται από το σύστημα, το API παρέχει [BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), και οι προγραμματιστές μπορούν εύκολα να αποκτήσουν πρόσβαση σε μια ενσωματωμένη ιδιότητα και να ενημερώσουν την τιμή της. Ανάλογα με τις απαιτήσεις της εφαρμογής, οι προγραμματιστές μπορούν να χρησιμοποιήσουν το ευρετήριο ή το όνομα ιδιότητας από το [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για τη διαχείριση ενσωματωμένων ιδιοτήτων" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Διαχείριση προσαρμοσμένων ιδιοτήτων" %}}

Για τη διαχείριση ιδιοτήτων που ορίζονται από το χρήστη, το API παρέχει [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), και οι προγραμματιστές μπορούν εύκολα να έχουν πρόσβαση σε ιδιότητες που έχουν ήδη προστεθεί, καθώς και να προσθέτουν νέες ιδιότητες. Για να προσθέσετε προσαρμοσμένες ιδιότητες, [Προσθήκη μεθόδου](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) του [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) Η κλάση προσθέτει την ιδιότητα και επιστρέφει μια αναφορά για τη νέα ιδιότητα ως an [Ιδιότητες.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) αντικείμενο. Η κλάση DocumentProperty χρησιμοποιείται για την ανάκτηση του ονόματος, της τιμής και του τύπου της ιδιότητας εγγράφου ως [DocumentProperty.Όνομα](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) που επιστρέφει ένα από τα [Τύπος ιδιοκτησίας](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) τιμές απαρίθμησης. 
 
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για προσθήκη μεταδεδομένων στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για κατάργηση προσαρμοσμένης ιδιότητας στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
