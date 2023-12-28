---
title: Προσθήκη ή αφαίρεση σχολιασμών αρχείων Excel μέσω του C++
description: Προσθέστε ή αφαιρέστε σχόλια σχολιασμού δεδομένων των υπολογιστικών φύλλων Excel και OpenOffice με τη βιβλιοθήκη C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση Microsoft<sup>&reg;</sup> Σχολιασμών αρχείου Excel μέσω C++" h2="Προσθέστε ή αφαιρέστε απλές σημειώσεις για σχολιασμούς ή σχόλια σε εφαρμογές που βασίζονται σε C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/el/cpp/) παρέχει υποστήριξη για τη διαχείριση σχολιασμών σε επίπεδο κελιού με προσθήκη, πρόσβαση και κατάργηση σχολίων. API παρέχει[Σχόλιο](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) και[Συλλογή σχολίων](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) καθώς[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)για το χειρισμό των σχολίων από όλες τις απόψεις. Οι υποστηριζόμενες μορφές Excel περιλαμβάνουν ODS, XLS, XLSX, XLSB και XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Σχολιασμοί δεδομένων αρχείων Excel" %}}
 Χειρισμός σχολίων σε φύλλα εργασίας - Δεν περιορίζεται πόσα σχόλια έχει ένα φύλλο στο MS Excel. Κάποιος μπορεί να εισάγει όσο χρειάζεται η εφαρμογή. Η διαδικασία εισαγωγής σχολίων είναι η δημιουργία[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) αντικείμενο κλάσης για να φορτώσετε ένα υπάρχον αρχείο και επιλέξτε φύλλο εργασίας όπου θέλετε να προσθέσετε το σχόλιο. Λάβετε όλα τα σχόλιά του χρησιμοποιώντας το getComments(). Προσθέστε το σχόλιο χρησιμοποιώντας[Προσθήκη(const char16_t* Όνομα κελιού)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) μέθοδος. Λάβετε το ευρετήριο κελιών και χρησιμοποιήστε το[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) για την εισαγωγή σχολίων. Επιπλέον, το API μπορεί να αφαιρέσει όλα τα σχόλια. Λίγες από τις μεθόδους είναι[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) to Διαγράφει όλα τα σχόλια στο υπολογιστικό φύλλο σχεδιαστή. Εξάλλου,***RemoveAt*** μέθοδος για την αφαίρεση του στοιχείου σε ένα καθορισμένο ευρετήριο ή με καθορισμένο όνομα.

{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για προσθήκη σχολίων στο αρχείο Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
