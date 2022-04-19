---
title: Mesclar diferentes arquivos do Excel em um único em Java
url: /pt/java/merger/
description: Mescle arquivos do Excel usando Java em várias planilhas ou em uma única planilha. Mescle, combine ou concatene documentos do Excel em PDF, Imagens e HTML também.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Mesclagem de arquivos do Excel via Java" h2="Combine dois ou mais arquivos do Excel em uma única planilha usando o código Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca do Excel](/cells/java/) fornece várias maneiras de combinar pastas de trabalho com vários tipos de conteúdo, como fórmulas, imagens, dados, gráficos, etc., em um único documento de planilha. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e muito mais.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine arquivos do Excel com imagens e gráficos" %}}
A maneira mais simples de combinar dois arquivos do Excel com imagens e gráficos é chamando o [Pasta de trabalho.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) método. Permite mesclar arquivos do Excel de tipo semelhante em uma única planilha.
{{% blocks/products/pf/feature-page-code h3="Java Código para combinar arquivos do Excel" %}}

```cs
// carregar o primeiro arquivo do Excel
var book1 = new Workbook("with-charts.xlsx");
// carregar o segundo arquivo do Excel em uma instância separada
var book2 = new Workbook("with-images.xlsx");

// mesclar duas pastas de trabalho
book1.combine(book2);
// salve a pasta de trabalho de destino 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar vários arquivos do Excel" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) O método suporta a fusão de dados, estilo e fórmulas de um arquivo Excel em uma nova planilha do mesmo formato. É uma maneira eficiente de mesclar vários arquivos ao usar o cache. 
{{% blocks/products/pf/feature-page-code h3="Java Código para mesclar vários arquivos do Excel" %}}

```cs
// crie uma matriz (comprimento = 2)
String[] files = new String[2];
// especificar caminhos de arquivo a serem mesclados
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// mescle os arquivos para salvar o resultado
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar arquivos do Excel copiando planilhas" %}}
[Planilha.copiar](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)pode ser usado para copiar dados e formatação de uma planilha de origem para outra planilha dentro ou entre pastas de trabalho. O método usa o objeto de planilha de origem como parâmetro.
{{% blocks/products/pf/feature-page-code h3="Java Código para copiar planilhas entre pastas de trabalho" %}}

```cs
// Crie uma pasta de trabalho.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Crie outra pasta de trabalho.
Workbook excelWorkbook1 = new Workbook();

// Copie a primeira folha do primeiro livro para o segundo livro.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Salve o arquivo.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}