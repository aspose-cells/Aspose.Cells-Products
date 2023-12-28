---
title: Διαχωρίστε το φύλλο εργασίας του Excel στο C#
description: C# πηγαίοι κώδικες που εξηγούν πώς να χωρίσετε Microsoft αρχεία Excel σε πολλαπλά αρχεία σε εφαρμογές Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Διαίρεση αρχείων Excel via .NET" h2="Διαχωρίστε ένα έγγραφο Excel σε διαφορετικά αρχεία χρησιμοποιώντας τον κωδικό C# εντός εφαρμογών που βασίζονται σε .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Βιβλιοθήκη Excel](/cells/el/net/) είναι σε θέση να χωρίσει το έγγραφο του Excel σε πολλαπλά υπολογιστικά φύλλα εντός εφαρμογών που βασίζονται σε .NET. Οι υποστηριζόμενες μορφές αρχείων περιλαμβάνουν XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Διαχωρίστε το έγγραφο του Excel σε πολλά αρχεία" %}}
Ο απλούστερος τρόπος διαχωρισμού των φύλλων αρχείων Excel είναι η πρόσβαση σε όλα τα φύλλα μέσω[Φύλλα εργασίας](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Επαναλαμβάνοντας σε κάθε φύλλο και καλώντας το[αντίγραφο](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) μέθοδος. Τέλος, αποθηκεύστε το σε μια καθορισμένη διαδρομή.

 + Φορτώστε το αρχείο Excel με πλήρη διαδρομή χρησιμοποιώντας[Τάξη βιβλίου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Επανάληψη σε κάθε φύλλο
+ Δημιουργήστε ένα νέο αντικείμενο κλάσης Βιβλίου εργασίας
 + Αντιγράψτε το φύλλο μέσω[Μέθοδος αντιγραφής](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Καλέστε τη μέθοδο Save() και περάστε το όνομα του αρχείου (πλήρης διαδρομή) με σχετικό SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για διαίρεση αρχείων Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Διαχωρίστε το φύλλο εργασίας του Excel σε παράθυρα" %}}

 Για τον διαχωρισμό του παραθύρου του φύλλου εργασίας σε παράθυρα, παρέχεται το API[Μέθοδος διαχωρισμού](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) της κλάσης φύλλου εργασίας, που παρέχει τη χωρισμένη προβολή του φύλλου εργασίας. Για να αφαιρέσετε τη διαχωρισμένη προβολή, το API παρέχει[Μέθοδος RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Τέλος αποθηκεύστε το σε μια καθορισμένη διαδρομή.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για διαίρεση του παραθύρου φύλλου εργασίας του Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για την κατάργηση της προβολής διαχωρισμένου πανιού" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
