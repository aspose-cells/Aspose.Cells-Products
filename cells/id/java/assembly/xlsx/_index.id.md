---
title:  Hasilkan Laporan di File XLSX via Java
weight: 7710
description: Contoh kode Java untuk membuat laporan berformat XLSX pada Runtime Environment Java untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
keywords: [Java Aspose.Cells., Java Create XLSX Reports Based on Predesigned Excel Template., Java Generate XLSX Reports Based on Predesigned Excel Template., Java Create XLSX Reports Based on Excel Template., Java Generate XLSX Reports Based on Excel Template., Java Create xlsx files Based on Excel Template., Java Generate xlsx files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pembuatan Laporan Massal dalam Format XLSX via Java" h2="Hasilkan laporan dalam format XLSX menggunakan sumber data & templat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Menghasilkan Laporan XLSX Menggunakan Java" %}}

 Untuk membuat laporan file XLSX, kami akan menggunakan
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-Langkah Menghasilkan Laporan XLSX via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Buat instance kelas WorkbookDesigner
1. Tambahkan objek Datasouce di ArrayList
1.  Tetapkan sumber data dan Proses untuk objek WorkbookDesigner
1.  Simpan hasil dalam format XLSX melalui metode Worbook.save

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java mendukung semua platform dan Sistem Operasi utama. Harap pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Hasilkan Laporan Excel dalam Format XLSX - Java" offSpacer="" %}}

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
workbook.save(dataDir + "output.xlsx", SaveFormat.XLSX);
	
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

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplikasi Gratis untuk Merakit XLSX" sectionDescription=" Periksa demo langsung kami[buat file XLSX](https://products.aspose.app/cells/assembly/xlsx) dengan manfaat berikut." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis atau mengkompilasi kode" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file XLSX dan tekan tombol \"Rakit\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Unduh file XLSX yang dihasilkan dari tautan" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX adalah format terkenal untuk dokumen Excel Microsoft yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Berdasarkan struktur yang diatur menurut Konvensi Pengemasan Terbuka sebagaimana diuraikan dalam Bagian 2 standar OOXML ECMA-376, format baru adalah paket zip yang berisi sejumlah file XML. Struktur dan file yang mendasarinya dapat diperiksa hanya dengan membuka ritsleting file .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Pembuatan Laporan Lainnya yang Didukung" subTitle="Dengan menggunakan Java, seseorang dapat dengan mudah membuat laporan dalam berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
