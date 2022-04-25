---
title: Σχολιασμοί αρχείων Excel μέσω C++
url: /el/cpp/annotation/
description: Προσθέστε ή αφαιρέστε σχόλια σχολιασμού δεδομένων υπολογιστικών φύλλων Excel και OpenOffice με τη βιβλιοθήκη C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση σχολιασμών αρχείων Microsoft<sup>&reg;</sup> Excel μέσω C++" h2="Προσθέστε ή αφαιρέστε απλές σημειώσεις για σχολιασμούς ή σχόλια σε εφαρμογές που βασίζονται σε C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) παρέχει υποστήριξη για τη διαχείριση σχολιασμών σε επίπεδο κελιού με την προσθήκη, την πρόσβαση και την αφαίρεση σχολίων. Το API παρέχει [IComment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) και [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) καθώς [GetICcomments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) για το χειρισμό των σχολίων από όλες τις απόψεις. Οι υποστηριζόμενες μορφές Excel περιλαμβάνουν ODS, XLS, XLSX, XLSB και XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Σχολιασμοί δεδομένων αρχείων Excel" %}}
Χειρισμός σχολίων σε φύλλα εργασίας - Δεν περιορίζεται πόσα σχόλια έχει ένα φύλλο στο MS Excel. Κάποιος μπορεί να εισάγει όσο χρειάζεται η εφαρμογή. Η διαδικασία εισαγωγής σχολίων είναι η δημιουργία [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) αντικείμενο κλάσης για να φορτώσετε ένα υπάρχον αρχείο και επιλέξτε φύλλο εργασίας όπου θέλετε να προσθέσετε το σχόλιο. Λάβετε όλα τα σχόλιά του χρησιμοποιώντας το getComments(). Προσθέστε το σχόλιο χρησιμοποιώντας [Προσθήκη](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) μέθοδος. Λάβετε το ευρετήριο κελιών και χρησιμοποιήστε το [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) για την εισαγωγή σχολίων. Επιπλέον, το API έχει τη δυνατότητα να αφαιρεί όλα τα σχόλια. Λίγες από τις μεθόδους είναι [ClearComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Διαγράφει όλα τα σχόλια στο υπολογιστικό φύλλο σχεδιαστή. Εξάλλου, [RemoveAt](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) μέθοδο για την αφαίρεση του στοιχείου σε ένα καθορισμένο ευρετήριο ή με καθορισμένο όνομα.

{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για προσθήκη σχολίων στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}