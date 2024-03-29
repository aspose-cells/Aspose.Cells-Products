---
title: C# EXCEL-ből SqlServerbe - EXCEL-ből SqlServerbe konvertáló
description: Aspose Excel. Konvertálja az EXCEL-t SqlServerré gyorsan és egyszerűen a Aspose.Cells. C# EXCEL-ből SqlServerré. C# Mentse az EXCEL-t az SqlServerbe. Mentse az EXCEL-t SqlServer-ként a C# használatával.
keywords: [Aspose Excel., C# Aspose.Cells., Convert EXCEL to SqlServer in C#., Save EXCEL to SqlServer using C#., C# EXCEL to SqlServer saveformat., EXCEL to SqlServer Converter., C# Save EXCEL as SqlServer]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja az EXCEL-t SqlServer-re a C#-ben" h2="Nagy sebességű C# könyvtár az EXCEL-ből SqlServerré konvertálásához. Ez egy professzionális szoftvermegoldás EXCEL, SqlServer és sok más formátum importálásához és exportálásához .NET Framework, .NET Core vagy Mono platformokon." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SqlServer" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertálja az EXCEL-t SqlServerbe a C# használatával" %}}
 Hogyan konvertálhatom az EXCEL-t SqlServerre? A Aspose.Cells for .NET könyvtárral könnyedén konvertálhatja az EXCEL-t SqlServerbe programozottan néhány sornyi kóddal.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)képes többplatformos alkalmazásokat létrehozni, módosítani, konvertálni, renderelni és kinyomtatni az összes Excel fájlt. .NET Az Excel API nemcsak a táblázatformátumok között konvertál, hanem Excel-fájlokat is képes megjeleníteni képként, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT és egyebekként, így tökéletes választás a szabványos formátumú dokumentumok cseréjéhez. Nyisd ki[NuGet](https://www.nuget.org/packages/aspose.cells) csomagkezelő, keresse meg a Aspose.Cells-et, és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Az EXCEL konvertálása SqlServerre a C# számon keresztül" %}}

{{% blocks/products/pf/agp/text %}}

Programozottan kell konvertálnia az EXCEL fájlokat SqlServerbe? .NET A fejlesztők egyszerűen betölthetik és néhány sornyi kóddal SqlServerré konvertálhatják az EXCEL-t.

{{% /blocks/products/pf/agp/text %}}

1.  Telepítse a „Aspose.Cells for .NET” fájlt.
1.  Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a C# projekthez.
1.  Töltse be az EXCEL-fájlt a munkafüzet egy példányával.
1.  Hozzon létre egy Insert utasítást oszlopnevek és értékek alapján.
1. Utasítások végrehajtása adatok beszúrásához az SqlServer adatbázisba.

{{% blocks/products/pf/agp/code-block title="Mintakód az EXCEL SqlServerré konvertálásához - C#" offSpacer="" %}}

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

{{% blocks/products/pf/agp/content h2="C# könyvtár az EXCEL SqlServerré konvertálásához" %}}

{{% blocks/products/pf/agp/text %}}

Két alternatív lehetőség van a „Aspose.Cells for .NET” telepítésére a rendszerre. Kérjük, válasszon egyet, amely megfelel az Ön igényeinek, és kövesse a lépésről lépésre található utasításokat:

{{% /blocks/products/pf/agp/text %}}

1.  Telepítse a[NuGet Csomag](https://www.nuget.org/packages/Aspose.Cells/) . Lát[Dokumentáció](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Telepítse a könyvtárat a segítségével[Csomagkezelő konzol](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) a Visual Studio IDE-n belül

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós példakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows vagy kompatibilis operációs rendszer .NET, .NET Core, Windows Azure vagy Mono platformmal.
-  Fejlesztői környezet, például Microsoft Visual Studio.
-  Adjon hivatkozást a Aspose.Cells for .NET DLL-re a projektben.

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az EXCEL-t sok más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-html/" name="EXCEL: HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-md/" name="EXCEL TO MD" description="Markdown Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-mhtml/" name="EXCEL: MHTML" description="Weboldal archív formátuma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-ods/" name="EXCEL: ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-pdf/" name="EXCEL: PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-png/" name="EXCEL: PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-svg/" name="EXCEL: SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tiff/" name="EXCEL: TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tsv/" name="EXCEL: TSV" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-txt/" name="EXCEL: TXT" description="Szöveges dokumentum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xls/" name="EXCEL: XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsb/" name="EXCEL: XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsm/" name="EXCEL: XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsx/" name="EXCEL: XLSX" description="OOXML Excel fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlt/" name="EXCEL: XLT" description="Microsoft Excel-sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltm/" name="EXCEL: XLTM" description="Excel-makró-kompatibilis sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltx/" name="EXCEL: XLTX" description="Office OpenXML Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xml/" name="EXCEL TO XML" description="Bővíthető jelölőnyelv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xps/" name="EXCEL: XPS" description="XML papír specifikációk" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-json/" name="EXCEL: JSON" description="JavaScript objektum jelölés" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
