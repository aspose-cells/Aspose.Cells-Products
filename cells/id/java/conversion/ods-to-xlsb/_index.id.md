---
title: Konversikan ODS ke XLSB melalui Java 
weight: 5170
url: /id/java/conversion/ods-to-xlsb/ 
description: Contoh Java kode konversi untuk format ODS ke file XLSB. Pemrogram dapat menggunakan kode contoh ini untuk mengekspor spreadsheet Excel & OpenOffice ke XLSB dalam Aplikasi berbasis Java Web atau Desktop apa pun.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversikan ODS ke XLSB melalui Java" h2="ODS ke XLSB Java konversi untuk mengonversi satu atau beberapa halaman ke XLSB menggunakan pustaka Java Lokal." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi ODS ke XLSB Menggunakan Java" %}}

 Untuk merender ODS ke XLSB, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Mengkonversi ODS ke XLSB melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pengembang dapat dengan mudah mengonversi file ODS ke XLSB hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file ODS dengan instance kelas Workbook1. Panggil Workbook.save metode1. Lewati jalur keluaran dengan ekstensi XLSB & SaveFormat sebagai parameter1. Periksa jalur yang ditentukan untuk file XLSB yang dihasilkan
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode sumber konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS ke XLSB Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// memuat file ODS dalam instance Workbook
Workbook book = new Workbook("template.ods");
// simpan ODS sebagai XLSB
book.save("output.xlsb", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Konversi ODS ke XLSB" sectionDescription="[Mengkonversi ODS ke XLSB](https://products.aspose.app/cells/conversion/ods-to-xlsb) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file ODS Anda, itu akan langsung dikonversi ke XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java Pustaka Manipulasi Spreadsheet" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

File dengan ekstensi ODS adalah singkatan dari format OpenDocument Spreadsheet Document yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF ke dalam baris dan kolom. Ini adalah format berbasis XML dan merupakan salah satu dari beberapa subtipe dalam keluarga Open Document Formats (ODF). Format ditentukan sebagai bagian dari spesifikasi ODF 1.2 yang diterbitkan dan dikelola oleh OASIS. Sejumlah aplikasi di Windows serta sistem operasi lain dapat membuka file ODS untuk diedit dan dimanipulasi termasuk Microsoft Excel, NeoOffice dan LibreOffice. File ODS juga dapat dikonversi ke format spreadsheet lain seperti XLS, XLSX, dan lainnya dengan aplikasi yang berbeda.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Konten dapat menyertakan tabel angka, teks, atau angka dan teks yang tidak terstruktur atau semi-terstruktur, rumus, koneksi data eksternal, bagan, dan gambar. Tidak seperti XLSX (yang didasarkan pada format file Open XML), XLSB mewakili file buku kerja Excel biner. File XLSB dapat dibaca dan ditulis lebih cepat yang membuatnya berguna untuk bekerja dengan file besar. XLSB jarang digunakan untuk menyimpan buku kerja karena XLSX (dan sebelumnya XLS) adalah format file pilihan pengguna yang paling umum untuk menyimpan buku kerja. Itu dapat dibuka oleh Microsoft Office 2007 dan di atasnya.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi ODS ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-bmp/" name="ODS KE BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-csv/" name="OD KE CSV" description="Nilai Dipisahkan Koma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-dif/" name="OD UNTUK DIF" description="Format Pertukaran Data" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-emf/" name="OD KE EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-gif/" name="OD KE GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-html/" name="OD KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-jpeg/" name="ODS KE JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-mhtml/" name="OD KE MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-pdf/" name="OD KE PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-png/" name="OD KE PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-svg/" name="OD KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tiff/" name="OD KE TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tsv/" name="ODS KE TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-txt/" name="OD KE TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlm/" name="OD KE XLM" description="File Makro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xls/" name="OD KE XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlsx/" name="ODS KE XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlt/" name="ODS KE XLT" description="Templat Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltm/" name="ODS KE XLTM" description="Template Excel Macro-enabled" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltx/" name="ODS KE XLTX" description="Templat Excel Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xps/" name="OD KE XPS" description="Spesifikasi Kertas XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-json/" name="ODS UNTUK JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}