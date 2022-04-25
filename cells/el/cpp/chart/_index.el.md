---
title: Δημιουργία γραφημάτων Excel και μετατροπή σε εικόνες μέσω C++
url: /el/cpp/chart/
description: C++ πηγαίος κώδικας για σχεδίαση και μετατροπή γραφήματος ή διαγράμματος στο Microsoft Excel χρησιμοποιώντας τη Βιβλιοθήκη C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργήστε γραφήματα Microsoft<sup>&reg;</sup> Excel και μετατρέψτε σε εικόνες μέσω C++" h2="Μετατρέψτε γραφήματα εγγράφων Excel σε εικόνες και δημιουργήστε γραφήματα συμπεριλαμβανομένων γραφημάτων Pie, Pyramid, Line και Bubble εντός εφαρμογών που βασίζονται σε C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Χρησιμοποιώντας γραφήματα του Excel, μπορεί κανείς να πάρει τη μεγαλύτερη εικόνα και να αναλύσει τα δεδομένα εύκολα για τη λήψη σωστών αποφάσεων. [C++ Βιβλιοθήκη Excel](/cells/cpp/) υποστηρίζει τη δημιουργία διαφορετικών γραφημάτων που παρατίθενται από [enum Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) συμπεριλαμβανομένων γραφημάτων περιοχής, ράβδου, πίτας, πυραμίδας, γραμμής και φυσαλίδων. Επιπλέον, για τη μετατροπή γραφημάτων σε εικόνες, το API παρέχει α [Μέθοδος ToImage](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) στην απαιτούμενη μορφή εικόνας.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε γραφήματα Excel" %}}

Διαδικασία δημιουργίας γραφήματος Excel είναι, να δημιουργήσετε μια παρουσία του [Τάξη IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και επιλέξτε το επιθυμητό [Φύλλο εργασίας](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Προσθέστε το γράφημα χρησιμοποιώντας [Προσθήκη μεθόδου](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) με σχετικές παραμέτρους συμπεριλαμβανομένου του τύπου γραφήματος. Πρόσβαση στο γράφημα μέσω ευρετηρίου και [Προσθήκη](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) την πηγή δεδομένων για το γράφημα.

{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για τη δημιουργία γραφημάτων Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή γραφημάτων σε εικόνες" %}}


Για τη διαδικασία μετατροπής γραφημάτων είναι, πρώτα να δημιουργήσετε γράφημα ως σχετικού τύπου χρησιμοποιώντας τον παραπάνω κώδικα ή να αποκτήσετε πρόσβαση σε αυτό από το σχετικό φύλλο. Καθορίστε τη διαδρομή αποθήκευσης εξόδου για την εικόνα και χρησιμοποιήστε τη μέθοδο ToImage για τη μετατροπή.

 
{{% blocks/products/pf/feature-page-code h3="C++ Κώδικας για μετατροπή γραφημάτων Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}