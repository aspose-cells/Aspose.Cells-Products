---
title: Εισαγωγή σχολίων στο Excel μέσω .NET

description: C# πηγαίους κώδικες για τον τρόπο εισαγωγής σχολίου σε αρχεία Microsoft Excel χρησιμοποιώντας τη Βιβλιοθήκη .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Εισαγωγή σχολίων στο Excel μέσω .NET" h2="Δημιουργήστε έγγραφα Excel και εισαγάγετε σχόλια χρησιμοποιώντας API από την πλευρά του διακομιστή σε εφαρμογές που βασίζονται στο .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Μπορείτε να προσθέσετε σχόλια στα κελιά. Όταν ένα κελί έχει ένα σχόλιο, εμφανίζεται μια ένδειξη στη γωνία του κελιού. Τα σχόλια εμφανίζονται όταν τοποθετείτε το δείκτη του ποντικιού σας πάνω από ένα κελί. Αυτά τα σχόλια μπορούν να χρησιμοποιηθούν για συζήτηση, ειδικές οδηγίες ή σήμανση περιεχομένου εγγράφου. [.NET Βιβλιοθήκη Excel](/cells/net/) υποστηρίζει την εισαγωγή σχολίων σε αρχεία Excel. Για αυτό, το API παρέχει ένα [Σχόλιο](https://reference.aspose.com/cells/net/aspose.cells/comment) τάξη για σχόλια.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Εισαγάγετε σχόλια στο Αρχείο Excel" %}}

Η εισαγωγή σχολίων χρησιμοποιώντας το Excel API είναι απλή. Η διαδικασία είναι, Δημιουργία [Τάξη βιβλίου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/workbook) αντικείμενο και επιλέξτε το πρώτο φύλλο εργασίας ή το σχετικό φύλλο παρέχοντας το ευρετήριό του. Εισαγάγετε τα απαιτούμενα δεδομένα κελιών χρησιμοποιώντας [Μέθοδος PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Προσθέστε σχόλιο στο φύλλο εργασίας χρησιμοποιώντας [Συλλογή σχολίων](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'μικρό [Προσθήκη μεθόδου](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για εισαγωγή σχολίου στο Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
