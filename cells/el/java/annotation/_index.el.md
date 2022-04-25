---
title: Σχολιασμοί αρχείων Excel μέσω Java
url: /el/java/annotation/
description: Προσθέστε ή αφαιρέστε σχολιασμούς δεδομένων υπολογιστικών φύλλων Excel και OpenOffice με τη βιβλιοθήκη Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Διαχείριση σχολιασμών αρχείων Microsoft<sup>&reg;</sup> Excel μέσω Java" h2="Εισαγάγετε απλές σημειώσεις για σχολιασμό ή διαγράψτε σχόλια σε επίπεδο κελιού υπολογιστικού φύλλου Excel εντός εφαρμογών που βασίζονται σε Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) παρέχει υποστήριξη για τη διαχείριση σχολιασμών σε επίπεδο κελιού με την προσθήκη, την πρόσβαση και τη διαγραφή σχολίων. Το API παρέχει [Σχόλιο](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Συλλογή σχολίων](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) και [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) για το χειρισμό των σχολίων από όλες τις απόψεις.
Οι υποστηριζόμενες μορφές αρχείων περιλαμβάνουν ODS, XLS, XLSX, XLSB και XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Σχολιασμοί δεδομένων αρχείων Excel" %}}
Διαχείριση σχολίων σε φύλλα εργασίας - Δεν υπάρχει όριο πόσα σχόλια έχει ένα φύλλο στο MS Excel. Κάποιος μπορεί να προσθέσει όσα απαιτούνται από την εφαρμογή. Η διαδικασία προσθήκης σχολίων είναι η δημιουργία [ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) αντικείμενο κλάσης ή φορτώστε ένα υπάρχον αρχείο χρησιμοποιώντας την κλάση Βιβλίο εργασίας. Αποκτήστε πρόσβαση σε όλα τα σχόλιά του χρησιμοποιώντας το getComments(). Λάβετε το ευρετήριο κελιών και χρησιμοποιήστε το [setNote](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) για την εισαγωγή σχολίων. Επιπλέον, το API έχει τη δυνατότητα να αφαιρεί όλα τα σχόλια. 

{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για προσθήκη σχολίων στο αρχείο Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για την κατάργηση σχολίων εντός του αρχείου Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}