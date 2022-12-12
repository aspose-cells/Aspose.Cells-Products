---
title: Kelola Metadata File Excel melalui Java

description: Lihat, tambah, edit, hapus, atau ekstrak metadata file Excel hanya dengan beberapa baris Java kode
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Metadata File Microsoft<sup>&reg;</sup> Excel melalui Java" h2="Lihat, tambah, perbarui, hapus, atau ekstrak properti file Excel khusus dan bawaan menggunakan Java API sisi server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) mendukung pengelolaan properti bawaan (ditentukan sistem) seperti judul, nama penulis, statistik dokumen, dll. serta properti khusus (ditentukan pengguna) dalam bentuk pasangan nama/nilai. Ada [Kelas buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) untuk memuat file, dan [Koleksi Lembar Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) berurusan dengan kumpulan lembar kerja serta [kelas lembar kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) untuk mewakili lembar kerja tunggal. Untuk mengakses properti bawaan dan kustom, BuiltInDocumentProperties, CustomDocumentProperties membuat prosesnya sederhana untuk manajemen metadata. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengelola Properti yang Ditetapkan Sistem" %}}

Untuk mengelola properti bawaan, API menyediakan [BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), dan pemrogram dapat dengan mudah mengakses properti bawaan dan memperbarui nilainya. Bergantung pada persyaratan aplikasi, pengembang dapat menggunakan indeks atau nama properti dari [KoleksiProperti Dokumen](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Mengelola Properti yang Ditetapkan Sistem" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Tambah dan Hapus Metadata Buatan Kustom" %}}

Untuk menangani properti khusus, API menyediakan [Properti Dokumen Kustom](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), dan pengembang dapat dengan mudah mengakses properti yang ada serta menambahkan properti baru menggunakan [tambahkan metode](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) dari [KoleksiProperti Dokumen Kustom](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class menambahkan properti dan mengembalikan referensi untuk properti baru sebagai [Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) obyek. Kelas DocumentProperty digunakan untuk mengambil nama, nilai, dan jenis properti dokumen sebagai [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Properti Dokumen. Nilai](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) yang mengembalikan salah satu [Jenis properti](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) nilai enumerasi. 
 
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menghapus Properti Kustom di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
