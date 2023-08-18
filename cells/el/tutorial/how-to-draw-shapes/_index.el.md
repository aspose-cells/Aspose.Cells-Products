---
title: Πώς να προσθέσετε σχήματα μέσω του Aspose.Cells
weight: 7700
limit:
description: Μάθετε πώς να προσθέτετε σχήματα.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /el/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Μάθετε πώς να προσθέτετε σχήματα με το Aspose.Cells" >}}

<p>
Σε αυτό το σεμινάριο, θα προσθέσουμε σχήματα σε ένα αρχείο excel.
</p>

<p>
 Θα ξεκινήσουμε δημιουργώντας ένα νέο βιβλίο εργασίας χρησιμοποιώντας το<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells βιβλιοθήκη</a> και προσθέστε σχήματα.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Ελέγξτε τον παρακάτω κώδικα για να μάθετε πώς μπορείτε να προσθέσετε σχήματα.
//ExStepSummary:0: Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε σχήμα ορθογωνίου.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε σχήμα γραμμής.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε οβάλ σχήμα.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
χρησιμοποιώντας Aspose.Cells;
χρησιμοποιώντας Aspose.Cells. Σχέδιο;





Τετράδιο εργασίας = νέο βιβλίο εργασίας();
Φύλλο εργασίας = βιβλίο εργασίας. Φύλλα εργασίας[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection σχήματα = φύλλο.Σχήματα;

//Προσθήκη σχήματος ορθογωνίου
shapes.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Προσθήκη σχήματος γραμμής
shapes.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Προσθήκη οβάλ σχήματος
shapes.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
ΤΕΤΡΑΔΙΟ ΕΡΓΑΣΙΩΝ
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