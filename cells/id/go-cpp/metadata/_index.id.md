---
title: Kelola Metadata File Excel dengan Go via C++
description: Melihat, menambahkan, mengedit, menghapus, atau mengekstrak metadata file Excel menggunakan Go melalui pustaka C++.
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Metadata Dokumen Excel Microsoft<sup>&reg;</sup> melalui Go via C++" h2="Melihat, menyisipkan, memperbarui, menghapus, atau mengekstrak properti dokumen Excel kustom dan bawaan dalam aplikasi C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata di Excel - Cara melihat, menyisipkan, dan menghapus metadata file Excel.[Buka melalui C++ Perpustakaan Excel](/cells/id/go-cpp/)Faclitates mempermudah proses dengan mendukung properti bawaan/yang ditentukan sistem seperti nama penulis, judul, statistik dokumen, dll., yang terkadang dibutuhkan untuk memeriksa kapan terakhir kali file dimodifikasi atau disimpan, bersama dengan properti khusus/yang ditentukan pengguna dalam bentuk pasangan nama/nilai. Untuk mengotomatiskan proses, pustaka ini mendukung pembuatan dan pemeliharaan file metadata Excel berukuran besar.[Buku Kerja](https://reference.aspose.com/cells/go-cpp/workbook/) Kelas ini membuka buku kerja berdasarkan jalur, aliran data, dan tipe format file khusus. Jadi, muat file dengan metode yang sesuai untuk pemrosesan lebih lanjut. Beberapa kemungkinan tercantum di bawah ini dan pengembang dapat dengan mudah meningkatkan kode mereka sesuai dengan kebutuhan aplikasi.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Membaca dan Memperbarui Properti Bawaan" %}}

 Untuk mengotomatiskan properti bawaan, API menyediakan[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Metode yang mengembalikan koleksi DocumentProperties yang mewakili semua properti dokumen bawaan spreadsheet. Setelah mengakses semua properti bawaan, akses properti yang relevan menggunakan metode yang relevan seperti GetTitle(), GetSubject(), dll. Untuk memperbarui properti, API menyediakan metode seperti SetTitle, SetSubject, SetAuthor, SetComments, dll. Lihat[koleksi properti dokumen bawaan](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) untuk fungsi yang dibutuhkan.

{{% blocks/products/pf/feature-page-code h3="Gunakan kode C++ untuk membaca properti yang ditentukan sistem." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Gunakan kode C++ untuk memperbarui properti bawaan." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Lihat dan Tambahkan Properti yang Didefinisikan Secara Kustom" %}}

 Untuk menangani properti khusus, API menyediakan[Buku Kerja::DapatkanPropertiDokumentasiKustom](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)yang mengembalikan semua koleksi properti dokumen kustom dari spreadsheet. Pertama-tama, dengan mengakses properti kustom melalui metode ini, pengembang dapat menggunakan metode yang relevan untuk menambahkan properti seperti AddIDocumentProperty, AddLinkToContentProperty dan juga menggunakan UpdateLinkedPropertyValue, UpdateLinkedRange untuk memperbarui nilai properti dokumen kustom yang masing-masing terhubung ke konten dan ke rentang yang ditautkan. Pengembang dapat menggunakan metode yang relevan dari[kumpulan properti dokumen kustom](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Masuk melalui kode C++ untuk melihat properti khusus." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Gunakan kode C++ untuk menambahkan metadata pada file Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}