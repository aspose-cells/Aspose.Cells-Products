---
title: Pembuatan dan Konversi Bagan Excel ke Gambar via .NET
description:  C# source code untuk menggambar dan mengkonversi chart atau diagram di Microsoft Excel menggunakan .NET Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Pembuatan dan Konversi Bagan Berkas Excel via .NET" h2="Buat bagan dokumen Excel dan konversikan ke gambar menggunakan API sisi server dalam aplikasi berbasis .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Menggambar grafik adalah seni untuk menampilkan data secara grafis agar mudah dianalisis.[.NET Perpustakaan Excel](/cells/id/net/) mendukung menggambar grafik dalam file Excel. API mendukung pembuatan bagan berbeda yang tercantum di[Pencacahan Tipe Bagan](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) termasuk diagram lingkaran, piramida, garis, dan gelembung. Selain itu, ini juga mengubah bagan menjadi gambar. API menyediakan a[Kelas diagram](https://reference.aspose.com/cells/net/aspose.cells.charts) untuk bagan blok bangunan.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Buat Bagan dalam File Excel" %}}

 Membuat grafik menggunakan Excel API itu sederhana. Prosesnya adalah, Buat[Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) objek dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Masukkan data sel yang diperlukan menggunakan[metode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Tambahkan bagan ke lembar kerja dengan menggunakan koleksi Bagan[Tambahkan metode](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Tentukan[Jenis Bagan](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)dari pencacahan ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Membuat Grafik Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konversi Bagan Excel ke Gambar" %}}

 Proses mengubah bagan menjadi gambar adalah, Gunakan kelas Buku Kerja untuk memuat file Excel, pilih lembar kerja yang relevan yang berisi bagan dan panggil[metode ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) untuk konversi.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi Bagan Excel menjadi Gambar" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
