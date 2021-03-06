---
title: Lindungi dan kunci dokumen XLSX melalui .NET 
weight: 90
url: /id/net/protect/xlsx/ 
description: C# kode sumber untuk mengunci file XLSX menggunakan sandi pada Platform .NET Framework, .NET Core, Mono atau Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Enkripsi File XLSX melalui C#" h2="Spreadsheet Excel yang dilindungi sandi termasuk format XLSX menggunakan .NET Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Melindungi File XLSX Menggunakan C#" %}}

 Untuk melindungi file XLSX, kami akan menggunakan
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API yang kaya fitur, kuat, dan mudah digunakan perlindungan dokumen API untuk C# platform. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 *{/0}Aspose.Cells** 
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lindungi XLSX melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

 Anda membutuhkan
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 direferensikan dalam proyek Anda untuk menjalankan alur kerja berikut.

{{% /blocks/products/pf/agp/text %}}

1. Buat instance kelas Workbook dengan jalur ke file XLSX1. Dapatkan default atau Lembar Kerja apa pun untuk menambahkan perlindungan1. Lindungi Lembar Kerja dengan Lembar Kerja. Metode proteksi1. Lindungi Buku Kerja dengan Buku Kerja. Metode proteksi1. Simpan hasil dalam format XLSX
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET didukung di semua sistem operasi utama. Pastikan saja Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Mono atau Xamarin Platforms- Lingkungan pengembangan seperti Microsoft Visual Studio- Aspose.Cells for .NET dirujuk dalam proyek Anda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="" %}}

```cs

// muat file XLSX Excel 
var book = new Aspose.Cells.Workbook("unlocked.xlsx");

// akses lembar kerja pertama
var worksheet = book.Worksheets[0];

// lindungi lembar kerja dengan kata sandi
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// lindungi seluruh buku kerja dengan kata sandi
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// simpan file yang dimodifikasi dalam format default
book.Save("protected.xlsx");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for .NET API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Melindungi XLSX" sectionDescription="Periksa demo langsung kami untuk [mengenkripsi file XLSX](https://products.aspose.app/cells/protect/xlsx) dengan manfaat sebagai berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSX dan tekan tombol \"Buka Kunci\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLSX yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan dirilisnya Microsoft Office 2007. Berdasarkan struktur yang diatur menurut Konvensi Pembungkus Terbuka sebagaimana diuraikan dalam Bagian 2 dari standar OOXML ECMA-376, format barunya adalah paket zip yang berisi sejumlah file XML. Struktur dan file yang mendasarinya dapat diperiksa hanya dengan membuka ritsleting file .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Perlindungan Lain yang Didukung" subTitle="Dengan menggunakan C#, seseorang dapat dengan mudah melindungi format lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="File Spreadsheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}