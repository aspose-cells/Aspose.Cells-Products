---
title: Gabungkan Berbagai File Excel menjadi Satu di Java
description: Gabungkan file Excel menggunakan Java menjadi beberapa lembar atau satu lembar. Gabungkan, gabungkan, atau gabungkan dokumen Excel ke PDF, Gambar dan HTML juga.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Penggabungan File Excel via Java" h2="Gabungkan dua atau lebih file Excel dalam satu spreadsheet menggunakan kode Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Perpustakaan Excel](/cells/id/java/)menyediakan berbagai cara untuk menggabungkan buku kerja dengan berbagai tipe konten seperti rumus, gambar, data, bagan, dll ke dalam satu dokumen spreadsheet. Format file yang didukung meliputi XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV dan banyak lagi.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan File Excel dengan Gambar dan Bagan" %}}
 Cara paling sederhana untuk menggabungkan dua file Excel yang memiliki gambar & bagan adalah dengan memanggil[Buku Kerja.gabungkan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metode. Memungkinkan untuk menggabungkan file Excel dengan tipe serupa ke dalam satu spreadsheet.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menggabungkan File Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan Beberapa File Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Metode ini mendukung penggabungan data, gaya, dan rumus file Excel ke spreadsheet baru dengan format yang sama. Ini adalah cara efisien untuk menggabungkan beberapa file saat menggunakan caching.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menggabungkan Beberapa File Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan File Excel dengan Menyalin Lembar Kerja" %}}
[Lembar Kerja.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)dapat digunakan untuk menyalin data dan memformat dari lembar kerja sumber ke lembar kerja lain di dalam atau antar buku kerja. Metode ini mengambil objek lembar kerja sumber sebagai parameter.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menyalin Lembar Kerja antar Buku Kerja" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Format Penggabungan Lainnya yang Didukung" subTitle="Menggunakan Java, Seseorang juga dapat menggabungkan banyak format file lainnya termasuk.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Nilai yang Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Templat Excel Microsoft" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Templat Excel yang mendukung Makro" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
