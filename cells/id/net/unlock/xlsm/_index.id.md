---
title:  Buka kunci dokumen XLSM via .NET
weight: 9810
description: Kode sumber C# untuk membuka kunci file XLSM yang dilindungi kata sandi di .NET Framework, .NET Core, Mono atau Platform Xamarin.
keywords: [C# Aspose.Cells., c# unlock XLSM files., c# how to unlock XLSM document., c# unprotect XLSM files., remove protection from XLSM files., decrypt XLSM Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Buka kunci XLSM Spreadsheet melalui C#" h2="Hapus perlindungan dari XLSM menggunakan perpustakaan .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Membuka Kunci File XLSM Menggunakan C#" %}}

 Untuk menghapus file proteksi XLSM, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Buka kunci XLSM melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Anda membutuhkan
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 direferensikan dalam proyek Anda untuk menjalankan alur kerja berikut.

{{% /blocks/products/pf/agp/text %}}

1.  Buat instance kelas Buku Kerja dengan jalur ke file XLSM yang dilindungi
1.  Dapatkan lembar kerja default atau apa pun untuk menghapus perlindungan
1.  Hapus proteksi Lembar Kerja dengan metode Lembar Kerja. Buka proteksi
1.  Hapus proteksi Buku Kerja dengan metode Buku Kerja. Buka proteksi
1.  Simpan hasilnya dalam format XLSM

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

// instantiate a Workbook object with protected XLSM file
var workbook = new Aspose.Cells.Workbook("protected.xlsm");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSM format
workbook.Save("unprotected.xlsm", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Membuka Kunci XLSM" sectionDescription=" Periksa demo langsung kami[membuka kunci file XLSM](https://products.aspose.app/cells/unlock/xlsm) dengan manfaat berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSM dan tekan tombol \"Buka Kunci\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLSM yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
File dengan ekstensi XLSM merupakan jenis file Spreadsheet yang mendukung Makro. Dari sudut pandang aplikasi, Makro adalah kumpulan instruksi yang digunakan untuk mengotomatisasi proses. Makro digunakan untuk mencatat langkah-langkah yang dilakukan berulang kali dan memfasilitasi pelaksanaan tindakan dengan menjalankan kembali makro. Makro diprogram dengan Visual Basic for Applications (VBA) Microsoft dari dalam Buku Kerja Excel menggunakan Editor Visual Basic dan dapat dijalankan/debug langsung dari sana.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Membuka Kunci Lainnya yang Didukung" subTitle="Dengan menggunakan C#, seseorang dapat dengan mudah menghapus proteksi/pembukaan berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
