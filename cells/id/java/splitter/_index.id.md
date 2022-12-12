---
title: Pisahkan Spreadsheet Excel menjadi Worksheet di Java

description: Java kode sumber yang menjelaskan cara membagi berkas Microsoft Excel menjadi beberapa dokumen menggunakan Java pustaka Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pemisahan File Microsoft<sup>&reg;</sup> Excel melalui Java" h2="Pisahkan spreadsheet Excel menjadi lembar kerja dalam Java aplikasi berbasis" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ada berbagai skenario, Ketika ada kebutuhan untuk membagi file Excel seperti spreadsheet yang berisi data siswa dengan alokasi satu lembar untuk setiap siswa. Dan ada kebutuhan untuk membagi setiap lembar siswa bijaksana sebagai file terpisah. Untuk mengotomatiskannya melalui Java aplikasi, [Java Excel API](/cells/java/) apakah ada untuk membagi dokumen Excel sheetwise. Format yang didukung termasuk XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Dokumen Excel menjadi Beberapa File" %}}

Cara paling sederhana untuk membagi file Excel menjadi lembar adalah, Akses semua lembar, ulangi setiap lembar dan simpan satu per satu dalam format yang diinginkan. Untuk memuat lembar kerja, API menyediakan [buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) kelas. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metode mendapatkan jumlah lembar. Ulangi setiap lembar dan gunakan [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) untuk mengakses lembar tertentu. Pindahkan data lembar yang dipilih ke objek kelas Buku Kerja yang baru dibuat dengan menggunakan [Salin metode](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Terakhir simpan ke dalam format yang diperlukan.

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Memisahkan File Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Lembar Kerja Excel menjadi Panel" %}}

API juga menyediakan fungsionalitas untuk membagi lembar kerja Excel menjadi panel yang berbeda. Prosesnya, Load file menggunakan kelas Workbook. Pilih lembar kerja pertama atau lembar apa pun yang diperlukan dengan memberikan indeksnya. Panggil setActiveCell yang memiliki indeks sel yang relevan sebagai parameter. Dan akhirnya pisahkan jendela lembar kerja menjadi panel yang berbeda dengan memanggil metode split().

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Membagi Lembar Excel menjadi Tampilan Panel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
