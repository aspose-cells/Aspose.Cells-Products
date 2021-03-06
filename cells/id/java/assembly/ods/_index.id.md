---
title: Buat Laporan dalam File ODS melalui Java 
weight: 2440
url: /id/java/assembly/ods/ 
description: Java kode contoh untuk membuat laporan format ODS di Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pembuatan Laporan Massal dalam Format ODS melalui Java" h2="Hasilkan laporan dalam format ODS menggunakan sumber data & template." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Membuat Laporan ODS Menggunakan Java" %}}

 Untuk membuat laporan file ODS, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang merupakan platform perakitan API for Java yang kaya fitur, kuat, dan mudah digunakan. Anda dapat mengunduh versi terbarunya langsung dari
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Membuat Laporan ODS melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Buat instance kelas WorkbookDesigner1. Tambahkan objek Datasouce dalam ArrayList1. Atur sumber data dan Proses untuk objek WorkbookDesigner1. Simpan hasil dalam format ODS melalui metode Worbook.save
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java mendukung semua platform utama dan Sistem Operasi. Harap pastikan bahwa Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Membuat Laporan Excel dalam Format ODS - C#" offSpacer="" %}}

```cs
//Buat desainer buku kerja
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Buat objek Orang dengan foto
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Setel sumber data dan proses tag penanda pintar
designer.setDataSource("Person", persons);
designer.process();

//Simpan buku kerja
workbook.save(dataDir + "output.ods", SaveFormat.ODS);
	
System.out.println("File saved");
    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for Java API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Microsoft Excel ke format yang berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan perhitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Merakit ODS" sectionDescription="Periksa demo langsung kami untuk [buat file ODS](https://products.aspose.app/cells/assembly/ods) dengan manfaat sebagai berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file ODS dan tekan tombol \"Assemble\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file ODS yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
File dengan ekstensi ODS adalah singkatan dari format OpenDocument Spreadsheet Document yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF ke dalam baris dan kolom. Ini adalah format berbasis XML dan merupakan salah satu dari beberapa subtipe dalam keluarga Open Document Formats (ODF). Format ditentukan sebagai bagian dari spesifikasi ODF 1.2 yang diterbitkan dan dikelola oleh OASIS. Sejumlah aplikasi di Windows serta sistem operasi lain dapat membuka file ODS untuk diedit dan dimanipulasi termasuk Microsoft Excel, NeoOffice dan LibreOffice. File ODS juga dapat dikonversi ke format spreadsheet lain seperti XLS, XLSX, dan lainnya dengan aplikasi yang berbeda.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Pembuatan Laporan Lainnya yang Didukung" subTitle="Dengan menggunakan Java, seseorang dapat dengan mudah membuat laporan dari berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="File Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}