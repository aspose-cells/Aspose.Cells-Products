---
title: C# SQLite para EXCEL - Conversor SQLite para EXCEL
description: Aspose Excel. Converta SQLite para EXCEL de forma rápida e fácil com Aspose.Cells. C# SQLite para EXCEL. C# Salve SQLite no EXCEL. Salve SQLite como EXCEL usando C#.
keywords: [Aspose Excel., C# Aspose.Cells., Convert SQLite to EXCEL in C#., Save SQLite to EXCEL using C#., C# SQLite to EXCEL saveformat., SQLite to EXCEL Converter., C# Save SQLite as EXCEL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter SQLite para EXCEL em C#" h2="Biblioteca C# de alta velocidade para conversão de SQLite em EXCEL. Esta é uma solução de software profissional para importar e exportar EXCEL, SQLite e muitos outros formatos nas plataformas .NET Framework, .NET Core ou Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SQLite" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converter SQLite em EXCEL usando C#" %}}
 Como faço para converter SQLite em EXCEL? Com a biblioteca Aspose.Cells for .NET, você pode facilmente converter SQLite para EXCEL programaticamente com algumas linhas de código.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)é capaz de construir aplicativos multiplataforma com a capacidade de gerar, modificar, converter, renderizar e imprimir todos os arquivos Excel. .NET Excel API não apenas converte formatos de planilha, mas também pode renderizar arquivos Excel como imagens, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT e muito mais, tornando-o a escolha perfeita para troca de documentos em formatos padrão da indústria. Abrir[NuGet](https://www.nuget.org/packages/aspose.cells) gerenciador de pacotes, procure Aspose.Cells e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Como converter SQLite para EXCEL via C#" %}}

{{% blocks/products/pf/agp/text %}}

Precisa converter dados SQLite para EXCEL programaticamente? Os desenvolvedores .NET podem facilmente carregar e converter SQLite em EXCEL em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1.  Instale 'Aspose.Cells for .NET'.
1.  Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto C#.
1.  Consulte dados do banco de dados SQLite para obter um objeto DataTable.
1.  Crie uma nova pasta de trabalho e importe dados de um objeto DataTable.
1. Salve os dados no formato xlsx chamando o método Workbook.Save.

{{% blocks/products/pf/agp/code-block title="Código de exemplo para converter SQLite em EXCEL - C#" offSpacer="" %}}

```cs
var connectionString = "Data Source = SQLiteTestData.sqlite;Cache=Shared;";
var tableName = "countrylanguage";

string query = $"SELECT * FROM {tableName}";

using (SQLiteConnection connection = new SQLiteConnection(connectionString))
{
    SQLiteConnection a =  connection.OpenAndReturn();
    //connection.Open();
    SQLiteCommand cmd = new SQLiteCommand(query, connection);
    SQLiteDataAdapter adapter = new SQLiteDataAdapter(cmd);

    DataTable dataTable = new DataTable();
    adapter.Fill(dataTable);

    Workbook workbook = new Workbook();
    Worksheet worksheet = workbook.Worksheets[0];
    worksheet.Cells.ImportData(dataTable, 0, 0, new ImportTableOptions() { InsertRows = true });
    workbook.Save("SQLiteData.xlsx");
}

```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Biblioteca C# para converter SQLite para EXCEL" %}}

{{% blocks/products/pf/agp/text %}}

Existem duas opções alternativas para instalar “Aspose.Cells for .NET” em seu sistema. Escolha um que se adeque às suas necessidades e siga as instruções passo a passo:

{{% /blocks/products/pf/agp/text %}}

1.  Instale um[Pacote NuGet](https://www.nuget.org/packages/Aspose.Cells/) . Ver[Documentação](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Instale a biblioteca usando[Console do gerenciador de pacotes](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) dentro do IDE do Visual Studio

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de exemplo de conversão .NET, certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com plataformas .NET, .NET Core, Windows Azure ou Mono.
-  Ambiente de desenvolvimento como Microsoft Visual Studio.
-  Adicione referência à DLL Aspose.Cells for .NET em seu projeto.

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
