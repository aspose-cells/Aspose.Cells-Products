---
title:  Lindungi dan kunci dokumen XLS via .NET
weight: 7010
description: Kode sumber C# untuk mengunci file XLS menggunakan kata sandi pada Kerangka .NET, Inti .NET, Mono atau Platform Xamarin.
keywords: [C# Aspose.Cells., c# Lock XLS files., c# How to Protect and lock XLS document., c# Protect XLS files., Encrypt XLS Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Enkripsi File XLS melalui C#" h2="Spreadsheet Excel yang dilindungi kata sandi termasuk format XLS menggunakan Perpustakaan .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Melindungi File XLS Menggunakan C#" %}}

 Untuk melindungi file XLS, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang merupakan perlindungan dokumen yang kaya fitur, kuat dan mudah digunakan API untuk platform C#. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 **Aspose.Cells** 
 dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lindungi XLS melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Anda membutuhkan
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 direferensikan dalam proyek Anda untuk menjalankan alur kerja berikut.

{{% /blocks/products/pf/agp/text %}}

1.  Buat instance kelas Buku Kerja dengan jalur ke file XLS
1.  Dapatkan lembar kerja default atau apa pun untuk menambahkan perlindungan
1.  Lindungi Lembar Kerja dengan metode Lembar Kerja.Proteksi
1.  Lindungi Buku Kerja dengan metode Buku Kerja.Proteksi
1.  Simpan hasilnya dalam format XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET didukung di semua sistem operasi utama. Pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Platform Xamarin
-  Lingkungan pengembangan seperti Microsoft Visual Studio
-  Tambahkan referensi ke DLL Aspose.Cells for .NET di proyek Anda

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="" %}}

```cs

// load the XLS Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xls");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xls");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Melindungi XLS" sectionDescription=" Periksa demo langsung kami[mengenkripsi file XLS](https://products.aspose.app/cells/protect/xls) dengan manfaat berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLS dan tekan tombol \"Buka Kunci\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLS yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat dengan Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Workbook dimana setiap workbook dapat memiliki satu atau lebih lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama untuk digunakan sekarang.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Perlindungan Lainnya yang Didukung" subTitle="Dengan menggunakan C#, seseorang dapat dengan mudah melindungi format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
