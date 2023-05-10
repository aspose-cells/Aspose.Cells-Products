---
title: Anotasi File Excel via Java
description: Tambah atau hapus anotasi data spreadsheet Excel dan OpenOffice dengan perpustakaan Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Kelola Microsoft<sup>&reg;</sup> Anotasi Berkas Excel via Java" h2="Sisipkan catatan sederhana untuk anotasi atau hapus komentar tingkat sel spreadsheet Excel dalam aplikasi berbasis Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/id/java/) memberikan dukungan untuk mengelola anotasi di tingkat sel dengan menambahkan, mengakses, dan menghapus komentar. API menyediakan[Komentar](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [KoleksiKomentar](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Komentar Berulir](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) Dan[ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) untuk menangani komentar di semua aspek.
Format file yang didukung termasuk ODS, XLS, XLSX, XLSB dan XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotasi Data File Excel" %}}
 Mengelola Komentar di Lembar Kerja - Tidak ada batasan berapa banyak komentar yang dimiliki satu lembar di MS Excel. Satu dapat menambahkan sebanyak persyaratan aplikasi. Proses penambahan komentar adalah, create[Buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)objek kelas atau memuat file yang ada menggunakan kelas Workbook. Akses semua komentarnya menggunakan getComments(). Dapatkan indeks sel dan gunakan[setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) untuk memasukkan komentar. Selain itu, API mampu menghapus semua komentar.

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menambahkan Komentar Dalam File Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Menghapus Komentar Dalam File Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
