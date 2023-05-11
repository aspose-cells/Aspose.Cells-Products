---
title: Mesclar diferentes arquivos do Excel em um único em Java
description: Mescle arquivos do Excel usando Java em várias planilhas ou em uma única planilha. Mesclar, combinar ou concatenar documentos do Excel para PDF, Imagens e HTML também.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Mesclagem de arquivos do Excel via Java" h2="Combine dois ou mais arquivos do Excel em uma única planilha usando o código Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca Excel](/cells/pt/java/) fornece várias maneiras de combinar pastas de trabalho com vários tipos de conteúdo, como fórmulas, imagens, dados, gráficos, etc., em um único documento de planilha. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e mais.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine arquivos do Excel com imagens e gráficos" %}}
 A maneira mais simples de combinar dois arquivos do Excel com imagens e gráficos é chamando o método[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) método. Ele permite mesclar arquivos do Excel de tipo semelhante em uma única planilha.
{{% blocks/products/pf/feature-page-code h3="Java Código para Combinar Arquivos Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar vários arquivos do Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) O método suporta a fusão de dados, estilo e fórmulas de um arquivo do Excel em uma nova planilha do mesmo formato. É uma maneira eficiente de mesclar vários arquivos ao usar o cache.
{{% blocks/products/pf/feature-page-code h3="Java Código para Mesclar Vários Arquivos Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar arquivos do Excel copiando planilhas" %}}
[Planilha.cópia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) pode ser usado para copiar dados e formatação de uma planilha de origem para outra planilha dentro ou entre pastas de trabalho. O método usa o objeto de planilha de origem como parâmetro.
{{% blocks/products/pf/feature-page-code h3="Java Código para copiar planilhas entre pastas de trabalho" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de mesclagem suportados" subTitle="Usando Java, também é possível mesclar muitos outros formatos de arquivo, incluindo .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formato de arquivo da página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Ficheiro de Planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valores separados por tabulações" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Arquivo Binário da Pasta de Trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Ficheiro Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Modelo Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Modelo habilitado para macro do Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
