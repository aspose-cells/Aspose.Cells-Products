---
title:  Cari dokumen TSV tanpa membuka via .NET
weight: 2810
description: Kode sumber C# untuk mencari kata dengan pola dalam file TSV pada Kerangka .NET, Inti .NET, Mono atau Platform Xamarin.
keywords: [C# Aspose.Cells., c# search words with pattern in tsv file., c# find words with pattern in tsv file., c# search string with pattern in tsv file., c# find words with pattern in tsv file., c# search words in tsv file., c# find words in tsv file., c# search string in tsv file., c# find string in tsv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cari TSV Format di C#" h2="Pencarian dokumen TSV asli dan berkinerja tinggi menggunakan API sisi server Aspose.Cells for .NET, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mencari File TSV Menggunakan C#" %}}

 Untuk mencari file TSV, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang merupakan pencarian dokumen yang kaya fitur, kuat dan mudah digunakan API untuk platform C#. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 **Aspose.Cells** 
 dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Mencari File TSV di C#" %}}

{{% blocks/products/pf/agp/text %}}

 Pencarian dokumen dasar dengan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API dapat dilakukan hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

+ Muat file TSV menggunakan kelas Buku Kerja.
+ Dapatkan sel di lembar yang relevan.
+ Cari Numbers, Tanggal dan Teks menggunakan metode Temukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 API kami didukung di semua platform dan Sistem Operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Platform Xamarin
-  Lingkungan pengembangan seperti Microsoft Visual Studio
-  Tambahkan referensi ke DLL Aspose.Cells for .NET di proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cari TSV File - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.tsv");

// get cells collection
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell with the input string
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell containing with the input string
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online TSV Cari Demo Langsung" sectionDescription=" Cari teks, kata, frasa dalam dokumen TSV sekarang juga dengan mengunjungi kami[Situs web Demo Langsung](https://products.aspose.app/cells/search). Demo langsung memiliki manfaat sebagai berikut" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Cukup unggah file TSV Anda." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Hasil pencarian langsung muncul." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV " readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Format file Nilai yang Dipisahkan Tab (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Format file, mirip dengan CSV, digunakan untuk mengatur data secara terstruktur untuk mengimpor dan mengekspor antar aplikasi yang berbeda. Format ini terutama digunakan untuk impor/ekspor dan pertukaran data dalam aplikasi dan database Spreadsheet. Setiap catatan dalam file TSV terkandung dalam satu baris file teks di mana setiap nilai bidang dipisahkan oleh karakter tab. Jenis media untuk format file TSV adalah nilai yang dipisahkan teks/tab.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Pencarian Lainnya yang Didukung" subTitle="Dengan menggunakan C#, seseorang juga dapat mencari format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="Nilai yang Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
