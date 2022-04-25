---
title: Buat Bagan Excel dan Konversikan ke Gambar melalui C++
url: /id/cpp/chart/
description: C++ kode sumber untuk menggambar dan mengonversi bagan atau diagram di Microsoft Excel menggunakan C++ Pustaka
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat Microsoft<sup>&reg;</sup> Bagan Excel dan Konversikan ke Gambar melalui C++" h2="Konversi bagan dokumen Excel menjadi gambar serta buat bagan termasuk bagan Pai, Piramida, Garis, dan Gelembung dalam C++ aplikasi berbasis." >}}

{{% blocks/products/pf/feature-page-summary %}}

Menggunakan grafik Excel, seseorang bisa mendapatkan gambaran yang lebih besar dan menganalisis data dengan mudah untuk mengambil keputusan yang tepat. [C++ Perpustakaan Excel](/cells/cpp/) mendukung pembuatan bagan berbeda yang terdaftar oleh [enum Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) termasuk area, bar, pie, piramida, grafik garis dan gelembung. Selain itu, Untuk konversi bagan ke gambar, API menyediakan [Metode ToImage](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) ke dalam format gambar yang diperlukan.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Buat Bagan Excel" %}}

Proses pembuatan bagan Excel adalah, buat instance dari [Kelas IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) dan pilih yang diinginkan [lembar kerja](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Tambahkan bagan menggunakan [Tambahkan metode](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) dengan parameter yang relevan termasuk jenis grafik. Akses grafik melalui indeks dan [Menambahkan](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) sumber data untuk grafik.

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Membuat Bagan Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konversi Bagan ke Gambar" %}}


Untuk proses konversi grafik, pertama-tama buat grafik dengan jenis yang relevan menggunakan kode di atas atau akses dari lembar yang relevan. Tentukan jalur penyimpanan keluaran untuk gambar dan gunakan metode ToImage untuk konversi.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Mengonversi Bagan Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}