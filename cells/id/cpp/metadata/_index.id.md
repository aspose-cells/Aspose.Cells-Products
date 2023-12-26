---
title: Kelola Metadata File Excel melalui C++
description: Lihat, tambah, edit, hapus atau ekstrak metadata file Excel menggunakan perpustakaan C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata Dokumen Excel melalui C++" h2="Lihat, sisipkan, perbarui, hapus atau ekstrak properti dokumen Excel kustom dan bawaan dalam aplikasi C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata di Excel - Cara melihat, menyisipkan dan menghapus metadata file excel.[C++ Perpustakaan Excel](/cells/id/cpp/) memfasilitasi dengan cara yang mudah dengan mendukung properti bawaan / yang ditentukan sistem seperti nama penulis, judul, statistik dokumen, dll. Kadang-kadang diperlukan seperti memeriksa kapan file terakhir diubah atau disimpan bersama dengan properti khusus / yang ditentukan pengguna dalam bentuk pasangan nama/nilai. Untuk mengotomatiskan proses, perpustakaan mendukung pembuatan dan pemeliharaan file Excel metadata berukuran besar.[Buku Kerja](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Membuka buku kerja berdasarkan jalur, aliran, dan FileFormatType khusus. Jadi muat file dengan metode yang sesuai untuk diproses lebih lanjut. Beberapa kemungkinan tercantum di bawah ini dan pengembang dapat dengan mudah menyempurnakan kode mereka sesuai dengan kebutuhan aplikasi.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Baca dan Perbarui Properti Bawaan" %}}

 Untuk mengotomatiskan properti bawaan, API menyediakan[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metode yang mengembalikan koleksi DocumentProperties yang mewakili semua properti dokumen bawaan spreadsheet. Setelah mengakses semua properti bawaan, akses properti yang relevan menggunakan metode yang relevan seperti GetTitle(), GetSubject() dll. Untuk memperbarui properti, API menyediakan metode seperti SetTitle, SetSubject, SetAuthor, SetComments dll. Lihat[koleksi properti dokumen bawaan](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) untuk fungsi yang diperlukan.

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Membaca Properti Buatan Sistem" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Memperbarui Properti Bawaan" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Lihat dan Tambahkan Properti Buatan Khusus" %}}

Untuk menangani properti khusus, API menyediakan[Buku Kerja::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) yang mengembalikan semua kumpulan properti dokumen kustom dari spreadsheet. Pertama-tama mengakses properti khusus melalui metode ini, pengembang dapat menggunakan metode yang relevan untuk menambahkan properti seperti AddIDocumentProperty, AddLinkToContentProperty dan juga menggunakan UpdateLinkedPropertyValue, UpdateLinkedRange untuk memperbarui nilai properti dokumen khusus yang masing-masing tertaut ke konten dan ke rentang tertaut. Pengembang dapat menggunakan metode yang relevan dari[kumpulan properti dokumen khusus](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Melihat Properti Kustom" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
