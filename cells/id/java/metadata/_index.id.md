---
title: Kelola Metadata File Excel via Java
description: Lihat, tambah, edit, hapus atau ekstrak metadata file Excel hanya dengan beberapa baris kode Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata File Excel via Java" h2="Lihat, tambah, perbarui, hapus, atau ekstrak properti file Excel kustom dan bawaan menggunakan API sisi server Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Unggul API](/cells/id/java/) mendukung pengelolaan properti bawaan (ditentukan sistem) seperti judul, nama penulis, statistik dokumen, dll serta properti khusus (ditentukan pengguna) dalam bentuk pasangan nama/nilai. Ada[Kelas buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) untuk memuat file, dan[Koleksi Lembar Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) berkaitan dengan pengumpulan lembar kerja serta[Kelas lembar kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) untuk mewakili lembar kerja tunggal. Untuk mengakses properti bawaan dan khusus, BuiltInDocumentProperties, CustomDocumentProperties membuat proses manajemen metadata menjadi sederhana.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengelola Properti Buatan Sistem" %}}

 Untuk mengelola properti bawaan, API menyediakan[Properti BuiltInDocument](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) dan pemrogram dapat dengan mudah mengakses properti bawaan dan memperbarui nilainya. Tergantung pada kebutuhan aplikasi, pengembang dapat menggunakan indeks atau nama properti dari[Koleksi Properti Dokumen](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Mengelola Properti Buatan Sistem" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Menambah dan Menghapus Metadata yang Ditentukan Khusus" %}}

Untuk menangani properti khusus, API menyediakan[Properti Dokumen Khusus](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , dan pengembang dapat dengan mudah mengakses properti yang ada serta menambahkan properti baru menggunakan[tambahkan metode](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) dari[KoleksiProperti Dokumen Khusus](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) kelas menambahkan properti dan mengembalikan referensi untuk properti baru sebagai[Properti.Properti Dokumen](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) obyek. Kelas DocumentProperty digunakan untuk mengambil nama, nilai, dan tipe properti dokumen sebagai[Properti Dokumen.Nama](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Properti Dokumen.Nilai](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [Properti Dokumen.Jenis](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) yang mengembalikan salah satu dari[Jenis properti](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) nilai pencacahan.
 
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menghapus Properti Kustom di File Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
