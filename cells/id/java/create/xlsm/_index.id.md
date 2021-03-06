---
title: Buat File MS Excel XLSM melalui Java 
url: /id/java/create-xlsm/ 
description: Java Contoh kode untuk membuat dokumen XLSM. Gunakan kode ini untuk membuat file MS Excel XLSM dalam Java desktop atau aplikasi web berbasis.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Buat Dokumen XLSM melalui Java" h2="Pembuatan spreadsheet MS Excel XLSM native dan berkinerja tinggi secara terprogram menggunakan Java library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Menghasilkan file MS Excel XLSM secara dinamis dalam menjalankan aplikasi itu mudah. Untuk membuat dokumen XLSM dari awal tanpa memerlukan MS Office, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang menawarkan berbagai fitur untuk pembuatan, manipulasi, dan konversi spreadsheet menggunakan platform Java. Pengembang dapat dengan mudah meningkatkan kode untuk memperbarui data sel, menghasilkan bagan atau grafik serta membuat tabel pivot, menambahkan rumus tingkat sel, dan lainnya di spreadsheet.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara Membuat XLSM melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Sangat mudah bagi pengembang untuk membuat, memuat, memodifikasi, dan mengonversi spreadsheet MS Excel XLSM dalam menjalankan berbagai aplikasi pelaporan untuk pemrosesan data hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Buat instance dari [Kelas buku kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).1. Akses lembar kerja yang relevan menggunakan metode getWorksheets.get().1. Pilih sel yang relevan, masukkan nilainya ke sel yang diinginkan menggunakan nama sel, seperti A1, B3, dll.1. Simpan buku kerja sebagai format XLSM menggunakan metode save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

Sebelum menjalankan Java kode sumber contoh konversi, pastikan Anda memiliki prasyarat berikut.  

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Aspose.Cells for Java mendukung versi Java berikut: J2SE 6.0 (1.6), J2SE 7.0 (1.7), atau lebih tinggi.- [Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.](https://docs.aspose.com/cells/java/installation/) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode sumber berikut menunjukkan cara membuat file MS Excel XLSM menggunakan Java." offSpacer="" %}}

```cs

// Buat buku kerja baru
Workbook wkb = new Workbook();

// Akses lembar kerja pertama dari buku kerja.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Tambahkan konten yang relevan di sel
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Simpan buku kerja sebagai file XLSM
wkb.save("Excel.xlsm"); 

// Untuk meningkatkan kode untuk fungsionalitas lebih lanjut, berikut adalah lebih banyak fungsi
// getCells() dan setValue untuk memodifikasi konten sel
// getCharts().add() untuk menambahkan grafik
// getPivotTables().add() untuk membuat Tabel Pivot
// getCells().get(int cell id).setFormula untuk menambahkan rumus level sel


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Pustaka Pemrograman Spreadsheet Excel yang mampu membangun aplikasi lintas platform dengan kemampuan untuk menghasilkan, memodifikasi, mengonversi, merender, dan mencetak file MS Excel XLSM. Java Excel API tidak hanya mengonversi antar format spreadsheet, tetapi juga dapat merender file Excel sebagai gambar, PDF, HTML, ODS, dan lainnya, sehingga menjadikannya pilihan yang sempurna untuk bertukar dokumen dalam format standar industri.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Pembuatan Spreadsheet yang Didukung Lainnya" subTitle="Anda juga dapat membuat format Microsoft Excel lainnya termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xls/" name="XLS" description="Microsoft Excel Spreadsheet (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsx/" name="XLSX" description="Buka Buku Kerja XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsb/" name="XLSB" description="Buku Kerja Biner Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsm/" name="XLSM" description="Spreadsheet berkemampuan makro" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlt/" name="XLT" description="Excel 97 - 2003 Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltx/" name="XLTX" description="Templat Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltm/" name="XLTM" description="Template Excel Macro-Enabled" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-csv/" name="CSV" description="Nilai Dipisahkan Koma" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-tsv/" name="TSV" description="Nilai yang Dipisahkan Tab" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-ods/" name="ODS" description="Spreadsheet OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
