---
title: Cara menambahkan bentuk melalui Aspose.Cells
weight: 7700
limit:
description: Pelajari cara menambahkan bentuk.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /id/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Pelajari cara menambahkan bentuk dengan Aspose.Cells" >}}

<p>
Dalam tutorial ini, kami akan menambahkan bentuk di file excel.
</p>

<p>
 Kita akan mulai dengan membuat buku kerja baru menggunakan<a href="https://www.nuget.org/packages/Aspose.Cells">Perpustakaan Aspose.Cells</a> dan menambahkan bentuk.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Silakan periksa kode berikut untuk mengetahui cara menambahkan bentuk.
//ExStepSummary:0: Kode berikut menunjukkan cara menambahkan bentuk persegi panjang.
//ExStepImage:0:langkah-1.png
//ExStepSummary:1: Kode berikut menunjukkan cara menambahkan bentuk garis.
//ExStepImage:1:langkah-2.png
//ExStepSummary:2: Kode berikut menunjukkan cara menambahkan bentuk oval.
//ExStepImage:2:langkah-3.png
//ExStart
//ExStep:0-
menggunakan Aspose.Cells;
menggunakan Aspose.Cells.Gambar;





Buku kerja buku kerja = Buku Kerja baru();
Lembar kerja = buku kerja.Lembar kerja[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection bentuk = sheet.Shapes;

//Tambahkan bentuk persegi panjang
bentuk.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Tambahkan bentuk garis
bentuk.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
// Tambahkan bentuk oval
bentuk.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
buku kerja
//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Pemasangan Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Penyunting</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}