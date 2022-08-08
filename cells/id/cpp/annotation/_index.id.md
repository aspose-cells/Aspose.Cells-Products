---
title: Anotasi File Excel melalui C++
url: /id/cpp/annotation/
description: Tambahkan atau hapus komentar anotasi data spreadsheet Excel dan OpenOffice dengan pustaka C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Anotasi File Excel melalui C++" h2="Tambahkan atau hapus catatan sederhana untuk anotasi atau komentar dalam C++ aplikasi berbasis." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) memberikan dukungan untuk mengelola anotasi di tingkat sel dengan menambahkan, mengakses, dan menghapus komentar. API menyediakan [komentar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) dan [KoleksiKomentar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) sebaik [DapatkanIKomentar()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) untuk menangani komentar dalam semua aspek. Format Excel yang didukung termasuk ODS, XLS, XLSX, XLSB dan XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotasi Data File Excel" %}}
Memanipulasi Komentar di Lembar Kerja - Tidak terbatas pada berapa banyak komentar yang dimiliki lembar kerja di MS Excel. Seseorang dapat memasukkan sebanyak kebutuhan aplikasi. Proses memasukkan komentar adalah, buat [buku kerja](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objek kelas untuk memuat file yang sudah ada dan pilih lembar kerja tempat Anda ingin menambahkan komentar. Dapatkan semua komentarnya menggunakan getComments(). Tambahkan komentar menggunakan [Menambahkan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusif_ptr < Aspose::Cells::Systems::String > nama sel) metode. Dapatkan indeks sel dan gunakan [setCatatan](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) untuk memasukkan komentar. Selain itu, API mampu menghapus semua komentar. Beberapa metodenya adalah [HapusKomentar()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) untuk Menghapus semua komentar di spreadsheet desainer. Lebih-lebih lagi, [HapusPada](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusif_ptr< Aspose::Cells::Systems::String > name) metode untuk menghapus elemen pada indeks tertentu atau dengan nama tertentu.

{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Menambahkan Komentar Dalam File Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}