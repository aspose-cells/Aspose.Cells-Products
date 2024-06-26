---
title:  Cari dan ganti teks di dokumen XLSM via .NET
weight: 2370
description: Kode sumber C# untuk menyunting informasi sensitif dalam file XLSM di Kerangka .NET, Inti .NET, Mono atau Platform Xamarin.
keywords: [C# Aspose.Cells., c# Search and replace text in XLSM file., c# redact XLSM file., c# edit XLSM file., c# XLSM file redaction., c# Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Sunting XLSM Format di C#" h2="Informasi redaksi sensitif dokumen XLSM asli dan berkinerja tinggi menggunakan API sisi server Aspose.Cells for .NET, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Redaksi File XLSM Menggunakan C#" %}}

 Untuk menyunting file XLSM, kami akan menggunakan[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API yang merupakan manipulasi dokumen yang kaya fitur, kuat dan mudah digunakan API untuk platform C#. Membuka[NuGet](https://www.nuget.org/packages/aspose.cells) manajer paket, cari**Aspose.Cells** dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Menyunting File XLSM di C#" %}}

{{% blocks/products/pf/agp/text %}}

 Pencarian dokumen dasar dan mengganti teks dalam konten, komentar atau metadata dengan[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API dapat dilakukan hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

+ Muat file XLSM.
+ Pilih lembar.
+ Buat objek FindOptions.
Atur Opsi Pencarian
+ Ulangi setiap sel dan gunakan metode Temukan.
+ Simpan buku kerja.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 API kami didukung di semua platform dan Sistem Operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Platform Xamarin
-  Lingkungan pengembangan seperti Microsoft Visual Studio
-  Tambahkan referensi ke DLL Aspose.Cells for .NET di proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redaksi File XLSM - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xlsm");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //find only whole word and not part of any word.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xlsm");

// Find/Replace in whole workbook.

Workbook wb = new Workbook("e:\test2\Input.xlsm");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Redaksi Online XLSM" sectionDescription=" Cari dan ganti teks pada isi, komentar atau metadata di dokumen XLSM sekarang juga dengan mengunjungi kami[Situs web Demo Langsung](https://products.aspose.app/cells/redaction). Demo langsung memiliki manfaat sebagai berikut" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSM Anda." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Itu akan segera disunting." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
File dengan ekstensi XLSM merupakan jenis file Spreadsheet yang mendukung Makro. Dari sudut pandang aplikasi, Makro adalah kumpulan instruksi yang digunakan untuk mengotomatisasi proses. Makro digunakan untuk mencatat langkah-langkah yang dilakukan berulang kali dan memfasilitasi pelaksanaan tindakan dengan menjalankan kembali makro. Makro diprogram dengan Visual Basic for Applications (VBA) Microsoft dari dalam Buku Kerja Excel menggunakan Editor Visual Basic dan dapat dijalankan/debug langsung dari sana.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Redaksi Lain yang Didukung" subTitle="Dengan menggunakan C#, seseorang dapat dengan mudah menyunting berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
