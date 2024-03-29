---
title: Pisahkan lembar Lembar Kerja Excel secara bijaksana di C#
description: Kode sumber C# yang menjelaskan cara membagi file Excel Microsoft menjadi beberapa file dalam aplikasi Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Pemisahan File Excel via .NET" h2="Pisahkan satu dokumen Excel menjadi file berbeda menggunakan kode C# dalam aplikasi berbasis .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Perpustakaan Excel](/cells/id/net/) mampu membagi dokumen Excel menjadi beberapa spreadsheet dalam aplikasi berbasis .NET. Format file yang didukung antara lain XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Dokumen Excel menjadi Beberapa File" %}}
Cara paling sederhana untuk membagi lembar file Excel adalah, Mengakses semua lembar melalui[Lembar kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Mengulangi setiap lembar dan memanggil[Menyalin](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metode. Akhirnya menyimpannya ke jalur yang ditentukan.

 + Muat file Excel dengan path lengkap menggunakan[Kelas buku kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Ulangi setiap lembar
+ Buat objek kelas Buku Kerja baru
 + Salin lembar melalui[Metode penyalinan](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Panggil metode Save() dan berikan nama file (path lengkap) yang memiliki SaveFormat yang relevan.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Membagi File Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Pisahkan Lembar Kerja Excel menjadi Panel" %}}

 Untuk membagi jendela lembar kerja menjadi beberapa panel, API menyediakan[Metode terpisah](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) dari kelas lembar kerja, yang menyediakan tampilan lembar kerja yang terbagi. Untuk menghapus tampilan terpisah, API menyediakan[Hapus metode Split](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Terakhir simpan ke jalur yang ditentukan.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Membagi Jendela Lembar Kerja Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghapus Tampilan Pan Terpisah" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
