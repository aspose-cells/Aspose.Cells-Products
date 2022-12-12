---
title: Pisahkan lembar kerja Excel dengan bijak di C#

description: C# kode sumber yang menjelaskan cara membagi berkas Microsoft Excel menjadi beberapa berkas dalam aplikasi C#.NET Visual
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pemisahan File Microsoft<sup>&reg;</sup> Excel melalui .NET" h2="Pisahkan satu dokumen Excel menjadi file yang berbeda menggunakan C# kode dalam .NET aplikasi berbasis" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Perpustakaan Excel](/cells/net/) mampu membagi dokumen Excel menjadi beberapa spreadsheet dalam .NET aplikasi berbasis. Format file yang didukung termasuk XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Dokumen Excel menjadi Beberapa File" %}}
Cara paling sederhana untuk membagi lembar file Excel adalah, Mengakses semua lembar melalui [Lembar kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterasi melalui setiap lembar dan memanggil [Salinan](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metode. Akhirnya menyimpannya ke jalur yang ditentukan. 

+ Muat file Excel dengan path lengkap menggunakan [Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Ulangi melalui setiap lembar
+ Buat objek kelas Buku Kerja baru
+ Salin lembar melalui [Salin metode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Panggil metode Save() dan berikan nama file (path lengkap) yang memiliki SaveFormat yang relevan.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Memisahkan File Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Lembar Kerja Excel menjadi Panel" %}}

Untuk membagi jendela lembar kerja menjadi panel, API menyediakan [Metode terpisah](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) kelas lembar kerja, yang menyediakan tampilan lembar kerja yang terpisah. Untuk menghapus tampilan terbelah, API menyediakan [Hapus metode Split](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Terakhir simpan ke jalur yang ditentukan. 

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Memisahkan Jendela Lembar Kerja Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghapus Tampilan Pan Terpisah" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
