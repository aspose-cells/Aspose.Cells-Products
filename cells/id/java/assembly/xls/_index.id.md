---
title:  Hasilkan Laporan di File XLS via Java
weight: 1090
description: Contoh kode Java untuk membuat laporan berformat XLS pada Runtime Environment Java untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
keywords: [Java Aspose.Cells., Java Create XLS Reports Based on Predesigned Excel Template., Java Generate XLS Reports Based on Predesigned Excel Template., Java Create XLS Reports Based on Excel Template., Java Generate XLS Reports Based on Excel Template., Java Create XLS files Based on Excel Template., Java Generate XLS files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pembuatan Laporan Massal dalam Format XLS via Java" h2="Hasilkan laporan dalam format XLS menggunakan sumber data & templat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Menghasilkan Laporan XLS Menggunakan Java" %}}

 Untuk membuat laporan file XLS, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang merupakan platform perakitan API for Java yang kaya fitur, kuat, dan mudah digunakan. Anda dapat mendownload versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-Langkah Menghasilkan Laporan XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Buat instance kelas WorkbookDesigner
1. Tambahkan objek Datasouce di ArrayList
1.  Tetapkan sumber data dan Proses untuk objek WorkbookDesigner
1.  Simpan hasil dalam format XLS melalui metode Worbook.save

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java mendukung semua platform dan Sistem Operasi utama. Harap pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Hasilkan Laporan Excel dalam Format XLS - Java" offSpacer="" %}}

```java
//Create a workbook designer
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Create Persons objects with photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Set the data source and process smart marker tags
designer.setDataSource("Person", persons);
designer.process();

//Save the workbook
workbook.save(dataDir + "output.xls", SaveFormat.XLS);
	
System.out.println("File saved");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for Java API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Merakit XLS" sectionDescription=" Periksa demo langsung kami[buat file XLS](https://products.aspose.app/cells/assembly/xls) dengan manfaat berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLS dan tekan tombol \"Rakit\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLS yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat dengan Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. File yang disimpan oleh Excel dikenal sebagai Workbook dimana setiap workbook dapat memiliki satu atau lebih lembar kerja. Data disimpan dan ditampilkan kepada pengguna dalam format tabel di lembar kerja dan dapat mencakup nilai numerik, data teks, rumus, koneksi data eksternal, gambar, dan bagan. Aplikasi seperti Microsoft Excel memungkinkan Anda mengekspor data buku kerja ke beberapa format berbeda termasuk PDF, CSV, XLSX, TXT, HTML, XPS, dan beberapa lainnya. Format file XLS diganti dengan format yang lebih terbuka dan terstruktur, XLSX, dengan dirilisnya Microsoft Excel 2007. Versi terbaru masih memberikan dukungan untuk membuat dan membaca file XLS, meskipun XLSX adalah pilihan pertama untuk digunakan sekarang.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Pembuatan Laporan Lainnya yang Didukung" subTitle="Dengan menggunakan Java, seseorang dapat dengan mudah membuat laporan dalam berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="Berkas OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
