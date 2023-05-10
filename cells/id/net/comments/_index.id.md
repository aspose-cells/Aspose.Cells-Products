---
title: Sisipkan komentar di Excel via .NET
description:  Kode sumber C# itu cara memasukkan komentar ke dalam file Excel Microsoft menggunakan Perpustakaan .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> penyisipan komentar Excel via .NET" h2="Buat dokumen Excel dan sisipkan komentar menggunakan API sisi server di aplikasi berbasis .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Anda dapat menambahkan komentar ke sel. Saat sel memiliki komentar, indikator akan muncul di sudut sel. Komentar muncul saat Anda mengarahkan kursor ke sel. Komentar ini dapat digunakan untuk diskusi, petunjuk khusus, atau markup konten dokumen.[.NET Perpustakaan Excel](/cells/id/net/)mendukung penyisipan komentar di file Excel. Untuk ini, API menyediakan a[Komentar](https://reference.aspose.com/cells/net/aspose.cells/comment) kelas untuk blok penyusun komentar.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Sisipkan komentar di File Excel" %}}

 Memasukkan komentar menggunakan Excel API itu sederhana. Prosesnya adalah, Buat[Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) objek dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Masukkan data sel yang diperlukan menggunakan[metode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Tambahkan komentar ke lembar kerja dengan menggunakan[KoleksiKomentar](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[Tambahkan metode](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menyisipkan Komentar di Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
