---
title: Cara menambahkan TextBox melalui Aspose.Cells
weight: 7700
limit:
description: Pelajari cara menambahkan TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /id/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Pelajari cara menambahkan TextBox dengan Aspose.Cells" >}}

<p>
Dalam tutorial ini, kita akan menambahkan TextBox dalam file excel.
</p>

<p>
 Kita akan mulai dengan membuat buku kerja baru menggunakan<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells perpustakaan</a> dan tambahkan Kotak Teks.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Silakan periksa kode berikut untuk mengetahui cara menambahkan TextBox.
//ExStepSummary:0: Kode berikut menunjukkan cara menambahkan TextBox dan mengatur teks.
//ExStepImage:0:langkah-1.png
//ExStepSummary:1: Kode berikut menunjukkan cara mengubah warna teks.
//ExStepImage:1:langkah-2.png
//ExStepSummary:2: Kode berikut menunjukkan cara mengubah sudut rotasi TextBox.
//ExStepImage:2:langkah-3.png
//ExStart
//ExLangkah:0-
menggunakan Aspose.Cells;
menggunakan Aspose.Cells.Gambar;

Buku kerja buku kerja = Buku Kerja baru();
Lembar kerja = buku kerja.Lembar kerja[0];
sheet.PageSetup.PrintGridlines = benar;
sheet.PageSetup.PrintArea = "A1:F20";

Bentuk ShapeCollection = lembar.Bentuk;

//Tambahkan TextBox dan atur teks
TextBox textBox = bentuk.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET adalah perpustakaan kelas pemrograman yang memungkinkan pengembang perangkat lunak memanipulasi dan memproses file spreadsheet dalam aplikasi mereka sendiri.";

//Langkah Sebelumnya:1-
//Mengubah warna teks
textBox.Font.Color = Warna.Biru;

//Langkah Sebelumnya:2-
//Ubah sudut rotasi TextBox
textBox.RotationAngle = 90;

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