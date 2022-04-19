---
title: Anotasi File Excel melalui Java
url: /id/java/annotation/
description: Tambahkan atau hapus anotasi data spreadsheet Excel dan OpenOffice dengan Java library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Anotasi File Excel melalui Java" h2="Sisipkan catatan sederhana untuk anotasi atau hapus komentar tingkat sel spreadsheet Excel dalam Java aplikasi berbasis." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) memberikan dukungan untuk mengelola anotasi di tingkat sel dengan menambahkan, mengakses, dan menghapus komentar. API menyediakan [Komentar](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Koleksi Komentar](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Komentar Berutas](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) dan [KoleksiKomentar Berulir](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) untuk menangani komentar dalam semua aspek.
Format file yang didukung termasuk ODS, XLS, XLSX, XLSB dan XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotasi Data File Excel" %}}
Mengelola Komentar di Lembar Kerja - Tidak ada batasan berapa banyak komentar yang dimiliki lembar kerja di MS Excel. Seseorang dapat menambahkan sebanyak kebutuhan aplikasi. Proses menambahkan komentar adalah, buat [buku kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objek kelas atau memuat file yang ada menggunakan kelas Buku Kerja. Akses semua komentarnya menggunakan getComments(). Dapatkan indeks sel dan gunakan [setCatatan](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) untuk memasukkan komentar. Selain itu, API mampu menghapus semua komentar. 

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menambahkan Komentar Dalam File Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menghapus Komentar Dalam File Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}