---
title: Pembuatan dan Konversi Bagan Excel ke Gambar melalui .NET
url: /id/net/chart/
description: C# kode sumber untuk menggambar dan mengonversi bagan atau diagram di Microsoft Excel menggunakan .NET Pustaka. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Pembuatan dan Konversi Bagan File Excel melalui .NET" h2="Buat bagan dokumen Excel dan konversikan ke gambar menggunakan API sisi server dalam .NET aplikasi berbasis." >}}
{{% blocks/products/pf/feature-page-summary %}}
Menggambar grafik adalah seni untuk menampilkan data secara grafis untuk analisis yang mudah. [.NET Perpustakaan Excel](/cells/net/) mendukung menggambar grafik dalam file Excel. API mendukung pembuatan bagan berbeda yang tercantum di [ChartType Enumeration](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) termasuk diagram lingkaran, piramida, garis, dan gelembung. Selain itu, ini juga mengubah grafik menjadi gambar. API menyediakan [Kelas grafik](https://apireference.aspose.com/cells/net/aspose.cells.charts) untuk blok bangunan grafik.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Buat Bagan dalam File Excel" %}}

Membuat bagan menggunakan Excel API itu sederhana. Proses adalah, Buat [Kelas buku kerja](https://apireference.aspose.com/cells/net/aspose.cells/workbook) objek dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Masukkan data sel yang diperlukan menggunakan [Metode PutValue](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Tambahkan bagan ke lembar kerja dengan menggunakan koleksi Bagan [Tambahkan metode](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Tentukan [Tipe Bagan](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) dari enumerasi ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Membuat Bagan Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konversi Bagan Excel ke Gambar" %}}

Proses mengonversi grafik menjadi gambar adalah, Gunakan kelas Workbook untuk memuat file Excel, pilih workseet yang relevan yang berisi grafik dan panggil [Metode ToImage](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) untuk konversi.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi Bagan Excel ke Gambar" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}