---
title: Sisipkan komentar di Excel melalui .NET
url: /id/net/comment/
description: C# kode sumber yang cara menyisipkan komentar ke dalam file Microsoft Excel menggunakan .NET Pustaka. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Penyisipan komentar Microsoft<sup>&reg;</sup> Excel melalui .NET" h2="Buat dokumen Excel dan sisipkan komentar menggunakan API sisi server di aplikasi berbasis .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Anda dapat menambahkan komentar ke sel. Saat sel memiliki komentar, indikator muncul di sudut sel. Komentar muncul saat Anda mengarahkan kursor ke sel. Komentar ini dapat digunakan untuk diskusi, instruksi khusus, atau markup konten dokumen. [.NET Perpustakaan Excel](/cells/net/) mendukung penyisipan komentar dalam file Excel. Untuk ini, API menyediakan a [Komentar](https://reference.aspose.com/cells/net/aspose.cells/comment) kelas untuk blok bangunan komentar.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Sisipkan komentar di File Excel" %}}

Menyisipkan komentar menggunakan Excel API sangatlah mudah. Proses adalah, Buat [Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) objek dan pilih lembar kerja pertama atau lembar yang relevan dengan memberikan indeksnya. Masukkan data sel yang diperlukan menggunakan [Metode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Tambahkan komentar ke lembar kerja dengan menggunakan [Koleksi Komentar](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Tambahkan metode](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menyisipkan Komentar di Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
