---
title: Διαχωρίστε το υπολογιστικό φύλλο του Excel σε φύλλα εργασίας στο Java
description: Java πηγαίοι κώδικες που εξηγούν πώς να χωρίσετε Microsoft αρχεία Excel σε πολλά έγγραφα χρησιμοποιώντας τη βιβλιοθήκη Excel Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Διαίρεση αρχείων Excel via Java" h2="Διαχωρίστε το υπολογιστικό φύλλο Excel σε φύλλα εργασίας εντός εφαρμογών που βασίζονται σε Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Υπάρχουν διάφορα σενάρια, Όταν υπάρχει ανάγκη διαχωρισμού αρχείων Excel όπως ένα υπολογιστικό φύλλο που περιέχει δεδομένα μαθητών με κατανομή ενός φύλλου για κάθε μαθητή. Και υπάρχει ανάγκη να χωριστεί κάθε φύλλο μαθητή ως ξεχωριστό αρχείο. Για την αυτοματοποίησή της via Java εφαρμογή,[Java Excel API](/cells/el/java/) υπάρχει για διαχωρισμό εγγράφων του Excel κατά φύλλο. Οι υποστηριζόμενες μορφές περιλαμβάνουν XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαχωρίστε το έγγραφο του Excel σε πολλά αρχεία" %}}

Ο απλούστερος τρόπος για να χωρίσετε το αρχείο Excel σε φύλλο είναι η πρόσβαση σε όλα τα φύλλα, η επανάληψη σε κάθε φύλλο και η αποθήκευση ένα προς ένα στην επιθυμητή μορφή. Για τη φόρτωση του φύλλου εργασίας, παρέχεται το API[ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) τάξη.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) Η μέθοδος λαμβάνει τον συνολικό αριθμό φύλλων. Επαναλάβετε σε κάθε φύλλο και χρησιμοποιήστε[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) για πρόσβαση σε συγκεκριμένο φύλλο. Μετακινήστε τα επιλεγμένα δεδομένα φύλλου σε αντικείμενο κλάσης Βιβλίο εργασίας που δημιουργήθηκε πρόσφατα χρησιμοποιώντας[Μέθοδος αντιγραφής](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Τέλος αποθηκεύστε το στην απαιτούμενη μορφή.

{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για διαίρεση αρχείων Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Διαχωρίστε το φύλλο εργασίας του Excel σε παράθυρα" %}}

Το API παρέχει επίσης τη λειτουργικότητα του διαχωρισμού του φύλλου εργασίας του Excel σε διαφορετικά παράθυρα. Η διαδικασία είναι, Φόρτωση του αρχείου χρησιμοποιώντας την κλάση Βιβλίο εργασίας. Επιλέξτε το πρώτο φύλλο εργασίας ή οποιοδήποτε επιθυμητό φύλλο παρέχοντας το ευρετήριό του. Καλέστε το setActiveCell που έχει ως παράμετρο σχετικό δείκτη κελιού. Και τέλος χωρίστε το παράθυρο του φύλλου εργασίας σε διαφορετικά παράθυρα καλώντας τη μέθοδο split().

{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για διαίρεση φύλλου Excel σε προβολή παραθύρου" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
