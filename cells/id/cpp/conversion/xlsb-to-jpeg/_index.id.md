---
title: Konversi XLSB ke JPEG melalui C++ aplikasi 
weight: 6990
url: /id/cpp/conversion/xlsb-to-jpeg/ 
description: Contoh C++ kode konversi untuk dokumen XLSB ke format JPEG. Pemrogram dapat menggunakan kode sumber ini untuk konversi batch XLSB ke JPEG dalam C++ Aplikasi apa pun.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversikan XLSB ke JPEG melalui C++" h2="Konversi XLSB ke JPEG performa tinggi menggunakan C++ library tanpa memerlukan instalasi Microsoft Excel, OpenOffice, atau Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi XLSB ke JPEG Menggunakan C++" %}}

 Untuk mengonversi XLSB ke JPEG, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Mengonversi XLSB ke JPEG melalui C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ pengembang dapat dengan mudah mengonversi file XLSB ke JPEG hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file XLSB menggunakan Factory::CreateIWorkbook.1. Pilih lembar kerja pertama.1. Setel opsi (JPEG).1. Iterasi melalui setiap halaman lembar dan render.1. Buka file JPEG di program yang kompatibel.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan C++ kode contoh konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB ke JPEG C++ Kode Sumber Konversi" offSpacer="" %}}

```cs
// Jalur direktori keluaran.
StringPtr outDir = new String("OutputDirectoryPath");

// Muat XLSB.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlsb");

// Akses lembar kerja pertama.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Buat objek opsi gambar atau cetak.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Tentukan format gambar.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Tentukan resolusi horizontal dan vertikal
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render lembar sesuai dengan gambar atau opsi cetak yang ditentukan.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Dapatkan jumlah halaman.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Buat objek pembuat string untuk rangkaian string.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render setiap halaman ke gambar jpeg satu per satu.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// Dapatkan jalur gambar keluaran.
	StringPtr outputJPEG = sb->ToString();

	// Konversi lembar kerja ke gambar jpeg.
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi XLSB ke JPEG" sectionDescription="[Konversi XLSB ke JPEG](https://products.aspose.app/cells/conversion/xlsb-to-jpeg) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSB Anda, itu akan langsung dikonversi ke JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="C++ Pustaka Manipulasi File Excel" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Konten dapat menyertakan tabel angka, teks, atau angka dan teks yang tidak terstruktur atau semi-terstruktur, rumus, koneksi data eksternal, bagan, dan gambar. Tidak seperti XLSX (yang didasarkan pada format file Open XML), XLSB mewakili file buku kerja Excel biner. File XLSB dapat dibaca dan ditulis lebih cepat yang membuatnya berguna untuk bekerja dengan file besar. XLSB jarang digunakan untuk menyimpan buku kerja karena XLSX (dan sebelumnya XLS) adalah format file pilihan pengguna yang paling umum untuk menyimpan buku kerja. Itu dapat dibuka oleh Microsoft Office 2007 dan di atasnya.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar keluaran, sebagai hasil kompresi, merupakan pertukaran antara ukuran penyimpanan dan kualitas gambar. Pengguna dapat menyesuaikan tingkat kompresi untuk mencapai tingkat kualitas yang diinginkan sekaligus mengurangi ukuran penyimpanan. Kualitas gambar tidak terlalu terpengaruh jika kompresi 10:1 diterapkan pada gambar. Semakin tinggi nilai kompresi, semakin tinggi penurunan kualitas gambar. Format file gambar JPEG distandarisasi oleh Joint Photographic Experts Group dan, karenanya, dinamai JPEG. Format ini telah menjadi pilihan untuk menyimpan dan mentransmisikan gambar fotografi di web. Hampir semua Sistem Operasi sekarang memiliki viewer yang mendukung visualisasi gambar JPEG, yang sering juga disimpan dengan ekstensi JPG. Bahkan browser web mendukung visualisasi gambar JPEG.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi XLSB ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-bmp/" name="XLSB KE BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-csv/" name="XLSB KE CSV" description="Nilai Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-dif/" name="XLSB KE DIF" description="Format Pertukaran Data" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-emf/" name="XLSB KE EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-gif/" name="XLSB KE GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-html/" name="XLSB KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-mhtml/" name="XLSB KE MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-ods/" name="XLSB KE ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-pdf/" name="XLSB KE PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-png/" name="XLSB KE PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-svg/" name="XLSB KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-tiff/" name="XLSB KE TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-tsv/" name="XLSB KE TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xls/" name="XLSB KE XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xlsm/" name="XLSB KE XLSM" description="File Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xlsx/" name="XLSB KE XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xltm/" name="XLSB KE XLTM" description="Template Excel Macro-enabled" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xltx/" name="XLSB KE XLTX" description="Templat Excel Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsb-to-xps/" name="XLSB KE XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}