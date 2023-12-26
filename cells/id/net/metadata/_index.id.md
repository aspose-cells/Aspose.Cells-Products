---
title: Kelola Metadata File Excel via .NET C#
description: Lihat, tambah, edit, hapus atau ekstrak metadata file Excel hanya dengan beberapa baris kode C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata File Excel via .NET" h2="Lihat, tambahkan, perbarui, hapus atau ekstrak properti file Excel bawaan dan kustom menggunakan API sisi server .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Unggul API](/cells/id/net/) mendukung pengelolaan properti yang ditentukan sistem (bawaan) seperti judul, nama penulis, statistik dokumen, dll. serta properti yang ditentukan pengguna (khusus) dalam bentuk pasangan nama-nilai. Ada[Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) untuk memuat file, dan[Koleksi Lembar Kerja](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) berkaitan dengan pengumpulan lembar kerja serta[Kelas lembar kerja](https://reference.aspose.com/cells/net/aspose.cells/worksheet) untuk mewakili lembar kerja tunggal. Bersama dengan kelas-kelas ini, BuiltInDocumentProperties, CustomDocumentProperties membuat proses manajemen metadata menjadi sederhana.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengelola Properti Bawaan" %}}

 Untuk mengelola properti yang ditentukan sistem, API menyediakan[Properti BuiltInDocument](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) dan pemrogram dapat dengan mudah mengakses properti bawaan dan memperbarui nilainya. Tergantung pada kebutuhan aplikasi, pengembang dapat menggunakan indeks atau nama properti dari[Koleksi Properti Dokumen](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengelola Properti Bawaan" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Mengelola Properti yang Ditetapkan Kustom" %}}

 Untuk mengelola properti yang ditentukan pengguna, API menyediakan[Properti Dokumen Khusus](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , dan pengembang dapat dengan mudah mengakses properti yang sudah ditambahkan serta menambahkan properti baru. Untuk menambahkan properti khusus,[Tambahkan metode](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) dari[KoleksiProperti Dokumen Khusus](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) kelas menambahkan properti dan mengembalikan referensi untuk properti baru sebagai[Properti.Properti Dokumen](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) obyek. Kelas DocumentProperty digunakan untuk mengambil nama, nilai, dan tipe properti dokumen sebagai[Properti Dokumen.Nama](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [Properti Dokumen.Nilai](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [Properti Dokumen.Jenis](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) yang mengembalikan salah satu dari[Jenis properti](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) nilai pencacahan.
 
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghapus Properti Kustom di File Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
