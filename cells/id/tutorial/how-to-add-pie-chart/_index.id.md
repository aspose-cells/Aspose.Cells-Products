---
title: Cara menambahkan diagram lingkaran melalui Aspose.Cells
weight: 7700
limit:
description: Pelajari cara menambahkan diagram lingkaran.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /id/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Pelajari cara menambahkan diagram lingkaran dengan Aspose.Cells" >}}

<p>
Dalam tutorial ini, kami akan menambahkan diagram lingkaran dalam file excel.
</p>

<p>
 Kita akan mulai dengan membuat buku kerja baru menggunakan<a href="https://www.nuget.org/packages/Aspose.Cells">Perpustakaan Aspose.Cells</a> dan tambahkan diagram lingkaran.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Silakan periksa kode berikut untuk mengetahui cara menambahkan diagram lingkaran.
//ExStepSummary:0: Kode berikut menunjukkan cara menambahkan diagram lingkaran, mengatur rentang data seri, dan mengatur rentang data kategori.
//ExStepImage:0:langkah-1.png
//ExStepSummary:1: Kode berikut menunjukkan cara mematikan legenda.
//ExStepImage:1:langkah-2.png
//ExStepSummary:2: Kode berikut menunjukkan cara mengakses label data, mengaktifkan nama kategori, mengaktifkan format persentase, dan mengatur posisi.
//ExStepImage:2:langkah-3.png
//ExStart
//ExStep:0-
menggunakan Aspose.Cells;
menggunakan Aspose.Cells.Gambar;

Buku kerja buku kerja = Buku Kerja baru();
Lembar kerja = buku kerja.Lembar kerja[0];
lembar.Nama = "LembarBagan";
Cells sel = lembar.Cells;
sel["A1"].Nilai = "Buah";
sel["A2"].Nilai = "apel";
sel["A3"].Nilai = "oranye";
sel["A4"].Nilai = "blueberry";
sel["A5"].Nilai = "kiwi";

sel["B1"].Nilai = "Harga";
sel["B2"].Nilai = 10;
sel["B3"].Nilai = 5;
sel["B4"].Nilai = 20;
sel["B5"].Nilai = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

Grafik ChartCollection = sheet.Charts;

//Tambahkan diagram lingkaran, setel rentang data seri, dan setel rentang data kategori
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Bagan bagan = sheet.Charts[indeks];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
// Matikan legenda
chart.ShowLegend = false;

//ExStep:2-
//Akses label data, aktifkan nama kategori, aktifkan format persentase, dan setel posisi
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

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