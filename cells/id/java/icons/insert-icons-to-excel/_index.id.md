---
title: Masukkan SVG gambar/Ikon ke dalam Excel via Java
weight: 10
description: Sisipkan objek menggunakan Aspose.Cells' Java API tanpa software apapun seperti Microsoft atau Open Office, Adobe PDF, dll.
keywords: [Java Aspose.Cells., Java add SVG images/Icons into Excel., Java insert SVG images/Icons into Excel., Java create SVG images/Icons in Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Masukkan SVG gambar/Ikon ke dalam Excel via Java" h2="Masukkan SVG gambar/Ikon menggunakan Aspose.Cells\' API tanpa software apa pun seperti Microsoft atau Open Office, Adobe PDF, dll." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content %}}

Anda tidak ingin melihat gambar diregangkan dan dikompresi di perangkat apa pun?

Anda tidak ingin gambar menjadi buram saat diperbesar?

Anda tidak ingin gambar terdistorsi pada resolusi tinggi?

Mungkin SVG adalah pilihan yang bagus. Gambar SVG terlihat bagus pada tingkat zoom apa pun, dan tidak bergantung pada resolusi. Karena fidelitas gambar svg yang tinggi, gambar ini sangat populer di kalangan pengguna Excel.

Saat Anda menggunakan Excel, Anda mungkin mengalami masalah berikut ini:

+ File Excel target tidak dapat dimanipulasi secara manual secara langsung, dan diperlukan program untuk memprosesnya.
+ Masukkan sejumlah besar gambar svg ke dalam file Excel yang sama.
+ Masukkan gambar svg ke dalam sejumlah besar file Excel yang berbeda.

 Untuk mengatasi masalah ini, kami menyarankan Anda untuk menggunakan[Aspose.Cells](https://products.aspose.com/cells/)perpustakaan. Ini berisi banyak antarmuka umum untuk memproses file excel dan merupakan alat yang sangat berguna.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Cara Memasukkan Gambar/Ikon SVG ke File Excel Menggunakan Microsoft Excel" %}}

![](/cells/id/net/icons/insert-icons-to-excel/sample.png)

Microsoft Excel memberi kita tiga cara untuk menyisipkan svg:

+  **Masukkan gambar/Ikon lokal SVG**

Anda cukup menarik dan melepas file SVG ke lokasi tertentu di dokumen. Atau Anda dapat memilih jalur "*Sisipkan -> Gambar -> Perangkat Ini...*" dari pita.

+  **Masukkan gambar/Ikon preset SVG**

Microsoft Excel telah memberi kita gambar svg preset untuk kita pilih. Anda dapat membuka dialog pemilihan dengan memilih jalur "*Sisipkan -> Gambar -> Gambar Stok...*" dari pita. Sebagian besar file svg berada di bawah opsi "Ikon" di Gambar Stok.

+  **Masukkan SVG gambar/Ikon dari web**

Jika tidak ada cara di atas yang dapat memenuhi kebutuhan Anda, Anda juga dapat mencari hasil yang Anda inginkan dari Internet melalui Microsoft Excel. Anda dapat membuka dialog pemilihan dengan memilih "*Sisipkan -> Gambar -> Gambar Online...* " jalur dari pita.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Cara Memasukkan Gambar/Ikon SVG ke File Excel Menggunakan Menggunakan Java" %}}

 Untuk memasukkan gambar/Ikon SVG ke dalam file excel, kami akan menggunakan
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API yang merupakan platform API yang kaya fitur, kuat, dan mudah digunakan. Anda dapat mendownload versi terbarunya langsung dari
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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah memasukkan gambar/Ikon SVG ke file Excel via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+ Membuat Instansiasi objek Buku Kerja. (atau-> Muat file XLSX dengan path lengkap.)
+ Pilih Lembar Kerja melalui indeksnya.
 + Gunakan[tambahkan metode](https://reference.aspose.com/cells/java/com.aspose.cells/shapecollection/#addIcons-int-int-int-int-int-int-byte---byte---) untuk menyisipkan Info di lembar kerja yang dipilih
+ Simpan buku kerja dalam format XLSX.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java mendukung semua platform dan Sistem Operasi utama. Harap pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan versi terbaru Aspose.Cells for Java langsung dari Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Sisipkan SVG gambar/Ikon - Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "InsertIconsIntoWorksheet.java" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Cells for Java API" %}}

 Aspose.Cells API dapat digunakan untuk membuat, mengedit, mengonversi, dan merender format Excel Microsoft ke format berbeda. Selain itu, ini dapat digunakan untuk pembuatan bagan yang komprehensif, pelaporan yang dapat diskalakan, dan penghitungan yang andal dalam aplikasi perangkat lunak. Aspose.Cells adalah API yang berdiri sendiri dan tidak memerlukan perangkat lunak apa pun seperti Microsoft atau OpenOffice.


    {{% /blocks/products/pf/agp/content %}}

    


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
