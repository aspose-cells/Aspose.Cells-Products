---
title: Konversi CSV ke XLAM melalui C++ aplikasi 
url: /id/cpp/conversion/csv-to-xlam/ 
description: Contoh C++ kode konversi untuk dokumen CSV ke format XLAM. Pemrogram dapat menggunakan kode sumber ini untuk konversi CSV ke XLAM batch dalam Aplikasi C++ apa pun.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi CSV ke XLAM melalui C++" h2="Konversi CSV ke XLAM berperforma tinggi menggunakan pustaka C++ tanpa memerlukan penginstalan Microsoft Excel, OpenOffice, atau Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLAM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi CSV ke XLAM Menggunakan C++" %}}

 Untuk mengonversi CSV ke XLAM, kami akan menggunakan
 [Aspose.Cells untuk C++](https://products.aspose.com/cells/cpp) 
 API yang kaya fitur, canggih, dan mudah digunakan manipulasi dan konversi dokumen API untuk C++ platform. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 Aspose.Cells.Cpp 
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi CSV ke XLAM melalui C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ pengembang dapat dengan mudah mengonversi file CSV ke XLAM hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file CSV menggunakan Factory::CreateIWorkbook.1. Panggil metode Simpan().1. Lewati jalur file output dengan ekstensi file (XLAM).1. File XLAM akan disimpan di jalur yang ditentukan.1. Buka file XLAM di program yang kompatibel.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan C++ kode contoh konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV ke XLAM C++ Kode Sumber Konversi" offSpacer="" %}}

```cs
// Muat CSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// Simpan dalam format XLAM.
wkb->Save(u"convertedFile.xlam", SaveFormat_Xlam);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi CSV ke XLAM" sectionDescription="[Konversi CSV ke XLAM](https://products.aspose.app/cells/conversion/csv-to-xlam) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file CSV Anda, itu akan langsung dikonversi ke XLAM." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="C++ Pustaka Manipulasi File Excel" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

File dengan ekstensi CSV (Comma Separated Values) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Setiap baris dalam file CSV merupakan record baru dari kumpulan record yang terdapat dalam file tersebut. File tersebut dihasilkan ketika transfer data dimaksudkan dari satu sistem penyimpanan ke sistem penyimpanan lainnya. Karena semua aplikasi dapat mengenali record yang dipisahkan dengan koma, impor file data tersebut ke database dilakukan dengan sangat mudah. Hampir semua aplikasi spreadsheet seperti Microsoft Excel atau OpenOffice Calc dapat mengimpor CSV tanpa banyak usaha. Data yang diimpor dari file tersebut diatur dalam sel spreadsheet untuk representasi kepada pengguna.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLAM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlam/" >}}

XLAM adalah file Add-In Excel Macro-Enabled yang digunakan untuk menambahkan fungsi baru ke Excel. Add-In adalah program tambahan yang menjalankan kode tambahan dan menyediakan fungsionalitas tambahan untuk spreadsheet Excel. File XLAM disimpan dengan ekstensi .xlam. File XLAM adalah file berbasis XML yang mirip dengan format file XLSM dan XLSX dan disimpan dengan kompresi ZIP untuk mengurangi ukuran file secara keseluruhan.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi CSV ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV KE BMP" description="Gambar bitmap" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV KE DIF" description="Format Pertukaran Data" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV KE EMF" description="Format Metafile yang Ditingkatkan" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV KE GIF" description="Format Pertukaran Grafis" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV KE HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="CSV KE JPEG" description="Gambar JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV KE MHTML" description="Format Arsip Halaman Web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV KE ODS" description="File Spreadsheet OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="CSV KE PDF" description="Format Dokumen Portabel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV KE PNG" description="Grafik Jaringan Portabel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV KE TIFF" description="Format Gambar yang Ditandai" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV KE TSV" description="Nilai yang Dipisahkan Tab" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV KE XLS" description="Format Biner Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsb/" name="CSV KE XLSB" description="File Buku Kerja Excel Biner" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV KE XLSM" description="File Spreadsheet" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV KE XLSX" description="File Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV KE XLTM" description="Template Excel Macro-enabled" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV KE XLTX" description="Templat Excel Office OpenXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV KE XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}