---
title: Πώς να προσθέσετε γράφημα γραμμής μέσω Aspose.Cells
weight: 7700
limit:
description: Μάθετε πώς να προσθέτετε γράφημα γραμμών.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /el/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Μάθετε πώς να προσθέτετε γράφημα γραμμών με το Aspose.Cells" >}}

<p>
Σε αυτό το σεμινάριο, θα προσθέσουμε γράφημα γραμμών σε ένα αρχείο excel.
</p>

<p>
 Θα ξεκινήσουμε δημιουργώντας ένα νέο βιβλίο εργασίας χρησιμοποιώντας το<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells βιβλιοθήκη</a> και προσθέστε γράφημα γραμμών.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Ελέγξτε τον παρακάτω κώδικα για να μάθετε πώς μπορείτε να προσθέσετε γράφημα γραμμής.
//ExStepSummary:0: Ο παρακάτω κώδικας δείχνει τον τρόπο προσθήκης γραμμικού γραφήματος, ορισμού εύρους δεδομένων σειράς και ορισμού εύρους δεδομένων κατηγορίας.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Ο ακόλουθος κώδικας δείχνει πώς να μετακινήσετε το υπόμνημα στο κάτω μέρος και να ορίσετε το χρώμα της γραμματοσειράς του μύθου.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Ο ακόλουθος κώδικας δείχνει πώς να αποκτήσετε πρόσβαση σε ετικέτες δεδομένων, να ενεργοποιήσετε τα ονόματα κατηγοριών και να ορίσετε τη θέση.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
χρησιμοποιώντας Aspose.Cells;
χρησιμοποιώντας Aspose.Cells. Σχέδιο;

Τετράδιο εργασίας = νέο βιβλίο εργασίας();
Φύλλο εργασίας = βιβλίο εργασίας. Φύλλα εργασίας[0];
sheet.Name = "ChartSheet";
Cells κελιά = φύλλο.Cells;
κύτταρα["A1"].Value = "Fruit";
κύτταρα["A2"].Τιμή = "μήλο";
κύτταρα["A3"].Value = "πορτοκαλί";
κύτταρα["A4"].Value = "blueberry";
κύτταρα["A5"].Value = "ακτινίδιο";

κύτταρα["B1"].Value = "Τιμή";
κελιά["B2"].Τιμή = 10;
κελιά["B3"].Τιμή = 5;
κελιά["B4"].Τιμή = 20;
κελιά["B5"].Τιμή = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection charts = sheet.Charts;

//Προσθήκη γραμμικού γραφήματος, ορισμός εύρους δεδομένων σειράς και ορισμός εύρους δεδομένων κατηγορίας
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Γράφημα γραφήματος = φύλλο.Διαγράμματα[ευρετήριο];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Μετακινήστε το υπόμνημα προς τα κάτω και ορίστε το χρώμα της γραμματοσειράς του μύθου
γράφημα.Legend.Font.Color = Χρώμα.Μπλε;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Πρόσβαση σε ετικέτες δεδομένων, ενεργοποίηση ονομάτων κατηγοριών και ρύθμιση θέσης
DataLabels dataLabels = γράφημα.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Εγκατάσταση Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Συντάκτης</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}