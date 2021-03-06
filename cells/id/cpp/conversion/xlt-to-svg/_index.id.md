---
title: Konversi XLT ke SVG melalui C++ aplikasi 
url: /id/cpp/conversion/xlt-to-svg/ 
description: Contoh C++ kode konversi untuk dokumen XLT ke format SVG. Pemrogram dapat menggunakan kode sumber ini untuk konversi batch XLT ke SVG dalam C++ Aplikasi apa pun.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversikan XLT ke SVG melalui C++" h2="Konversi XLT ke SVG performa tinggi menggunakan C++ library tanpa memerlukan instalasi Microsoft Excel, OpenOffice, atau Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi XLT ke SVG Menggunakan C++" %}}

 Untuk mengonversi XLT ke SVG, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi XLT ke SVG melalui C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ pengembang dapat dengan mudah mengonversi file XLT ke SVG hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file XLT menggunakan Factory::CreateIWorkbook.1. Pilih lembar kerja pertama.1. Setel opsi (SVG).1. Iterasi melalui setiap halaman lembar dan render.1. Buka file SVG di program yang kompatibel.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan C++ kode contoh konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit, dan Linux 64 bit.- Aspose.Cells untuk C++ DLL yang dirujuk dalam proyek Anda.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT ke SVG C++ Kode Sumber Konversi" offSpacer="" %}}

```cs
// Jalur direktori keluaran.
StringPtr outDir = new String("OutputDirectoryPath");

// Muat XLT-nya.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlt");

// Akses lembar kerja pertama.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Buat objek opsi gambar atau cetak.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Tentukan format gambar.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetSvg());

// Tentukan resolusi horizontal dan vertikal
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render lembar sesuai dengan gambar atau opsi cetak yang ditentukan.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Dapatkan jumlah halaman.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Buat objek pembuat string untuk rangkaian string.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render setiap halaman ke gambar svg satu per satu.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageSVG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".svg"));

	// Dapatkan jalur gambar keluaran.
	StringPtr outputSVG = sb->ToString();

	// Konversi lembar kerja ke gambar svg.
	sr->ToImage(i, outputSVG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi XLT ke SVG" sectionDescription="[Mengonversi XLT ke SVG](https://products.aspose.app/cells/conversion/xlt-to-svg) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLT Anda, itu akan langsung dikonversi ke SVG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="C++ Pustaka Manipulasi File Excel" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

File dengan ekstensi .XLT adalah file template yang dibuat dengan Microsoft Excel yang merupakan aplikasi spreadsheet yang merupakan bagian dari suite Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membukanya. Versi terbaru Excel masih mampu membuka file template format lama ini. File templat semacam itu digunakan untuk membuat file Excel baru dengan cepat dengan data dan pengaturan default seperti pemformatan halaman, ukuran font, margin, bagan, dll yang dapat disimpan lebih lanjut sebagai file .XLS baru.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

File SVG adalah File Grafik Vektor Scalable yang menggunakan format teks berbasis XML untuk menggambarkan tampilan gambar. Kata Scalable mengacu pada fakta bahwa SVG dapat diskalakan ke berbagai ukuran tanpa kehilangan kualitas apa pun. Deskripsi berbasis teks dari file tersebut membuat mereka independen dari resolusi. Ini adalah salah satu format yang paling banyak digunakan untuk membangun situs web dan mencetak grafik untuk mencapai skalabilitas. Format tersebut hanya dapat digunakan untuk grafik dua dimensi sekalipun. File SVG dapat dilihat/dibuka di hampir semua browser modern termasuk Chrome, Internet Explorer, Firefox, dan Safari.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}