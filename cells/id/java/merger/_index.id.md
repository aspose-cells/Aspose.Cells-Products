---
title: Gabungkan File Excel yang Berbeda menjadi Satu di Java
url: /id/java/merger/
description: Gabungkan file Excel menggunakan Java menjadi beberapa lembar atau satu lembar. Gabungkan, gabungkan, atau gabungkan dokumen Excel ke PDF, Gambar, dan HTML juga.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Penggabungan File Excel melalui Java" h2="Gabungkan dua atau lebih file Excel dalam satu spreadsheet menggunakan Java kode" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Perpustakaan Excel](/cells/java/) menyediakan banyak cara untuk menggabungkan buku kerja dengan berbagai jenis konten seperti rumus, gambar, data, bagan dll ke dalam satu dokumen spreadsheet. Format file yang didukung termasuk XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV, dan lainnya.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan File Excel dengan Gambar dan Bagan" %}}
Cara termudah untuk menggabungkan dua file Excel yang memiliki gambar & bagan adalah dengan memanggil [buku kerja.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metode. Hal ini memungkinkan untuk menggabungkan file Excel dari jenis yang sama ke dalam satu spreadsheet.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menggabungkan File Excel" %}}

```cs
// muat file Excel pertama
var book1 = new Workbook("with-charts.xlsx");
// memuat file Excel kedua ke dalam instance terpisah
var book2 = new Workbook("with-images.xlsx");

// menggabungkan dua buku kerja
book1.combine(book2);
// simpan buku kerja target 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan Beberapa File Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) metode ini mendukung penggabungan data, gaya, dan rumus file Excel ke spreadsheet baru dengan format yang sama. Ini adalah cara yang efisien untuk menggabungkan beberapa file saat menggunakan caching. 
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menggabungkan Beberapa File Excel" %}}

```cs
// buat Array (panjang = 2)
String[] files = new String[2];
// tentukan jalur file yang akan digabungkan
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// gabungkan file untuk menyimpan hasilnya
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan File Excel dengan Menyalin Lembar Kerja" %}}
[lembar kerja.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)dapat digunakan untuk menyalin data dan pemformatan dari lembar kerja sumber ke lembar kerja lain di dalam atau di antara buku kerja. Metode ini mengambil objek lembar kerja sumber sebagai parameter.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menyalin Lembar Kerja antar Buku Kerja" %}}

```cs
// Buat Buku Kerja.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Buat Buku Kerja lain.
Workbook excelWorkbook1 = new Workbook();

// Salin lembar pertama buku pertama ke buku kedua.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Simpan file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}