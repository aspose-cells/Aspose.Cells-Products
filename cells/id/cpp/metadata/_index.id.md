---
title: Kelola Metadata File Excel melalui C++

description: Lihat, tambahkan, edit, hapus, atau ekstrak metadata file Excel menggunakan C++ perpustakaan
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Metadata Dokumen Excel melalui C++" h2="Lihat, sisipkan, perbarui, hapus, atau ekstrak properti dokumen Excel khusus dan bawaan dalam C++ aplikasi." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadata di Excel - Cara melihat, menyisipkan, dan menghapus metadata file excel. [C++ Perpustakaan Excel](/cells/cpp/) memfasilitasi dengan cara mudah dengan mendukung properti bawaan / yang ditentukan sistem seperti nama penulis, judul, statistik dokumen, dll. Kadang-kadang diperlukan seperti memeriksa kapan terakhir file dimodifikasi atau disimpan bersama dengan properti khusus / yang ditentukan pengguna dalam bentuk pasangan nama/nilai. Untuk mengotomatiskan proses, pustaka mendukung pembuatan dan pemeliharaan file Excel metadata besar. [Buat metode IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) dari [Kelas Pabrik](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Buka Buku Kerja berdasarkan jalur, aliran, dan FileFormatType khusus. Jadi muat file dengan metode yang sesuai untuk diproses lebih lanjut. Beberapa kemungkinan yang tercantum di bawah ini dan pengembang dapat dengan mudah meningkatkan kode mereka sesuai dengan kebutuhan aplikasi. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Baca dan Perbarui Properti Bawaan" %}}

Untuk mengotomatiskan properti bawaan, API menyediakan [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metode yang mengembalikan koleksi DocumentProperties yang mewakili semua properti dokumen bawaan dari spreadsheet. Setelah mengakses semua properti bawaan, akses properti yang relevan menggunakan metode yang relevan seperti GetTitle(), GetSubject() dll. Untuk memperbarui properti, API menyediakan metode seperti SetTitle, SetSubject, SetAuthor, SetComments dll. Lihat [koleksi properti dokumen bawaan](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) untuk fungsi yang dibutuhkan.

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Membaca Properti yang Ditetapkan Sistem" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Memperbarui Properti Bawaan" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Lihat dan Tambahkan Properti yang Ditetapkan Khusus" %}}

Untuk menangani properti khusus, API menyediakan [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) yang mengembalikan semua koleksi properti dokumen kustom dari spreadsheet. Pertama mengakses properti kustom melalui metode ini, pengembang dapat menggunakan metode yang relevan untuk menambahkan properti seperti AddIDocumentProperty, AddLinkToContentProperty dan juga menggunakan UpdateLinkedPropertyValue, UpdateLinkedRange untuk memperbarui nilai properti dokumen kustom yang masing-masing tertaut ke konten dan ke rentang tertaut. Pengembang dapat menggunakan metode yang relevan dari [kumpulan properti dokumen khusus](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Melihat Properti Khusus" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Menambahkan Metadata di File Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
