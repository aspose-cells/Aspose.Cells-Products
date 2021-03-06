---
title: Δημιουργία γραφημάτων Excel και μετατροπή σε εικόνες μέσω Java
url: /el/java/chart/
description: Java πηγαίος κώδικας για σχεδίαση και μετατροπή γραφήματος ή διαγράμματος στο Microsoft Excel χρησιμοποιώντας τη Βιβλιοθήκη Java. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Μετατροπή και δημιουργία γραφημάτων αρχείων Excel μέσω Java" h2="Μετατρέψτε γραφήματα εγγράφων Excel σε εικόνες καθώς και δημιουργήστε διάφορα γραφήματα χρησιμοποιώντας API από την πλευρά του διακομιστή εντός εφαρμογών που βασίζονται σε Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

Η ανάλυση δεδομένων μέσω διαγραμμάτων δείχνει τη μεγαλύτερη εικόνα και είναι εύκολο να ληφθούν πιο τεκμηριωμένες αποφάσεις με σαφέστερες πληροφορίες. [Java Βιβλιοθήκη Excel](/cells/java/) υποστηρίζει τη σχεδίαση διαφορετικών γραφημάτων που αναφέρονται από [Τύπος γραφήματος](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) συμπεριλαμβανομένων γραφημάτων πίτας, πυραμίδας, γραμμών και φυσαλίδων. Επιπλέον, μετατρέπει επίσης γραφήματα σε εικόνες. Το API παρέχει α [Τάξη γραφημάτων](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) για την αναπαράσταση ενός ενιαίου γραφήματος Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Μετατροπή γραφημάτων Excel σε εικόνες" %}}

Η διαδικασία μετατροπής γραφημάτων σε εικόνες συμπεριλαμβανομένων JPG, PNG, TIFF, BMP κ.λπ. [ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) τάξη για να φορτώσετε το αρχείο Excel, επιλέξτε το σχετικό [φύλλο εργασίας](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) που περιέχουν τα γραφήματα ή επαναλαμβάνονται σε κάθε γράφημα σε κάθε φύλλο εργασίας. Καθορίζω [ImageOrPrintOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) και απόδοση εικόνας εξόδου του γραφήματος χρησιμοποιώντας [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για μετατροπή γραφήματος Excel σε εικόνα" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε γραφήματα μέσα στο αρχείο Excel" %}}

Η δημιουργία γραφημάτων χρησιμοποιώντας το Excel API είναι απλή, καθώς το API παρέχει ένα σύνολο διαφορετικών κλάσεων, όπως Άξονας, Γράφημα, Περιοχή γραφήματος, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection κ.λπ. για διαφορετικά είδη γραφημάτων. Η διαδικασία είναι, Δημιουργήστε αντικείμενο κλάσης Βιβλίο εργασίας και επιλέξτε το πρώτο φύλλο εργασίας ή το σχετικό φύλλο παρέχοντας το ευρετήριό του. Για την προέλευση δεδομένων του γραφήματος, εισαγάγετε τιμές στα κελιά του φύλλου εργασίας χρησιμοποιώντας [setValue](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) μέθοδος. Χρησιμοποιήστε τη συλλογή ChartCollection [μέθοδος προσθήκης](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) για να προσθέσετε το γράφημα, ορίστε τον τύπο του γραφήματος με την απαρίθμηση ChartType. Αποκτήστε πρόσβαση στο νέο αντικείμενο Chart από τη συλλογή ChartCollection περνώντας το ευρετήριό του. Χρησιμοποιήστε το [SeriesCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) αντικειμένου γραφήματος για να καθορίσετε την πηγή δεδομένων του γραφήματος.

{{% blocks/products/pf/feature-page-code h3="Java Κώδικας για τη δημιουργία γραφημάτων Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}