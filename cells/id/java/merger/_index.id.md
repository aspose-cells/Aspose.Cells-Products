---
title: Gabungkan File Excel yang Berbeda menjadi Satu di Java
description: Gabungkan file Excel menggunakan Java menjadi beberapa lembar atau satu lembar. Gabungkan, gabungkan, atau gabungkan dokumen Excel ke PDF, Gambar, dan HTML juga.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Penggabungan Berkas Excel via Java" h2="Gabungkan dua atau lebih file Excel dalam satu spreadsheet menggunakan kode Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Perpustakaan Excel](/cells/id/java/) menyediakan berbagai cara untuk menggabungkan buku kerja dengan berbagai jenis konten seperti rumus, gambar, data, bagan, dll ke dalam satu dokumen spreadsheet. Format file yang didukung termasuk XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV dan lainnya.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan File Excel dengan Gambar dan Bagan" %}}
 Cara termudah untuk menggabungkan dua file Excel yang memiliki gambar & bagan adalah dengan memanggil[Workbook.gabungkan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metode. Ini memungkinkan untuk menggabungkan file Excel dengan tipe serupa ke dalam satu spreadsheet.
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

{{% blocks/products/pf/feature-page-section h2="Menggabungkan Beberapa File Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)metode ini mendukung penggabungan data, gaya, dan rumus file Excel ke spreadsheet baru dengan format yang sama. Ini adalah cara yang efisien untuk menggabungkan beberapa file saat menggunakan caching.
{{% blocks/products/pf/feature-page-code h3="Kode Java untuk Menggabungkan Beberapa File Excel" %}}

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

{{% blocks/products/pf/feature-page-section h2="Menggabungkan File Excel dengan Menyalin Lembar Kerja" %}}
[Lembar kerja.salinan](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) dapat digunakan untuk menyalin data dan pemformatan dari lembar kerja sumber ke lembar kerja lain di dalam atau di antara buku kerja. Metode mengambil objek lembar kerja sumber sebagai parameter.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Buka File Spreadsheet Dokumen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Format Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="File lembar bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Berkas Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Templat Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Template dengan Makro Excel yang diaktifkan" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
