---
title: Buka kunci dokumen XLSB melalui C++ 
weight: 7420
url: /id/cpp/unlock/xlsb/ 
description: C++ kode contoh untuk membuka kunci file XLSB yang dilindungi sandi di C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Buka kunci File XLSB melalui C++" h2="Hapus perlindungan dari spreadsheet Excel termasuk file XLSB menggunakan C++ Library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Menghapus Perlindungan File XLSB Menggunakan C++" %}}

 Untuk membuka kunci file XLSB, kami akan menggunakan
 [Aspose.Cells untuk C++](https://products.aspose.com/cells/cpp) 
 API yang kaya fitur, kuat, dan mudah digunakan perlindungan dokumen API untuk C++ platform. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 manajer paket, cari
 ***.Cpp** 
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Buka kunci XLSB melalui C++" %}}

{{% blocks/products/pf/agp/text %}}

 Anda membutuhkan
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 direferensikan dalam proyek Anda untuk menjalankan alur kerja berikut.

{{% /blocks/products/pf/agp/text %}}

1. Muat file terkunci XLSB menggunakan CreateIWorkbook.1. Panggil fungsi Unprotect() untuk membuka kunci.1. Setel kata sandi ke NULL menggunakan SetPassword.1. Simpan file XLSB di lokasi yang ditentukan.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells untuk C++ dukungan di semua platform utama dan Sistem Operasi. Harap pastikan bahwa Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Memerintah" offSpacer="" %}}

```cs

// Jalur direktori sumber.
StringPtr srcDir = new String("SourceDirectory\\");

// Jalur direktori keluaran.
StringPtr outDir = new String("OutputDirectory\\");

// Muat file XLSB
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sampleExcelFileProtected.xlsb")));

// Buka proteksi buku kerja
workbook->Unprotect(new String("12345"));

// Setel kata sandi ke nol
workbook->GetISettings()->SetPassword(NULL);

// Simpan file XLSB
workbook->Save(outDir->StringAppend(new String("sampleExcelFileUnprotected_out.xlsb")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells untuk C++ API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Membuka XLSB" sectionDescription="Periksa demo langsung kami untuk [buka kunci file XLSB](https://products.aspose.app/cells/unlock/xlsb) dengan manfaat sebagai berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSB dan tekan tombol \"Buka Kunci\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLSB yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Konten dapat menyertakan tabel angka, teks, atau angka dan teks yang tidak terstruktur atau semi-terstruktur, rumus, koneksi data eksternal, bagan, dan gambar. Tidak seperti XLSX (yang didasarkan pada format file Open XML), XLSB mewakili file buku kerja Excel biner. File XLSB dapat dibaca dan ditulis lebih cepat yang membuatnya berguna untuk bekerja dengan file besar. XLSB jarang digunakan untuk menyimpan buku kerja karena XLSX (dan sebelumnya XLS) adalah format file pilihan pengguna yang paling umum untuk menyimpan buku kerja. Itu dapat dibuka oleh Microsoft Office 2007 dan di atasnya.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Membuka Kunci Lainnya yang Didukung" subTitle="Dengan menggunakan C++, seseorang dapat dengan mudah menghapus perlindungan / pembukaan kunci dari berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="File Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}