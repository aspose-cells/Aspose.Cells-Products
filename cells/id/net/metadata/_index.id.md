---
title: Kelola Metadata File Excel via .NET C#
description: Lihat, tambah, edit, hapus, atau ekstrak metadata file Excel hanya dengan beberapa baris kode C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata File Excel via .NET" h2="Lihat, tambahkan, perbarui, hapus, atau ekstrak properti file Excel bawaan dan kustom menggunakan API .NET sisi server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/id/net/) mendukung pengelolaan properti yang ditentukan sistem (bawaan) seperti judul, nama penulis, statistik dokumen, dll. Serta properti yang ditentukan pengguna (kustom) dalam bentuk pasangan nama-nilai. Ada[Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) untuk memuat file, dan[Koleksi Lembar Kerja](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)berkaitan dengan koleksi lembar kerja serta[Kelas lembar kerja](https://reference.aspose.com/cells/net/aspose.cells/worksheet) untuk mewakili lembar kerja tunggal. Seiring dengan kelas-kelas ini, BuiltInDocumentProperties, CustomDocumentProperties membuat proses pengelolaan metadata menjadi sederhana.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengelola Properti Bawaan" %}}

 Untuk mengelola properti yang ditentukan sistem, API menyediakan[Properti Dokumen Bawaan](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , dan pemrogram dapat dengan mudah mengakses properti bawaan dan memperbarui nilainya. Bergantung pada persyaratan aplikasi, pengembang dapat menggunakan indeks atau nama properti dari[KoleksiProperti Dokumen](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengelola Properti Bawaan" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Mengelola Properti yang Ditentukan Khusus" %}}

 Untuk mengelola properti yang ditentukan pengguna, API menyediakan[Properti Dokumen Khusus](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , dan pengembang dapat dengan mudah mengakses properti yang sudah ditambahkan serta menambahkan properti baru. Untuk menambahkan properti khusus,[Tambahkan metode](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) dari[Pengumpulan Properti Dokumen Kustom](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class menambahkan properti dan mengembalikan referensi untuk properti baru sebagai[Properti.DokumenProperti](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)obyek. Kelas DocumentProperty digunakan untuk mengambil nama, nilai, dan jenis properti dokumen sebagai[PropertiDokumen.Nama](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [Properti Dokumen.Nilai](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [Properti Dokumen.Tipe](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) yang mengembalikan salah satu[Jenis properti](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) nilai pencacahan.
 
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghapus Properti Kustom di File Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
