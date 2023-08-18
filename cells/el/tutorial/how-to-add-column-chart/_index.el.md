---
title: Πώς να προσθέσετε γράφημα στηλών μέσω Aspose.Cells
weight: 7700
limit:
description: Μάθετε πώς να προσθέτετε γράφημα στηλών.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /el/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Μάθετε πώς να προσθέτετε γράφημα στηλών με Aspose.Cells" >}}

<p>
Σε αυτό το σεμινάριο, θα προσθέσουμε γράφημα στηλών σε ένα αρχείο excel.
</p>

<p>
 Θα ξεκινήσουμε δημιουργώντας ένα νέο βιβλίο εργασίας χρησιμοποιώντας το<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells βιβλιοθήκη</a> και προσθέστε γράφημα στηλών.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Ελέγξτε τον παρακάτω κώδικα για να μάθετε πώς μπορείτε να προσθέσετε γράφημα στηλών.
//ExStepSummary:0: Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε γράφημα στηλών.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Ο ακόλουθος κώδικας δείχνει πώς να μετακινήσετε το υπόμνημα προς τα αριστερά και να ορίσετε το χρώμα της γραμματοσειράς του μύθου.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Ο παρακάτω κώδικας δείχνει πώς να ορίσετε τον τίτλο ενός γραφήματος και να αλλάξετε το χρώμα της γραμματοσειράς σε μπλε.
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

//Προσθήκη γραφήματος στήλης
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Διάγραμμα γραφήματος = γραφήματα[ευρετήριο];

//ExStep:1-
//Μετακινήστε το υπόμνημα προς τα αριστερά και ορίστε το χρώμα της γραμματοσειράς του μύθου
γράφημα.Legend.Font.Color = Χρώμα.Μπλε;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Ορίστε τον τίτλο ενός γραφήματος και αλλάξτε το χρώμα της γραμματοσειράς σε μπλε
chart.Title.Text = "Γράφημα στήλης τιμών φρούτων";
chart.Title.Font.Color = Χρώμα.Μπλε;

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