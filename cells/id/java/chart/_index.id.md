---
title: Buat Bagan Excel dan Konversikan ke Gambar melalui Java
url: /id/java/chart/
description: Java kode sumber untuk menggambar dan mengonversi bagan atau diagram di Microsoft Excel menggunakan Java Pustaka. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi dan Pembuatan Bagan File Microsoft<sup>&reg;</sup> Excel melalui Java" h2="Konversi bagan dokumen Excel menjadi gambar serta buat berbagai bagan menggunakan API sisi server dalam Java aplikasi berbasis." >}}


{{% blocks/products/pf/feature-page-summary %}}

Menganalisis data melalui grafik menunjukkan gambaran yang lebih besar dan mudah untuk membuat keputusan yang lebih tepat dengan wawasan yang lebih jelas. [Java Perpustakaan Excel](/cells/java/) mendukung menggambar pembuatan bagan berbeda yang terdaftar oleh [Tipe Bagan](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) termasuk diagram lingkaran, piramida, garis, dan gelembung. Selain itu, ini juga mengubah grafik menjadi gambar. API menyediakan [Kelas grafik](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) untuk mewakili satu bagan Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konversi Bagan Excel ke Gambar" %}}

Proses mengonversi grafik ke gambar termasuk JPG, PNG, TIFF, BMP dll adalah, Gunakan [buku kerja](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) kelas untuk memuat file Excel, pilih yang relevan [meja kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) berisi bagan atau mengulangi setiap bagan di setiap lembar kerja. Mendefinisikan [Opsi GambarAtauCetak](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) dan render gambar output dari Bagan menggunakan [Bagan.keGambar](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Mengonversi Bagan Excel ke Gambar" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Buat Bagan dalam File Excel" %}}

Membuat bagan menggunakan Excel API itu sederhana, karena API menyediakan kumpulan kelas yang berbeda seperti Sumbu, Bagan, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection dll untuk berbagai jenis bagan. Prosesnya adalah, Buat objek kelas Buku Kerja dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Untuk sumber data bagan, masukkan nilai ke sel lembar kerja menggunakan [setNilai](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) metode. Gunakan koleksi ChartCollection [tambahkan metode](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) untuk menambahkan bagan, tentukan jenis bagan dengan enumerasi ChartType. Akses objek Bagan baru dari koleksi ChartCollection dengan meneruskan indeksnya. Menggunakan [Koleksi Seri](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objek charting untuk menentukan sumber data diagram.

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Membuat Bagan Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}