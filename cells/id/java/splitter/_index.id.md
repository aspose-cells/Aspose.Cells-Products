---
title: Pisahkan Spreadsheet Excel menjadi Lembar Kerja di Java
description: Kode sumber Java yang menjelaskan cara membagi file Excel Microsoft menjadi beberapa dokumen menggunakan perpustakaan Excel Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Pemisahan Berkas Excel via Java" h2="Pisahkan spreadsheet Excel menjadi lembar kerja dalam aplikasi berbasis Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Ada berbagai skenario, Ketika ada kebutuhan untuk membagi file Excel seperti spreadsheet yang berisi data siswa dengan alokasi satu lembar untuk setiap siswa. Dan ada kebutuhan untuk membagi setiap lembar siswa menjadi file terpisah. Untuk mengotomatiskannya aplikasi via Java,[Java Excel API](/cells/id/java/) apakah ada untuk membagi dokumen Excel menjadi lembaran. Format yang didukung antara lain XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Dokumen Excel menjadi Beberapa File" %}}

Cara termudah untuk membagi file Excel menjadi lembar adalah, Akses semua lembar, ulangi setiap lembar dan simpan satu per satu dalam format yang diinginkan. Untuk memuat lembar kerja, API menyediakan[Buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) kelas.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metode mendapat jumlah lembar. Ulangi setiap lembar dan gunakan[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) untuk mengakses sheet tertentu. Pindahkan data lembar yang dipilih ke dalam objek kelas Buku Kerja yang baru dibuat dengan menggunakan[Metode salin](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Akhirnya simpan ke dalam format yang diperlukan.

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Membagi File Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Lembar Kerja Excel menjadi Panel" %}}

API juga menyediakan fungsionalitas untuk membagi lembar kerja Excel menjadi panel yang berbeda. Prosesnya adalah, Muat file menggunakan kelas Workbook. Pilih lembar kerja pertama atau lembar apa pun yang diperlukan dengan memberikan indeksnya. Panggil setActiveCell yang memiliki indeks sel yang relevan sebagai parameter. Dan akhirnya pisahkan jendela lembar kerja menjadi panel yang berbeda dengan memanggil metode split() .

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Membagi Lembar Excel menjadi Tampilan Pane" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
