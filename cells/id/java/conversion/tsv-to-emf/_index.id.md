---
title: Konversikan TSV ke EMF melalui Java 
weight: 2530
url: /id/java/conversion/tsv-to-emf/ 
description: Contoh Java kode konversi untuk format TSV ke file EMF. Pemrogram dapat menggunakan kode contoh ini untuk mengekspor spreadsheet Excel & OpenOffice ke EMF dalam Aplikasi berbasis Web atau Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversikan TSV ke EMF melalui Java" h2="Konversi TSV ke EMF Java untuk mengonversi satu atau beberapa halaman ke EMF menggunakan pustaka Java Lokal." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi TSV ke EMF Menggunakan Java" %}}

 Untuk merender TSV ke EMF, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang merupakan platform konversi API for Java yang kaya fitur, canggih, dan mudah digunakan. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositori.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi TSV ke EMF melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pengembang dapat dengan mudah mengonversi file TSV ke EMF hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file TSV dengan instance Workbook1. Pilih default atau Lembar Kerja apa pun dari koleksi1. Buat & atur objek ImageOrPrintOptions1. Buat SheetRender dengan objek Worksheet & ImageOrPrintOptions1. Panggil metode SheetRender.toImage untuk menyimpan hasil dalam format EMF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode sumber konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV ke EMF Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// memuat file TSV yang akan dirender
Workbook workbook = new Workbook("sourceFile.tsv");
// mengakses Lembar Kerja default dari koleksi
Worksheet worksheet = workbook.getWorksheets().get(0);
// tentukan parameter untuk gambar yang dihasilkan
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.EMF);
// konversi lembar kerja ke gambar dalam format EMF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.emf");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi TSV ke EMF" sectionDescription="[Mengkonversi TSV ke EMF](https://products.aspose.app/cells/conversion/tsv-to-emf) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file TSV Anda, itu akan langsung dikonversi ke EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java Pustaka Manipulasi Spreadsheet" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Format file Tab-Separated Values (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Format file, mirip dengan CSV, digunakan untuk mengatur data secara terstruktur untuk mengimpor dan mengekspor antara aplikasi yang berbeda. Format ini terutama digunakan untuk impor/ekspor data dan pertukaran dalam aplikasi dan database Spreadsheet. Setiap catatan dalam file TSV terkandung dalam satu baris file teks di mana setiap nilai bidang dipisahkan oleh karakter tab. Jenis media untuk format file TSV adalah teks/tab-separated-values.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Enhanced metafile format (EMF) menyimpan gambar grafis perangkat-independen. Metafile EMF terdiri dari catatan panjang variabel dalam urutan kronologis yang dapat membuat gambar yang disimpan setelah diurai pada perangkat output apa pun. Catatan panjang variabel ini dapat berupa definisi objek tertutup, perintah untuk menggambar, dan properti grafik yang penting untuk membuat gambar secara akurat. Saat perangkat membuka metafile EMF menggunakan lingkungan grafisnya sendiri, proporsi, dimensi, warna, dan properti grafis lainnya dari gambar asli tetap sama terlepas dari platform perangkat pembuka.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi TSV ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-bmp/" name="TSV KE BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-csv/" name="TSV KE CSV" description="Nilai Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-dif/" name="TSV KE DIF" description="Format Pertukaran Data" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-gif/" name="TSV KE GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-html/" name="TSV KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-jpeg/" name="TSV KE JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-mhtml/" name="TSV KE MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-ods/" name="TSV KE ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-pdf/" name="TSV KE PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-png/" name="TSV KE PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-svg/" name="TSV KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-tiff/" name="TSV KE TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-txt/" name="TSV KE TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlm/" name="TSV KE XLM" description="File Makro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xls/" name="TSV KE XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsb/" name="TSV KE XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsx/" name="TSV KE XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlt/" name="TSV KE XLT" description="Templat Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltm/" name="TSV KE XLTM" description="Template Excel Macro-enabled" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltx/" name="TSV KE XLTX" description="Templat Excel Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xps/" name="TSV KE XPS" description="Spesifikasi Kertas XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-json/" name="TSV KE JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}