---
title:  Ubah XLS menjadi Byte Array melalui C#
weight: 7690
description: C# Contoh kode untuk konversi XLS ke Byte Array. Gunakan kode ini untuk konversi Excel XLS ke Byte Array dalam VB.NET, Asp.NET atau aplikasi berbasis .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ubah XLS menjadi array byte melalui C#" h2="Asli dan berkinerja tinggi Microsoft Excel XLS ke konversi array byte atau sebaliknya untuk pemrosesan data spreadsheet menggunakan API sisi server .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array berguna untuk pemrosesan atau penyimpanan data. Anda dapat mengonversi file XLS ke Byte Array serta a**Array Byte ke XLS** dokumen menggunakan bahasa C#. Untuk mengonversi XLS ke array byte, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang menawarkan fitur berbeda untuk manipulasi dan konversi dokumen menggunakan platform .NET.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLS ke Byte Array melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Mudah bagi pengembang untuk memuat & mengonversi file XLS ke array byte untuk tugas manipulasi lebih lanjut hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1.  Sertakan namespace di file kelas Anda
1.  Muat File input XLS menggunakan Buku Kerja
1.  Inisialisasi objek MemoryStream
1.  Ubah data aliran menjadi array byte
1.  Proses data sesuai kebutuhan Anda

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

Pastikan saja sistem memiliki Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin serta lingkungan pengembangan seperti Microsoft Visual Studio.

{{% /blocks/products/pf/agp/text %}}

-  Instal dari baris perintah sebagai<code>nuget install Aspose.Cells</code> atau melalui Package Manager Console dari Visual Studio dengan<code>Install-Package Aspose.Cells</code>.
-  Alternatifnya, dapatkan penginstal MSI offline atau semua DLL dalam file ZIP dari<a href="https://downloads.aspose.com/cells/net">unduhan</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan XLS ke array byte C# Konversi" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xls");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xls);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Perpustakaan Pemrograman Spreadsheet Excel yang mampu membangun aplikasi lintas platform dengan kemampuan untuk menghasilkan, memodifikasi, mengonversi, merender, dan mencetak semua file Excel. .NET Excel API tidak hanya mengkonversi antar format spreadsheet, tetapi juga dapat merender file Excel termasuk XLS sebagai gambar, PDF, HTML, ODS dan banyak lagi, sehingga menjadikannya pilihan sempurna untuk bertukar dokumen dalam format standar industri.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat dengan Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Workbook dimana setiap workbook dapat memiliki satu atau lebih lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama untuk digunakan sekarang.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi yang Didukung Lainnya" subTitle="Anda juga dapat mengonversi format file lain menjadi array byte atau sebaliknya termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS Ke Array Byte" description="Microsoft Lembar Bentang Excel (Warisan)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX Ke Array Byte" description="Buka Buku Kerja XML" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB Ke Array Byte" description="Buku Kerja Biner Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM Ke Array Byte" description="Spreadsheet berkemampuan makro" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT Ke Array Byte" description="Templat Excel 97 - 2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX Ke Array Byte" description="Templat Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM Ke Array Byte" description="Templat Excel yang Diaktifkan Makro" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV Ke Array Byte" description="Nilai yang Dipisahkan Koma" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV Ke Array Byte" description="Tab Nilai Terpisah" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS Ke Array Byte" description="Lembar Bentang OpenDocument" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS Sampai PDF" description="Format Dokumen Portabel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS Sampai HTML" description="Hyper Text Markup Language" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX Sampai XPS" description="Microsoft Berkas Excel OOXML Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX Sampai HTML" description="Berkas OOXML Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX Sampai SVG" description="Grafik Vektor yang Dapat Diskalakan" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS Sampai JPEG" description="JPEG Gambar" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
