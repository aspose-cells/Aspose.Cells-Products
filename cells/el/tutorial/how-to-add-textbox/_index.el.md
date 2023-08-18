---
title: Πώς να προσθέσετε το TextBox μέσω του Aspose.Cells
weight: 7700
limit:
description: Μάθετε πώς μπορείτε να προσθέσετε TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /el/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Μάθετε πώς μπορείτε να προσθέσετε TextBox με Aspose.Cells" >}}

<p>
Σε αυτό το σεμινάριο, θα προσθέσουμε το TextBox σε ένα αρχείο excel.
</p>

<p>
 Θα ξεκινήσουμε δημιουργώντας ένα νέο βιβλίο εργασίας χρησιμοποιώντας το<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells βιβλιοθήκη</a> και προσθέστε το TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Ελέγξτε τον παρακάτω κώδικα για να μάθετε πώς μπορείτε να προσθέσετε TextBox.
//ExStepSummary:0: Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε TextBox και να ορίσετε κείμενο.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το χρώμα του κειμένου.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Ο ακόλουθος κώδικας δείχνει πώς να αλλάξετε τη γωνία περιστροφής του TextBox.
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

//Προσθήκη TextBox και ορισμός κειμένου
TextBox textBox = shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET είναι μια βιβλιοθήκη κλάσεων προγραμματισμού που επιτρέπει στους προγραμματιστές λογισμικού να χειρίζονται και να επεξεργάζονται αρχεία υπολογιστικών φύλλων μέσα στις δικές τους εφαρμογές.";

//ExStep:1-
//Αλλαγή χρώματος κειμένου
textBox.Font.Color = Χρώμα.Μπλε;

//ExStep:2-
//Αλλαγή της γωνίας περιστροφής του TextBox
textBox.RotationAngle = 90;

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