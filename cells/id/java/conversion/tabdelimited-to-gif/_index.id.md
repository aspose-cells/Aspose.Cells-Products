---
title: Konversi TABDELIMITED ke GIF melalui Java 
url: /id/java/conversion/tabdelimited-to-gif/ 
description: Contoh Java kode konversi untuk format TABDELIMITED ke file GIF. Pemrogram dapat menggunakan kode contoh ini untuk mengekspor spreadsheet Excel & OpenOffice ke GIF dalam Aplikasi berbasis Web atau Desktop Java apa pun.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi TABDELIMITED ke GIF melalui Java" h2="TABDELIMITED ke GIF Java konversi untuk mengonversi satu atau beberapa halaman ke GIF menggunakan perpustakaan Java Lokal." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi TABDELIMITED ke GIF Menggunakan Java" %}}

 Untuk merender TABDELIMITED ke GIF, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Mengkonversi TABDELIMITED ke GIF melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pengembang dapat dengan mudah mengonversi file TABDELIMITED ke GIF hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file TABDELIMITED dengan instance Workbook1. Pilih default atau Lembar Kerja apa pun dari koleksi1. Buat & atur objek ImageOrPrintOptions1. Buat SheetRender dengan objek Worksheet & ImageOrPrintOptions1. Panggil metode SheetRender.toImage untuk menyimpan hasil dalam format GIF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode sumber konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED ke GIF Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// muat file TABDELIMITED yang akan dirender
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// mengakses Lembar Kerja default dari koleksi
Worksheet worksheet = workbook.getWorksheets().get(0);
// tentukan parameter untuk gambar yang dihasilkan
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// konversi lembar kerja ke gambar dalam format GIF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED ke Demo Langsung Konversi GIF" sectionDescription="[Konversi TABDELIMITED ke GIF](https://products.aspose.app/cells/conversion/tabdelimited-to-gif) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file TABDELIMITED Anda, itu akan langsung dikonversi ke GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java Pustaka Manipulasi Spreadsheet" %}}

 Excel API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API mandiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

GIF atau Graphical Interchange Format adalah jenis gambar yang sangat terkompresi. Dimiliki oleh Unisys, GIF menggunakan algoritma kompresi LZW yang tidak menurunkan kualitas gambar. Untuk setiap gambar, GIF biasanya mengizinkan hingga 8 bit per piksel dan hingga 256 warna diizinkan di seluruh gambar. Berbeda dengan gambar JPEG, yang mampu menampilkan hingga 16 juta warna dan terbilang menyentuh batas mata manusia. Kembali ketika internet muncul, GIF tetap menjadi pilihan terbaik karena membutuhkan bandwidth rendah dan kompatibel untuk grafik yang menggunakan area warna solid. GIF animasi menggabungkan banyak gambar atau bingkai ke dalam satu file dan menampilkannya secara berurutan untuk menghasilkan klip animasi atau video pendek. Batasan warna hingga 256 untuk setiap bingkai dan kemungkinan paling tidak cocok untuk mereproduksi gambar dan foto lain dengan gradien warna.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}