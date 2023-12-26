---
title: Membuat Bagan Excel dan Konversi ke Gambar via Java
description:  Kode sumber Java untuk menggambar dan mengubah bagan atau diagram di Microsoft Excel menggunakan Library Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi dan Pembuatan Bagan File Excel via Java" h2="Konversikan bagan dokumen Excel menjadi gambar serta buat berbagai bagan menggunakan API sisi server dalam aplikasi berbasis Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Menganalisis data melalui grafik menunjukkan gambaran yang lebih besar dan mudah untuk membuat keputusan yang lebih tepat dengan wawasan yang lebih jelas.[Java Perpustakaan Excel](/cells/id/java/) mendukung menggambar pembuatan bagan berbeda yang dicantumkan oleh[Tipe Bagan](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) termasuk diagram lingkaran, piramida, garis, dan gelembung. Selain itu, ini juga mengubah grafik menjadi gambar. API menyediakan a[Kelas grafik](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) untuk mewakili satu bagan Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Ubah Bagan Excel menjadi Gambar" %}}

 Proses mengubah grafik menjadi gambar termasuk JPG, PNG, TIFF, BMP dll adalah, Gunakan[Buku Kerja](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) kelas untuk memuat file Excel, pilih yang relevan[meja kerja](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) berisi bagan atau mengulangi setiap bagan di setiap lembar kerja. Mendefinisikan[Opsi GambarAtauCetak](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) dan merender gambar keluaran Bagan menggunakan[Bagan.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Mengubah Bagan Excel menjadi Gambar" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Buat Bagan dalam File Excel" %}}

Membuat grafik menggunakan Excel API sangatlah sederhana, karena API menyediakan kumpulan kelas yang berbeda seperti Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection dll untuk berbagai jenis grafik. Prosesnya adalah, Buat objek kelas Buku Kerja dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Untuk sumber data bagan, masukkan nilai ke sel lembar kerja menggunakan[setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) metode. Gunakan koleksi ChartCollection[tambahkan metode](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) untuk menambahkan bagan, tentukan jenis bagan dengan enumerasi ChartType. Akses objek Chart baru dari koleksi ChartCollection dengan meneruskan indeksnya. Menggunakan[Koleksi Seri](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objek bagan untuk menentukan sumber data bagan.

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Membuat Grafik Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
