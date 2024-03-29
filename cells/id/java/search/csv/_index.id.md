---
title:  Cari dokumen CSV tanpa membuka via Java
weight: 390
description: Contoh kode Java untuk mencari kata dengan pola pada file CSV pada Runtime Environment Java untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
keywords: [Java Aspose.Cells., Java search words with pattern in csv file., Java find words with pattern in csv file., Java search string with pattern in csv file., Java find words with pattern in csv file., Java search words in csv file., Java find words in csv file., Java search string in csv file., Java find string in csv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cari CSV Format di Java" h2="Pencarian dokumen CSV asli dan berkinerja tinggi menggunakan API sisi server Aspose.Cells for Java, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Cara Mencari File CSV Menggunakan Java" %}}

 Untuk mencari file CSV, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang merupakan platform Pencarian API yang kaya fitur, kuat, dan mudah digunakan. Anda dapat mendownload versi terbarunya langsung dari
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah Mencari File CSV di Java" %}}

{{% blocks/products/pf/agp/text %}}

 Pencarian dokumen dasar menggunakan API Aspose.Cells dapat dilakukan hanya dengan beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

+ Muat file CSV dengan membuat instance objek Buku Kerja.
+ Akses lembar kerja pertama di file CSV.
+ Temukan sel yang berisi rumus yang ditentukan.
+ Buat instance FindOptions.
+ Temukan sel yang berisi nilai string
Cetak sel yang ditemukan setelah hasil pencarian

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java mendukung semua platform dan Sistem Operasi utama. Harap pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
-  Dapatkan versi terbaru Aspose.Cells for Java langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cari CSV File - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.csv");

// Accessing the first worksheet in the CSV file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for Java API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online CSV Cari Demo Langsung" sectionDescription=" Cari teks, kata, frasa dalam dokumen CSV sekarang juga dengan mengunjungi kami[Situs web Demo Langsung](https://products.aspose.app/cells/search). Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Cukup unggah file CSV Anda." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Hasil pencarian langsung muncul." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
File dengan ekstensi CSV (Nilai Dipisahkan Koma) mewakili file teks biasa yang berisi catatan data dengan nilai dipisahkan koma. Setiap baris dalam file CSV merupakan record baru dari kumpulan record yang terdapat dalam file tersebut. File tersebut dihasilkan ketika transfer data dimaksudkan dari satu sistem penyimpanan ke sistem penyimpanan lainnya. Karena semua aplikasi dapat mengenali catatan yang dipisahkan dengan koma, impor file data tersebut ke database dilakukan dengan sangat mudah. Hampir semua aplikasi spreadsheet seperti Microsoft Excel atau OpenOffice Calc dapat mengimpor CSV tanpa banyak usaha. Data yang diimpor dari file tersebut disusun dalam sel spreadsheet untuk direpresentasikan kepada pengguna.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Dokumen Pencarian yang Didukung Lainnya" subTitle="Dengan menggunakan Java, seseorang juga dapat mencari file lain termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Berkas Lembar Bentang" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
