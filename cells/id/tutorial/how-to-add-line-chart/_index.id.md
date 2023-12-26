---
title: Cara menambahkan diagram garis melalui Aspose.Cells
weight: 7700
limit:
description: Pelajari cara menambahkan diagram garis.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /id/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Pelajari cara menambahkan diagram garis dengan Aspose.Cells" >}}

<p>
Dalam tutorial ini, kita akan menambahkan diagram garis dalam file excel.
</p>

<p>
 Kita akan mulai dengan membuat buku kerja baru menggunakan<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells perpustakaan</a> dan tambahkan diagram garis.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Silakan periksa kode berikut untuk mengetahui cara menambahkan diagram garis.
//ExStepSummary:0: Kode berikut menunjukkan cara menambahkan diagram garis, mengatur rentang data seri, dan mengatur rentang data kategori.
//ExStepImage:0:langkah-1.png
//ExStepSummary:1: Kode berikut menunjukkan cara memindahkan legenda ke bawah dan mengatur warna font legenda.
//ExStepImage:1:langkah-2.png
//ExStepSummary:2: Kode berikut menunjukkan cara mengakses label data, mengaktifkan nama kategori, dan mengatur posisi.
//ExStepImage:2:langkah-3.png
//ExStart
//ExLangkah:0-
menggunakan Aspose.Cells;
menggunakan Aspose.Cells.Gambar;

Buku kerja buku kerja = Buku Kerja baru();
Lembar kerja = buku kerja.Lembar kerja[0];
sheet.Nama = "Lembar Bagan";
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

sheet.PageSetup.PrintGridlines = benar;
sheet.PageSetup.PrintArea = "A1:F20";

Bagan ChartCollection = lembar.Bagan;

//Tambahkan diagram garis, atur rentang data seri, dan atur rentang data kategori
int indeks = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Bagan bagan = lembar.Bagan[indeks];
chart.NSeries.Add("B2:B5", benar);
grafik.NSeries.CategoryData = "A2:A5";

//Langkah Sebelumnya:1-
//Pindahkan legenda ke bawah dan atur warna font legenda
chart.Legend.Font.Color = Warna.Biru;
chart.Legend.Position = LegendPositionType.Bottom;

//Langkah Sebelumnya:2-
//Akses label data, aktifkan nama kategori dan atur posisi
DataLabels dataLabels = bagan.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = benar;
dataLabels.Position = LabelPositionType.Center;

//ExLangkah:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Pemasangan Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Redaktur</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}