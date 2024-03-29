---
title: C# EXCEL ke SqlServer - Konverter EXCEL ke SqlServer
description: Aspose Unggul. Konversi EXCEL ke SqlServer dengan cepat dan mudah dengan Aspose.Cells. C# EXCEL ke SqlServer. C# Simpan EXCEL ke SqlServer. Simpan EXCEL sebagai SqlServer menggunakan C#.
keywords: [Aspose Excel., C# Aspose.Cells., Convert EXCEL to SqlServer in C#., Save EXCEL to SqlServer using C#., C# EXCEL to SqlServer saveformat., EXCEL to SqlServer Converter., C# Save EXCEL as SqlServer]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ubah EXCEL menjadi SqlServer di C#" h2="Pustaka C# berkecepatan tinggi untuk mengonversi EXCEL ke SqlServer. Ini adalah solusi perangkat lunak profesional untuk mengimpor dan mengekspor EXCEL, SqlServer, dan banyak format lainnya pada Platform .NET Framework, .NET Core, atau Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SqlServer" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konversi EXCEL ke SqlServer Menggunakan C#" %}}
 Bagaimana cara mengubah EXCEL ke SqlServer? Dengan perpustakaan Aspose.Cells for .NET, Anda dapat dengan mudah mengonversi EXCEL ke SqlServer secara terprogram dengan beberapa baris kode.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)mampu membangun aplikasi lintas platform dengan kemampuan untuk menghasilkan, memodifikasi, mengkonversi, merender dan mencetak semua file Excel. .NET Excel API tidak hanya mengkonversi antar format spreadsheet, tetapi juga dapat merender file Excel sebagai gambar, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT dan banyak lagi, sehingga menjadikannya pilihan sempurna untuk bertukar dokumen dalam format standar industri. Membuka[NuGet](https://www.nuget.org/packages/aspose.cells) manajer paket, cari Aspose.Cells dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Perintah Konsol Manajer Paket" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi EXCEL ke SqlServer melalui C#" %}}

{{% blocks/products/pf/agp/text %}}

Perlu mengonversi file EXCEL ke SqlServer secara terprogram? Pengembang .NET dapat dengan mudah memuat & mengonversi EXCEL ke SqlServer hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1.  Instal 'Aspose.Cells for .NET'.
1.  Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek C# Anda.
1.  Muat file EXCEL dengan instance Buku Kerja.
1.  Buat pernyataan Sisipkan berdasarkan nama dan nilai kolom.
1. Jalankan pernyataan untuk memasukkan data ke dalam database SqlServer.

{{% blocks/products/pf/agp/code-block title="Contoh Kode untuk Mengonversi EXCEL ke SqlServer - C#" offSpacer="" %}}

```cs
var connectionString = "Server=localhost;Database=SqlServerTestDataBase;User ID=root;Password=admin;Trusted_Connection=False;";
var tableName = "countrylanguage";
string excelFilePath = "SqlServerData.xlsx";
string autoIncrementColumnName = "id";

Workbook workbook = new Workbook(excelFilePath);
Worksheet worksheet = workbook.Worksheets[0];

DataTable dataTable = worksheet.Cells.ExportDataTableAsString(0, 0, worksheet.Cells.MaxDataRow + 1, worksheet.Cells.MaxDataColumn + 1, true);

using (SqlConnection connection = new SqlConnection(connectionString))
{
    connection.Open();
    using (SqlTransaction transaction = connection.BeginTransaction())
    {
        using (SqlCommand cmd = new SqlCommand())
        {
            cmd.Connection = connection;
            cmd.Transaction = transaction;

            foreach (DataRow dr in dataTable.Rows)
            {
                string columnNames = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select(c => $"[{c.ColumnName}]").Where(c => c != $"[{autoIncrementColumnName}]"));
                string valuesPlaceholders = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select((c, index) => $"@value{index + 1}")
                    .Where((val, index) => dataTable.Columns[index].ColumnName != autoIncrementColumnName));

                string insertCmd = $"INSERT INTO [{tableName}] ({columnNames}) VALUES ({valuesPlaceholders})";
                cmd.CommandText = insertCmd;

                cmd.Parameters.Clear();
                for (int i = 0; i < dataTable.Columns.Count; i++)
                {
                    if (dataTable.Columns[i].ColumnName != autoIncrementColumnName)
                    {
                        cmd.Parameters.AddWithValue($"@value{i + 1}", dr[i]);
                    }
                }

                cmd.ExecuteNonQuery();
            }
        }
        transaction.Commit();
    }
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Perpustakaan C# untuk mengonversi EXCEL ke SqlServer" %}}

{{% blocks/products/pf/agp/text %}}

Ada dua opsi alternatif untuk menginstal "Aspose.Cells for .NET" ke sistem Anda. Silakan pilih salah satu yang sesuai dengan kebutuhan Anda dan ikuti petunjuk langkah demi langkah:

{{% /blocks/products/pf/agp/text %}}

1.  Pasang a[NuGet Paket](https://www.nuget.org/packages/Aspose.Cells/) . Melihat[Dokumentasi](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Instal perpustakaan menggunakan[Konsol Manajer Paket](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) dalam Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan kode contoh konversi .NET, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows atau OS yang kompatibel dengan Platform .NET, .NET Core, Windows Azure, atau Mono..
-  Lingkungan pengembangan seperti Microsoft Visual Studio.
-  Tambahkan referensi ke DLL Aspose.Cells for .NET di proyek Anda.

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi yang Didukung Lainnya" subTitle="Anda juga dapat mengonversi EXCEL ke banyak format file lainnya termasuk beberapa format yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-html/" name="EXCEL KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-md/" name="EXCEL UNTUK MD" description="Bahasa Penurunan Harga" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-mhtml/" name="EXCEL KE MHTML" description="Format Arsip Halaman Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-ods/" name="EXCEL KE ODS" description="File Lembar Bentang OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-pdf/" name="EXCEL KE PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-png/" name="EXCEL KE PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-svg/" name="EXCEL KE SVG" description="Grafik Vektor yang Dapat Diskalakan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tiff/" name="EXCEL KE TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tsv/" name="EXCEL KE TSV" description="Nilai yang Dipisahkan Tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-txt/" name="EXCEL KE TXT" description="Dokumen Teks" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xls/" name="EXCEL KE XLS" description="Format Biner Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsb/" name="EXCEL KE XLSB" description="File Buku Kerja Excel Biner" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsm/" name="EXCEL KE XLSM" description="Berkas Lembar Bentang" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsx/" name="EXCEL KE XLSX" description="Berkas OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlt/" name="EXCEL KE XLT" description="Templat Excel Microsoft" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltm/" name="EXCEL KE XLTM" description="Templat Excel yang mendukung Makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltx/" name="EXCEL KE XLTX" description="Templat Excel Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xml/" name="EXCEL KE XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xps/" name="EXCEL KE XPS" description="Spesifikasi Kertas XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-json/" name="EXCEL KE JSON" description="Notasi Objek JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
