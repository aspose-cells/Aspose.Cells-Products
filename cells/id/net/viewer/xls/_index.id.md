---
title: Lihat Format File XLS melalui .NET 
weight: 1260
url: /id/net/viewer/xls/ 
description: C# kode sumber untuk memuat, merender, dan menampilkan dokumen XLS pada .NET Framework, .NET Core, Mono atau Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Penampil Berkas XLS for .NET" h2="Lihat spreadsheet Excel & OpenOffice seperti XLS tanpa memerlukan Microsoft Excel atau Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Melihat File XLS Menggunakan C#" %}}

 Untuk melihat file XLS, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang kaya fitur, canggih, dan mudah digunakan API untuk C# platform yang akan digunakan dengan Pemirsa mana pun. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 *{/0}Aspose.Cells** 
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Melihat XLS melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells memudahkan pengembang untuk melihat file XLS hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file XLS dalam instance Workbook1. Buat instance HtmlSaveOptions & setel properti ExportHeadings ke true1. Simpan file XLS dalam format HTML menggunakan metode Workbook.Save1. Muat HTML yang dihasilkan di browser default dengan Process.Start
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET didukung di semua sistem operasi utama. Pastikan saja Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Xamarin Platforms- Lingkungan pengembangan seperti Microsoft Visual Studio- Aspose.Cells for .NET dirujuk dalam proyek Anda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# contoh kode untuk melihat file XLS" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// memuat file XLS dalam instance Workbook
var book = new Aspose.Cells.Workbook("template.xls");
// buat instance HtmlSaveOptions & setel properti ExportHeadings ke true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// simpan file XLS dalam format HTML
book.Save(output, options);
// memuat HTML yang dihasilkan di browser default
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Melihat XLS" sectionDescription="Periksa demo langsung kami untuk [Lihat XLS](https://products.aspose.app/cells/viewer/xls) dengan manfaat sebagai berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLS dan tekan tombol \"Lihat\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLS dari tautan, jika diperlukan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Buku Kerja di mana setiap buku kerja dapat memiliki satu atau beberapa lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama yang digunakan sekarang.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Penampil yang Didukung Lainnya" subTitle="Menggunakan C#, Seseorang juga dapat melihat banyak format file lainnya termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Nilai Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="txt" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="File Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Templat Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Template Excel Macro-enabled" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Templat Excel Office OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}