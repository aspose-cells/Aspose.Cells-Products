---
title: Kelola Metadata File Excel via Java
description: Lihat, tambah, edit, hapus, atau ekstrak metadata file Excel hanya dengan beberapa baris kode Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata File Excel via Java" h2="Lihat, tambah, perbarui, hapus, atau ekstrak properti file Excel kustom dan bawaan menggunakan API Java sisi server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/id/java/) mendukung pengelolaan properti bawaan (ditentukan sistem) seperti judul, nama penulis, statistik dokumen, dll. Serta properti kustom (ditentukan pengguna) dalam bentuk pasangan nama/nilai. Ada[Kelas buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) untuk memuat file, dan[Koleksi Lembar Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) berkaitan dengan koleksi lembar kerja serta[Kelas lembar kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) untuk mewakili lembar kerja tunggal. Untuk mengakses properti bawaan dan kustom, BuiltInDocumentProperties, CustomDocumentProperties mempermudah proses pengelolaan metadata.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengelola Properti yang Ditentukan Sistem" %}}

 Untuk mengelola properti bawaan, API menyediakan[Properti Dokumen Bawaan](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) , dan pemrogram dapat dengan mudah mengakses properti bawaan dan memperbarui nilainya. Bergantung pada persyaratan aplikasi, pengembang dapat menggunakan indeks atau nama properti dari[KoleksiProperti Dokumen](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Mengelola Properti yang Ditentukan Sistem" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Tambah dan Hapus Metadata yang Ditentukan Khusus" %}}

Untuk menangani properti khusus, API menyediakan[Properti Dokumen Khusus](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , dan pengembang dapat dengan mudah mengakses properti yang ada serta menambahkan properti baru menggunakan[menambahkan metode](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) dari[Pengumpulan Properti Dokumen Kustom](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class menambahkan properti dan mengembalikan referensi untuk properti baru sebagai[Properti.DokumenProperti](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) obyek. Kelas DocumentProperty digunakan untuk mengambil nama, nilai, dan jenis properti dokumen sebagai[PropertiDokumen.Nama](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Properti Dokumen.Nilai](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [Properti Dokumen.Tipe](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) yang mengembalikan salah satu[Jenis properti](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) nilai pencacahan.
 
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menghapus Properti Kustom di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
