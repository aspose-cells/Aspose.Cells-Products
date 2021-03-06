---
title: Konversi JSON ke EMF melalui Java 
weight: 2020
url: /id/java/conversion/json-to-emf/ 
description: Contoh Java kode konversi untuk format JSON ke file EMF. Pemrogram dapat menggunakan kode contoh ini untuk mengekspor spreadsheet Excel & OpenOffice ke EMF dalam Aplikasi berbasis Web atau Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi JSON ke EMF melalui Java" h2="Ekspor JSON ke format EMF melalui Java tanpa memerlukan alat atau pustaka tambahan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi JSON ke EMF Menggunakan Java" %}}

 Untuk merender JSON ke EMF, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi JSON ke EMF melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pengembang dapat dengan mudah mengonversi file JSON ke EMF hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Buat instance baru dari kelas Workbook1. Pilih default atau Lembar Kerja apa pun dari koleksi1. Muat data JSON dari file1. Buat instance JsonLayoutOptions & atur opsi1. Panggil metode JsonUtility.importData untuk mengimpor data JSON1. Buat & atur objek ImageOrPrintOptions untuk rendering EMF1. Buat SheetRender untuk rendering1. Panggil metode SheetRender.toImage untuk menyimpan hasil dalam format EMF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode sumber konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON ke EMF Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// baca file data JSON sebagai string
String jsonInput = new String(Files.readAllBytes(Paths.get("data.json")));

// buat objek Workbook kosong
Workbook workbook = new Workbook();
// akses lembar kerja kosong default
Worksheet worksheet = workbook.getWorksheets().get(0);

// atur JsonLayoutOptions untuk pemformatan
JsonLayoutOptions layoutOptions = new JsonLayoutOptions();
layoutOptions.setArrayAsTable(true);

// impor data JSON ke lembar kerja default mulai dari sel A1
JsonUtility.importData(jsonInput, worksheet.getCells(), 0, 0, layoutOptions);

// tentukan parameter untuk gambar yang dihasilkan
ImageOrPrintOptions renderingOptions = new ImageOrPrintOptions();
renderingOptions.setOnePagePerSheet(true);
renderingOptions.setImageType(ImageType.EMF);

// konversi lembar kerja ke gambar dalam format EMF
SheetRender renderer = new SheetRender(worksheet, renderingOptions);
renderer.toImage(0, "output.emf");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi JSON ke EMF" sectionDescription="[Mengonversi JSON ke EMF](https://products.aspose.app/cells/conversion/json-to-emf) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file JSON Anda, itu akan langsung dikonversi ke EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java Pustaka Manipulasi Spreadsheet" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mengirimkan data. File JSON disimpan dengan ekstensi .json. JSON membutuhkan lebih sedikit pemformatan dan merupakan alternatif yang baik untuk XML. JSON berasal dari JavaScript tetapi merupakan format data yang tidak bergantung pada bahasa. Pembuatan dan penguraian JSON didukung oleh banyak bahasa pemrograman modern. application/json adalah jenis media yang digunakan untuk JSON.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Enhanced metafile format (EMF) menyimpan gambar grafis perangkat-independen. Metafile EMF terdiri dari catatan panjang variabel dalam urutan kronologis yang dapat membuat gambar yang disimpan setelah diurai pada perangkat output apa pun. Catatan panjang variabel ini dapat berupa definisi objek tertutup, perintah untuk menggambar, dan properti grafik yang penting untuk membuat gambar secara akurat. Saat perangkat membuka metafile EMF menggunakan lingkungan grafisnya sendiri, proporsi, dimensi, warna, dan properti grafis lainnya dari gambar asli tetap sama terlepas dari platform perangkat pembuka.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi JSON ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xls/" name="JSON KE XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsx/" name="JSON KE XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsb/" name="JSON KE XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlsm/" name="JSON KE XLSM" description="File Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xlt/" name="JSON KE XLT" description="Templat Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xltx/" name="JSON KE XLTX" description="Templat Excel Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xltm/" name="JSON KE XLTM" description="Template Excel Macro-enabled" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-csv/" name="JSON KE CSV" description="Nilai Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-tsv/" name="JSON KE TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-txt/" name="JSON KE TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-html/" name="JSON KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-mhtml/" name="JSON KE MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-ods/" name="JSON KE ODS" description="File Spreadsheet OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-dif/" name="JSON KE DIF" description="Format Pertukaran Data" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-pdf/" name="JSON KE PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-xps/" name="JSON KE XPS" description="Spesifikasi Kertas XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-svg/" name="JSON KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-tiff/" name="JSON KE TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-png/" name="PNG JSON" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-bmp/" name="JSON KE BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-jpeg/" name="JSON KE JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-gif/" name="JSON KE GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-md/" name="JSON KE MD" description="Bahasa Penurunan Harga" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-docx/" name="JSON KE DOCX" description="Dokumen Office 2007+ Words" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/json-to-pdf/" name="JSON KE PDF" description="Format Dokumen Portabel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}