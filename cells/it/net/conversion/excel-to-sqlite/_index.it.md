---
title: C# Convertitore da EXCEL a SQLite - Convertitore da EXCEL a SQLite
description: Aspose Excel. Converti EXCEL in SQLite in modo rapido e semplice con Aspose.Cells. C# EXCEL in SQLite. C# Salva EXCEL in SQLite. Salva EXCEL come SQLite utilizzando C#.
keywords: [Aspose Excel., C# Aspose.Cells., Convert EXCEL to SQLite in C#., Save EXCEL to SQLite using C#., C# EXCEL to SQLite saveformat., EXCEL to SQLite Converter., C# Save EXCEL as SQLite]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti EXCEL in SQLite in C#" h2="Libreria C# ad alta velocità per convertire EXCEL in SQLite. Si tratta di una soluzione software professionale per importare ed esportare EXCEL, SQLite e molti altri formati sulle piattaforme .NET Framework, .NET Core o Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SQLite" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converti EXCEL in SQLite utilizzando C#" %}}
 Come posso convertire EXCEL in SQLite? Con la libreria Aspose.Cells for .NET, puoi convertire facilmente EXCEL in SQLite a livello di codice con poche righe di codice.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)è in grado di creare applicazioni multipiattaforma con la capacità di generare, modificare, convertire, eseguire il rendering e stampare tutti i file Excel. .NET Excel API non solo converte tra formati di foglio di calcolo, ma può anche eseguire il rendering di file Excel come immagini, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT e altro, rendendolo quindi una scelta perfetta per scambiare documenti in formati standard del settore. Aprire[NuGet](https://www.nuget.org/packages/aspose.cells) gestore pacchetti, cerca Aspose.Cells e installa. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di Gestione pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Come convertire EXCEL in SQLite tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

Hai bisogno di convertire i file EXCEL in SQLite a livello di codice? .NET gli sviluppatori possono caricare e convertire facilmente EXCEL in SQLite in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1.  Installa 'Aspose.Cells for .NET'.
1.  Aggiungi un riferimento di libreria (importa la libreria) al tuo progetto C#.
1.  Carica il file EXCEL con un'istanza della cartella di lavoro.
1.  Crea un'istruzione Insert in base ai nomi e ai valori delle colonne.
1.  Esegui istruzioni per inserire dati nel database SQLite.

{{% blocks/products/pf/agp/code-block title="Codice di esempio per convertire EXCEL in SQLite - C#" offSpacer="" %}}

```cs
var connectionString = "Data Source = E:\\SQLiteTestData.sqlite;Cache=Shared;";
var tableName = "countrylanguage";
string excelFilePath = "SQLiteData.xlsx";
string autoIncrementColumnName = "id";

Workbook workbook = new Workbook(excelFilePath);
Worksheet worksheet = workbook.Worksheets[0];

DataTable dataTable = worksheet.Cells.ExportDataTableAsString(0, 0, worksheet.Cells.MaxDataRow + 1, worksheet.Cells.MaxDataColumn + 1, true);

using (SQLiteConnection connection = new SQLiteConnection(connectionString))
{
    connection.Open();
    using (SQLiteTransaction transaction = connection.BeginTransaction())
    {
        using (SQLiteCommand cmd = new SQLiteCommand())
        {
            cmd.Connection = connection;
            cmd.Transaction = transaction;

            foreach (DataRow dr in dataTable.Rows)
            {
                string columnNames = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select(c => $"`{c.ColumnName}`").Where(c => c != $"`{autoIncrementColumnName}`"));
                string valuesPlaceholders = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select((c, index) => $"@value{index + 1}")
                    .Where((val, index) => dataTable.Columns[index].ColumnName != autoIncrementColumnName));

                string insertCmd = $"INSERT INTO `{tableName}` ({columnNames}) VALUES ({valuesPlaceholders})";
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

{{% blocks/products/pf/agp/content h2="Libreria C# per convertire EXCEL in SQLite" %}}

{{% blocks/products/pf/agp/text %}}

Esistono due opzioni alternative per installare "Aspose.Cells for .NET" sul tuo sistema. Scegline uno che soddisfi le tue esigenze e segui le istruzioni passo passo:

{{% /blocks/products/pf/agp/text %}}

1.  Installa un[NuGet Pacchetto](https://www.nuget.org/packages/Aspose.Cells/) . Vedere[Documentazione](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Installa la libreria utilizzando[Console di gestione pacchetti](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) all'interno dell'IDE di Visual Studio

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione .NET, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con le piattaforme .NET, .NET Core, Windows Azure o Mono.
-  Ambiente di sviluppo come Microsoft Visual Studio.
-  Aggiungi il riferimento alla DLL Aspose.Cells for .NET nel tuo progetto.

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire EXCEL in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-html/" name="ECCELLERE AL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-md/" name="ECCELLERE A MD" description="Linguaggio di ribasso" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-mhtml/" name="ECCELLERE AL MHTML" description="Formato di archivio delle pagine Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-ods/" name="ECCELLERE AL ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-pdf/" name="ECCELLERE AL PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-png/" name="ECCELLERE AL PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-svg/" name="ECCELLERE AL SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tiff/" name="ECCELLERE AL TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tsv/" name="ECCELLERE AL TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-txt/" name="ECCELLERE AL TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xls/" name="ECCELLERE AL XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsb/" name="ECCELLERE AL XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsm/" name="ECCELLERE AL XLSM" description="File di foglio di calcolo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsx/" name="ECCELLERE AL XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlt/" name="ECCELLERE AL XLT" description="Microsoft Modello Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltm/" name="ECCELLERE AL XLTM" description="Modello con attivazione macro di Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltx/" name="ECCELLERE AL XLTX" description="Modello Excel OpenXML di Office" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xml/" name="EXCEL IN XML" description="Linguaggio di markup estensibile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xps/" name="ECCELLERE AL XPS" description="Specifiche della carta XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-json/" name="ECCELLERE AL JSON" description="Notazione oggetto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
