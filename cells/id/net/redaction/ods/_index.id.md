---
title: Cari dan ganti teks dalam dokumen ODS melalui .NET 
weight: 6100
url: /id/net/redaction/ods/ 
description: C# kode sumber untuk menyunting informasi sensitif dalam file ODS pada .NET Framework, .NET Core, Mono atau Platform Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Redaksi Format ODS di C#" h2="Informasi redaksi sensitif dokumen ODS asli dan berkinerja tinggi menggunakan Aspose.Cells for .NET API sisi server, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Redact File ODS Menggunakan C#" %}}

 Untuk menyunting file ODS, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang kaya fitur, canggih, dan mudah digunakan manipulasi dokumen API untuk C# platform. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 *{/0}Aspose.Cells** 
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Redact File ODS di C#" %}}

{{% blocks/products/pf/agp/text %}}

 Pencarian dokumen dasar dan mengganti teks dalam konten, komentar, atau metadata dengan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API dapat dilakukan hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

+ Muat file ODS.
+ Pilih lembar.
+ Buat objek FindOptions.
+ Atur Opsi Pencarian
+ Ulangi setiap sel dan gunakan metode Temukan.
+ Simpan buku kerja.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 API kami didukung di semua platform utama dan Sistem Operasi. Sebelum mengeksekusi kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Xamarin Platforms- Lingkungan pengembangan seperti Microsoft Visual Studio- Aspose.Cells for .NET DLL yang dirujuk dalam proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redaksi Berkas ODS - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.ods");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //temukan hanya seluruh kata dan bukan bagian dari kata apa pun.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.ods");

// Temukan/Ganti di seluruh buku kerja.

Workbook wb = new Workbook("e:\test2\Input.ods");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.ods");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Redaksi ODS Online" sectionDescription="Cari dan ganti teks dalam konten, komentar, atau metadata dalam dokumen ODS sekarang juga dengan mengunjungi . kami [Situs web Demo Langsung](https://products.aspose.app/cells/redaction). Demo langsung memiliki manfaat sebagai berikut" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file ODS Anda." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Itu akan diedit secara instan." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
File dengan ekstensi ODS adalah singkatan dari format OpenDocument Spreadsheet Document yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF ke dalam baris dan kolom. Ini adalah format berbasis XML dan merupakan salah satu dari beberapa subtipe dalam keluarga Open Document Formats (ODF). Format ditentukan sebagai bagian dari spesifikasi ODF 1.2 yang diterbitkan dan dikelola oleh OASIS. Sejumlah aplikasi di Windows serta sistem operasi lain dapat membuka file ODS untuk diedit dan dimanipulasi termasuk Microsoft Excel, NeoOffice dan LibreOffice. File ODS juga dapat dikonversi ke format spreadsheet lain seperti XLS, XLSX, dan lainnya dengan aplikasi yang berbeda. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Redaksi Lainnya yang Didukung" subTitle="Dengan menggunakan C#, seseorang dapat dengan mudah menyunting berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsm/" name="XLSM" description="File Spreadsheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}