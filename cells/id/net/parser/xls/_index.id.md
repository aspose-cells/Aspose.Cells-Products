---
title:  Ekstrak teks dan gambar dari dokumen XLS via .NET
weight: 5600
description: Kode sumber C# untuk mengekstrak teks dan gambar dari file XLS di Kerangka .NET, Inti .NET, Mono atau Platform Xamarin.
keywords: [C# Aspose.Cells., c# Extract text and images from XLS file., c# How to Parse XLS File., c# Extract text from XLS file., Extract images from XLS file using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Parsing XLS Format di C#" h2="Penguraian dokumen XLS asli dan berkinerja tinggi menggunakan API sisi server Aspose.Cells for .NET, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Parsing File XLS Menggunakan C#" %}}

 Untuk mengurai file XLS, kami akan menggunakan[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API yang merupakan manipulasi dokumen yang kaya fitur, kuat dan mudah digunakan API untuk platform C#. Membuka[NuGet](https://www.nuget.org/packages/aspose.cells) manajer paket, cari
 **Aspose.Cells** dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Parsing File XLS di C#" %}}

{{% blocks/products/pf/agp/text %}}

 Penguraian dokumen dasar dengan[Aspose.Cells for .NET](https://products.aspose.com/cells/net)API dapat dilakukan hanya dengan beberapa baris kode. Parsing teks & gambar dari file Microsoft Excel XLS, XLSX, XLSM, XLSB dan OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ Muat dokumen XLS.
+ Pilih lembar.
+ Dapatkan gambar dan jenis gambar.
+ Simpan gambar.
+ Simpan dokumen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 API kami didukung di semua platform dan Sistem Operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Platform Xamarin
-  Lingkungan pengembangan seperti Microsoft Visual Studio
-  Tambahkan referensi ke DLL Aspose.Cells for .NET di proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Parsing XLS File - C#" offSpacer="" %}}

```cs
    // extract images from Worksheets 
    // open a template Excel file
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xls");
    
    // get the first worksheet
    Worksheet worksheet = workbook.Worksheets[0];
    
    // get the first Picture in the first worksheet
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // set the output image file path
    string picformat = pic.ImageType.ToString();
                
    // Note: you may evaluate the image format before specifying the image path
    // define ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specify the image format
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // save the image
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Parser Online XLS" sectionDescription="Ekstrak teks dan gambar dari dokumen XLS sekarang juga dengan mengunjungi kami[Situs web Demo Langsung](https://products.aspose.app/cells/parser). Demo langsung memiliki manfaat sebagai berikut" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLS Anda." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ini akan diuraikan secara instan." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat dengan Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Workbook dimana setiap workbook dapat memiliki satu atau lebih lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama untuk digunakan sekarang.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Parsing Lainnya yang Didukung" subTitle="Menggunakan C#, seseorang dapat dengan mudah mengurai format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
