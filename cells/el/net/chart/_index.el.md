---
title: Δημιουργία γραφημάτων Excel και μετατροπή σε εικόνες μέσω .NET
url: /el/net/chart/
description: C# πηγαίος κώδικας για σχεδίαση και μετατροπή γραφήματος ή διαγράμματος στο Microsoft Excel χρησιμοποιώντας τη Βιβλιοθήκη .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Δημιουργία και μετατροπή γραφημάτων αρχείων Excel μέσω .NET" h2="Δημιουργήστε γραφήματα εγγράφων του Excel και μετατρέψτε σε εικόνες χρησιμοποιώντας API από την πλευρά του διακομιστή εντός εφαρμογών που βασίζονται σε .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
Η σχεδίαση γραφημάτων είναι μια τέχνη για την εμφάνιση δεδομένων γραφικά για εύκολη ανάλυση. [.NET Βιβλιοθήκη Excel](/cells/net/) υποστηρίζει τη σχεδίαση γραφημάτων σε αρχεία Excel. Το API υποστηρίζει τη δημιουργία διαφορετικών γραφημάτων που αναφέρονται στο [Αριθμός Τύπου Γραφήματος](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) συμπεριλαμβανομένων γραφημάτων πίτας, πυραμίδας, γραμμών και φυσαλίδων. Επιπλέον, μετατρέπει επίσης γραφήματα σε εικόνες. Το API παρέχει α [Τάξη γραφημάτων](https://reference.aspose.com/cells/net/aspose.cells.charts) για δομικά στοιχεία γραφήματος.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε γραφήματα μέσα στο αρχείο Excel" %}}

Η δημιουργία γραφημάτων χρησιμοποιώντας το Excel API είναι απλή. Η διαδικασία είναι, Δημιουργία [Τάξη βιβλίου εργασίας](https://reference.aspose.com/cells/net/aspose.cells/workbook) αντικείμενο και επιλέξτε το πρώτο φύλλο εργασίας ή το σχετικό φύλλο παρέχοντας το ευρετήριό του. Εισαγάγετε τα απαιτούμενα δεδομένα κελιών χρησιμοποιώντας [Μέθοδος PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Προσθέστε γράφημα στο φύλλο εργασίας χρησιμοποιώντας τη συλλογή γραφημάτων [Προσθήκη μεθόδου](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Προσδιορίστε το [Τύπος γραφήματος](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) από την απαρίθμηση ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για τη δημιουργία γραφημάτων Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Μετατροπή γραφημάτων Excel σε εικόνες" %}}

Η διαδικασία μετατροπής γραφημάτων σε εικόνες είναι: Χρησιμοποιήστε την κλάση Βιβλίο εργασίας για να φορτώσετε το αρχείο Excel, επιλέξτε το σχετικό φύλλο εργασίας που περιέχει τα γραφήματα και καλέστε το [Μέθοδος ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) για μετατροπή.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή γραφήματος Excel σε εικόνα" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}